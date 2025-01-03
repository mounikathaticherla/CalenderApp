# Calendar Application

## Overview
The **Calendar Application** is a React-based project designed to allow users to view and manage past and upcoming communications. It features a dynamic calendar interface for scheduling and tracking interactions with companies. The application is styled with **Tailwind CSS** for a responsive and modern user experience.

---

## Features

### Calendar Interface
- View communications:
  - **Past Communications**: Displays dates and methods of previous interactions.
  - **Upcoming Communications**: Shows scheduled dates and methods for future interactions.
- Interactive calendar:
  - Click on a date to add a new communication.
  - Click on an event to view details or edit/delete it.

### Event Management
- Add, edit, or delete communication events.
- Events include:
  - **Title**: The name of the communication.
  - **Description**: Notes about the communication.
  - **Date**: The scheduled date.

### Responsive Design
- Adapts seamlessly to desktop and mobile devices.

---

## Tech Stack
- **React**: Frontend framework for building the UI.
- **FullCalendar**: Library for calendar functionality.
- **Tailwind CSS**: Utility-first CSS framework for styling.

---

## Installation

### Prerequisites
- **Node.js** (v14 or higher)
- **npm** (v6 or higher)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/calendar-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd calendar-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## Folder Structure
```
src/
├── components/
│   ├── CalendarView.js   # Calendar interface component
├── App.js                # Root component
├── index.js              # Entry point
├── index.css             # Tailwind CSS setup
├── tailwind.config.js    # Tailwind CSS configuration
```

---

## Usage

1. **View Events**:
   - See past and upcoming communications on the calendar.

2. **Add Events**:
   - Click on a date to create a new communication event.

3. **Edit/Delete Events**:
   - Click on an existing event to edit its details or delete it.

---

## Customization

### Styling
- Modify the `tailwind.config.js` file to extend the default theme or add custom styles.

### Backend Integration
- Replace static event data with API calls to fetch real-time communication details.

---

## Future Enhancements
1. **Recurring Events**:
   - Add support for recurring communication schedules.
2. **Notifications**:
   - Show reminders for upcoming or overdue communications.
3. **Event Filtering**:
   - Allow users to filter events by type or date range.

---

## Contribution Guidelines
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact
For any questions or issues, please reach out to:
- **Name**: Mounika Thaticherla
- **Email**: mounikathaticherla@gmail.com
- **GitHub**: [https://github.com/mounikathaticherla](https://github.com/your-username)

