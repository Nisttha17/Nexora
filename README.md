# 🌆 Nexora – Intelligent Billboard Monitoring Platform

## 💡 Overview

Nexora is a Flutter-powered mobile application combined with a RESTful backend service that helps identify and report unauthorized or non-compliant billboards in urban areas.

The system aims to support cleaner city environments, reduce visual clutter, and assist municipal authorities in maintaining organized and sustainable public spaces.

Users can take photos of billboards and submit them through the mobile app. The backend processes the report, validates billboard information, and enables authorities to monitor and manage billboard compliance efficiently.

## 🚀 Key Features

📷 **Billboard Reporting** – Capture and upload billboard images directly from the mobile application.

📍 **Location Tracking** – Automatically records the geographical coordinates of each submission.

✅ **Authorization Verification** – Verifies billboard legitimacy using backend validation and stored records.

🔗 **REST API Connectivity** – Facilitates authentication, report submission, and data exchange between client and server.

🗺️ **Location-Based Monitoring** – Visualizes reported billboard locations for easier analysis and management.

🔔 **Notification System** – Sends alerts regarding newly reported or unauthorized billboards.

## 🧰 Technology Stack

| Layer               | Technologies               |
| ------------------- | -------------------------- |
| Mobile Application  | Flutter, Dart              |
| Backend Services    | Python / Node.js           |
| Database            | MySQL / MongoDB / Firebase |
| Storage             | AWS S3 / Firebase Storage  |
| APIs & Integrations | REST API, Google Maps API  |
| Version Control     | Git, GitHub                |

## ⚙️ Workflow

1. User signs in or creates an account.
2. A billboard image is captured through the mobile app.
3. GPS coordinates are automatically attached.
4. The report is submitted to the backend via REST APIs.
5. The system validates the billboard against authorized records.
6. The billboard is classified as valid or unauthorized.
7. A report is generated for administrative review and action.

## 🎯 Project Impact

✅ Simplifies identification of unauthorized billboards.

✅ Supports cleaner and more visually organized urban spaces.

✅ Assists authorities with data-driven monitoring and decision-making.

## 🌍 Future Scope

- Integrate AI-powered image analysis for automated billboard detection.
- Develop a dedicated administrative dashboard for city-wide monitoring.
- Enable real-time notifications for municipal departments and enforcement teams.
