# AWS_Escola_Da_Nuvem_Creating_an_AWS_Budget

## 🧩 Creating an AWS Budget with AWS Budgets

This lab provides a step-by-step guide on how to set up a spending budget on AWS using the AWS Budgets service. The activity includes creating the budget, configuring email alerts, and verifying the applied settings.

---

## 🎯 Lab Objectives

This lab teaches you how to:

- Access the AWS Budgets service via the AWS Management Console
- Create a budget with a custom limit
- Configure email alerts based on usage percentages
- Validate the budget creation and test automatic notifications

---

## 📘 Scenario

You are a beginner developer or student using AWS for learning and testing purposes.

To avoid billing surprises and keep your spending under control, it is essential to set up a budget with automatic alerts.

This lab simulates the creation of a simple budget with a limit of **US$ 10**, including an email notification triggered when **10%** of that amount has been consumed.

Submit a screenshot as proof that you have correctly configured the budget and the alert.

---

## ⚙️ What you do in practice

- Log in to the AWS Management Console
- Go to **Billing → Budgets**
- Click **Create budget**
- Choose **Customize (Advanced)**
- Fill in:
  - **Name:** `meu-budget-Renata-Wrobleski`
  - **Amount:** `10 USD`
  - **Period:** `Monthly`
- Create an alert:
  - **Threshold:** `10%`
  - **Type:** `Actual`
  - **Email:** your email address
- Finish by clicking **Create budget**

---

## 🏗️ Architecture

### Architecture Overview

![Architecture 1](https://github.com/user-attachments/assets/d8a11f8c-5c53-4cbf-86c5-ebfec99b8684)

![Architecture 2](https://github.com/user-attachments/assets/9c471b5d-4dca-4cb5-91df-d4efe6642abf)

![Architecture 3](https://github.com/user-attachments/assets/4b521d5a-b52d-4600-9e93-b676c1ca1e1c)

![Architecture 4](https://github.com/user-attachments/assets/f2af11ba-a368-435f-a72d-babc84b3fd9a)
