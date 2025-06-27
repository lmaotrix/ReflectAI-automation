# Power Automate Notification Flow

This flow sends a push notification to remind the user to log their daily reflections. When the notification is tapped on a mobile device, it opens a Microsoft Form for follow-up.

---

## 🚀 How to Import the Flow

1. Download `send-notification-flow.zip` from this repository.
2. Go to [Power Automate](https://make.powerautomate.com).
3. In the left menu, click **Import**.
4. Upload the `.zip` file.
5. Reconnect all required services during import:
   - Power Apps Notifications
   - Microsoft Forms
   - AI Builder (if applicable)

---

## 📱 Get It Working on Your Phone

To receive and open notifications on your phone, follow these steps:

### 1. Install the Power Automate mobile app
- **iOS**: [Download from App Store](https://apps.apple.com/app/microsoft-power-automate/id1408018998)
- **Android**: [Download from Google Play](https://play.google.com/store/apps/details?id=com.microsoft.flow)

### 2. Sign in with the **same Microsoft account** you used to import the flow.

### 3. Allow notifications:
- When prompted, grant **notification permission** to the Power Automate app.
- You can also check manually in your phone's settings under:
  - **iOS**: Settings > Notifications > Power Automate
  - **Android**: Settings > Apps > Power Automate > Notifications

### 4. Trigger the flow (manually or automatically):
- When the flow runs, it will send a **push notification** to your phone.
- Tapping the notification opens the configured **Microsoft Form**.

💡 Tip: You can customize the form URL inside the flow to point to your own form or external survey.

---

## 🔧 Requirements

- Microsoft Power Automate account
- Power Automate mobile app installed
- Microsoft Forms access
- Power Apps Notifications connector (included in most Microsoft 365 plans)

---

## 📄 License

MIT (or replace with your own if you're distributing commercially).

---

## 📝 Notes

- You can adapt this flow for use cases like:
  - Daily journaling reminders
  - Feedback collection
  - Mobile alerting for specific events (e.g., mood check-ins, status updates)

- For questions or support, open an issue on this repository.
