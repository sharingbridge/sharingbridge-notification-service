# sharebridge-notification-service

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

**Technology Stack:** Node.js with event-driven architecture (RabbitMQ/SQS) + Twilio (SMS) + Resend/SendGrid (Email)

For overall project context, see the [main ShareBridge repository](https://github.com/sharebridge/sharebridge).

## AI-Powered Development

This project uses AI-assisted development. Code and documentation are generated through prompts stored in the /prompting folder.

## Prompting Folder

The prompting/ folder contains:
- All prompts used to generate code for this component
- Feature requests and requirements in natural language
- AI model instructions and specifications
- Prompt templates for future development

**Transparency:** Anyone can see how features were specified and generated.  
**Reproducibility:** Use similar prompts to regenerate or modify components.  
**Collaboration:** Non-coders can contribute by writing or refining prompts.

## Repository Status

🚧 **Status:** Initial Setup  
📅 **Date:** January 9, 2026

## Getting Started

> Coming soon - Development setup instructions

## Contributing

See the [main repository's CALL_FOR_CONTRIBUTORS.md](https://github.com/sharebridge/sharebridge/blob/main/CALL_FOR_CONTRIBUTORS.md) for:
- How to contribute (technical and non-technical)
- Joining GitHub Discussions
- Submitting prompts and feature ideas

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Part of the [ShareBridge](https://github.com/sharebridge/sharebridge) ecosystem
