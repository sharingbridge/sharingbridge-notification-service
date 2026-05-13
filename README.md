# sharingbridge-notification-service

> Push notifications and alerts

## Overview

This repository contains the **Notification Service** - manages all user communications via push notifications, SMS, and email.

**Key Responsibilities:**
- 📱 Push notifications (Firebase FCM) to mobile apps
- 📧 Email notifications (order confirmations, updates)
- 💬 SMS notifications (for users without smartphones)
- 🔔 Real-time order status updates
- ⏰ Scheduled notifications and reminders
- 🌐 Multi-language notification templates
- 📊 Notification delivery tracking and analytics
- ⚙️ User notification preference management
- 🚦 Rate limiting to prevent spam

**Technology Stack:** Node.js with event-driven architecture (Redis Streams/PubSub for MVP, AWS SQS/SNS at scale) + Twilio (SMS) + Resend/SendGrid (Email)

For overall project context, see the [main SharingBridge repository](https://github.com/sharingbridge/sharingbridge).

## Repository Status

🚧 **Status:** Initial Setup  
📅 **Date:** January 9, 2026

## Getting Started

> Coming soon - Development setup instructions

## Contributing

See the [main repository's CALL_FOR_CONTRIBUTORS.md](https://github.com/sharingbridge/sharingbridge/blob/main/development/CALL_FOR_CONTRIBUTORS.md) for:
- How to contribute (technical and non-technical)
- Joining GitHub Discussions
- Submitting prompts and feature ideas

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Part of the [SharingBridge](https://github.com/sharingbridge/sharingbridge) ecosystem
