# 🌤️ Weather Email Automation using n8n

## 📖 Overview

This project automates weather reporting by fetching **real-time weather data** from the **Open-Meteo API**, processing the response using JavaScript, and sending formatted weather updates via **Gmail**.

The workflow runs automatically on a scheduled interval, eliminating the need for manual weather checks and ensuring timely email notifications.

---

## ✨ Features

* 🌦️ Automated weather monitoring
* ⏰ Scheduled workflow execution
* 🌐 Open-Meteo API integration
* 💻 JavaScript-based data processing
* 📧 Gmail email notifications
* ⚡ Fully automated no-code workflow
* 📍 Real-time weather updates

---

## 🏗️ Workflow Architecture

```text
Schedule Trigger
       │
       ▼
HTTP Request
       │
       ▼
JavaScript Code
       │
       ▼
Gmail Send Message
```

---

## 📸 Workflow Screenshot

The screenshot below illustrates the complete **n8n workflow**, where a **Schedule Trigger** automatically initiates the process, retrieves weather data from the **Open-Meteo API**, formats the information using **JavaScript**, and finally sends the weather report via **Gmail**.

<p align="center">
  <img src="Email.png" alt="Weather Email Automation Workflow" width="1000">
</p>

---

## ⚙️ How It Works

1. The **Schedule Trigger** starts the workflow automatically at the configured time.
2. The **HTTP Request** node fetches real-time weather information from the **Open-Meteo API**.
3. The **JavaScript Code** node extracts and formats the required weather details.
4. The **Gmail** node sends the formatted weather report to the specified email recipient.

---

## 💬 Example Weather Report

```text
Subject: Daily Weather Report ☀️

Hello,

Here is today's weather update:

🌡️ Temperature : 28°C
💨 Wind Speed  : 12 km/h
☁️ Condition   : Clear Sky

Have a great day!

Regards,
Weather Automation Bot
```

---

## 🛠️ Technologies Used

| Technology     | Purpose             |
| -------------- | ------------------- |
| n8n            | Workflow Automation |
| Open-Meteo API | Weather Data        |
| JavaScript     | Data Processing     |
| Gmail          | Email Notifications |

---

## 📂 Workflow Components

### 1️⃣ Schedule Trigger

* Starts the workflow automatically.
* Executes at predefined intervals.

### 2️⃣ HTTP Request

* Fetches real-time weather data.
* Connects to the Open-Meteo API.

### 3️⃣ JavaScript Code

* Processes API responses.
* Formats weather information for email.

### 4️⃣ Gmail Send Message

* Sends the formatted weather report.
* Delivers notifications directly to the recipient.

---

## 🎯 Applications

* 🌤️ Daily weather notifications
* 🏠 Smart home automation
* ✈️ Travel planning
* 📊 Weather monitoring systems
* 🌾 Agriculture weather updates
* 🏢 Office weather alerts

---

## 🚀 Future Improvements

* 🌍 Multiple city support
* ⚠️ Severe weather alerts
* 📱 SMS notifications
* 💬 WhatsApp integration
* 📈 Weather analytics dashboard
* 🗺️ Interactive weather maps
* 📅 Weekly weather forecast emails

---

## 📁 Project Structure

```text
Weather-Email-Automation/
│
├── assets/
│   └── workflow.png
│
├── workflow.json
│
├── README.md
│
└── LICENSE
```

---

## 📌 Requirements

* n8n
* Open-Meteo API
* Gmail Account
* Gmail Credentials configured in n8n

---

## ▶️ Getting Started

1. Clone this repository.

```bash
git clone https://github.com/your-username/Weather-Email-Automation.git
```

2. Open **n8n**.

3. Import the provided workflow (`workflow.json`).

4. Configure your **Gmail credentials**.

5. Set the desired schedule.

6. Activate the workflow.

7. Receive automated weather reports directly in your inbox.

---

## ⭐ If you found this project helpful, don't forget to give it a star!

