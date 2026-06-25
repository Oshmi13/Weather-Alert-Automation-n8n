

# Weather Email Automation using n8n

## Overview

This project automates weather reporting by fetching real-time weather data from the Open-Meteo API, processing the response using JavaScript, and sending weather updates via Gmail.

The workflow runs automatically on a schedule without any manual intervention.

## Features

- Automated weather monitoring
- Scheduled execution
- API integration with Open-Meteo
- JavaScript-based data processing
- Gmail notifications
- Fully automated workflow

## Workflow Architecture

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

## How It Works

1. Schedule Trigger starts the workflow automatically.
2. HTTP Request fetches weather data from the Open-Meteo API.
3. JavaScript processes and formats the weather information.
4. Gmail sends the weather report to the recipient.

## Technologies Used

- n8n
- Open-Meteo API
- JavaScript
- Gmail Integration

## Example Weather Report

Subject: Daily Weather Report

Temperature: 28°C
Wind Speed: 12 km/h
Weather Condition: Clear Sky

## Applications

- Daily weather notifications
- Smart home automation
- Travel planning alerts
- Weather monitoring systems

## Future Improvements

- Multiple city support
- Severe weather alerts
- SMS and WhatsApp notifications
- Weather forecast analytics dashboard

## Project Workflow

Schedule Trigger → Open-Meteo API → Data Processing → Gmail Notification

## Author

Oshmi Sisodia
