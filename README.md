# 🚗 WhatNext Vision Motors

## Salesforce Vehicle Ordering and Dealership Management System

> A Salesforce-based CRM application for managing vehicles, customers, dealers, vehicle orders, test drives, service requests, reports, and dashboards.

---

## 📌 Project Overview

**WhatNext Vision Motors** is a Salesforce-based Vehicle Ordering and Dealership Management System developed to automate and simplify dealership operations.

The system provides a centralized platform for managing:

- 🚘 Vehicle details
- 👤 Customer information
- 🏢 Dealer information
- 📦 Vehicle orders
- 🚗 Test-drive schedules
- 🔧 Vehicle service requests
- 📊 Reports and dashboards

Salesforce automation is used to reduce manual work, validate vehicle stock, assign dealers, update order status, and send test-drive reminders.

---

## 🎯 Objectives

The main objectives of this project are:

- To automate vehicle ordering and dealership management
- To maintain vehicle inventory efficiently
- To validate vehicle stock before placing an order
- To automatically assign dealers to customers
- To manage customer and dealer information
- To schedule vehicle test drives
- To send automated test-drive reminders
- To track vehicle order status
- To generate useful reports and dashboards
- To reduce manual errors and improve efficiency

---

## ⭐ Key Features

### 🚘 Vehicle Management

- Add new vehicles
- Update vehicle information
- Maintain vehicle price and stock
- Track vehicle availability
- Manage vehicle status

### 👤 Customer Management

- Add customer details
- Store customer contact information
- Manage customer preferences
- Maintain customer records

### 🏢 Dealer Management

- Add dealer information
- Store dealer location
- Maintain dealer contact details
- Automatically assign dealers to orders

### 📦 Vehicle Order Management

- Create vehicle orders
- Validate vehicle stock
- Prevent orders when vehicles are out of stock
- Track order status
- Automatically update vehicle stock

### 🚗 Test Drive Management

- Schedule test drives
- Store test-drive details
- Track test-drive status
- Send automatic reminders before the scheduled test drive

### 🔧 Service Request Management

- Create service requests
- Track service request status
- Maintain customer vehicle service information

### 📊 Reports and Dashboards

The system provides reports and dashboards for:

- Vehicle inventory
- Vehicle orders
- Sales information
- Customer information
- Dealer information
- Test-drive information

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Salesforce | CRM Platform |
| Salesforce Lightning | User Interface |
| Custom Objects | Data Management |
| Salesforce Flow | Process Automation |
| Apex | Backend Logic |
| Apex Trigger | Automated Processing |
| Batch Apex | Bulk Processing |
| Scheduled Apex | Scheduled Processing |
| Validation Rules | Data Validation |
| Reports | Data Analysis |
| Dashboards | Data Visualization |

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │      Customer       │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Vehicle Order     │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Stock Validation   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Dealer Assignment  │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Order Processing   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Reports & Dashboard │
                    └─────────────────────┘
