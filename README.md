# diary-remainder-app

## Tech Stack
- **Backend:** Node.js with Express.js
- **Database:** MongoDB
- **Frontend:** Android - kortlin

## Features

### Diary Page
- Input fields:
  - **Time** (String input for custom time entry)
  - **Data** (Text area for diary entry)
- **Buttons:**
  - View history
  - View previous day's entry

### To-Do / Reminder Page
- Ability to **add/book events**
- **Reminders & Alarms** for events
- Edit and delete events
- Notifications for reminders

## Backend (Node.js + MongoDB)
- **Endpoints:**
  - `/diary/add` (POST) - Add diary entry
  - `/diary/history` (GET) - Fetch previous entries
  - `/diary/:date` (GET) - Fetch entry for a specific date
  - `/todo/add` (POST) - Add a new event
  - `/todo/:id` (PUT) - Edit event
  - `/todo/:id` (DELETE) - Delete event
  - `/todo/upcoming` (GET) - Fetch upcoming events

## Additional Features (Future Enhancements)
- **Search & Filter** for diary entries
- **Category Tags** for diary and events
- **Cloud Sync & Backup**
- **Voice Notes Support** for diary
- **Dark Mode**
- **Biometric Lock for Security**

## Next Steps
1. Setup MongoDB schema for diary entries and reminders.
2. Develop REST APIs in Node.js.
3. Integrate APIs with the Android app.
4. Implement notification system for reminders.
5. Design and implement UI/UX for seamless experience.

