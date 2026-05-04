# 🚀 DevOps Project: Terraform + EC2 + Docker + Nginx + HTTPS

## 📌 Overview

This project demonstrates end-to-end deployment of a web application using DevOps practices on AWS.

## ⚙️ Tech Stack

* Terraform (Infrastructure as Code)
* AWS EC2 (Ubuntu)
* Docker (Containerization)
* Nginx (Reverse Proxy)
* Let's Encrypt (SSL)

## 🏗️ Architecture

User → Nginx → Docker Container

## 🚀 Implementation Steps

* Provisioned EC2 instance using Terraform
* Configured Security Groups (ports 22, 80, 443)
* Installed Docker and deployed application container
* Configured Nginx as reverse proxy
* Enabled HTTPS using Certbot

## 🔐 Security

* Restricted ports using Security Groups
* Enabled HTTPS encryption
* Used reverse proxy instead of exposing container directly

## 🧠 Challenges Faced

* Application not accessible due to missing route configuration
* Docker permission issues resolved by adding user to docker group
* SSL failure due to missing DNS configuration

## 📂 Project Structure

* main.tf → Terraform configuration
* .gitignore → ignored sensitive files

## 💬 Key Learnings

* Understanding of AWS networking (VPC, IGW, Security Groups)
* Hands-on experience with Docker and Nginx
* Practical implementation of HTTPS and deployment flow

