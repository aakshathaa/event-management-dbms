# 🎫 Event Ticket Management System (EventHub)

This project is a **web-based application** designed to simplify event ticket booking for users and management for organizers. It's built using PHP, MySQL, HTML, CSS, and JavaScript.

## 📝 About the Project

EventHub is your one-stop solution for:
- Browsing available events in Bangalore
- Booking tickets online
- Securely making payments
- Tracking your bookings

Organizers can also:
- Add or manage events
- Monitor ticket availability
- Track payments

The system features **real events from Bangalore (January-March 2025)** and is ideal for small to large-scale events like cultural fests, workshops, or conferences.

---

## 📁 Features

### For Attendees
- 🧾 Register and log in
- 🔍 Search and view events
- 🛒 Book tickets in real-time
- 💳 Make secure payments
- 📜 View booking history

### For Organizers
- 🎉 Create and update events
- 🎫 Manage ticket categories
- 📈 Track bookings and revenue

---

## ⚙️ How to Run the Project

### 🧑‍💻 Requirements

Make sure you have these installed:
- PHP 7.4 or higher
- MySQL 5.6 or higher
- Apache Server (XAMPP/LAMP recommended)
- A web browser (Chrome, Firefox)

### 🛠️ Setup Instructions

1. **Clone this Repository**
   ```bash
   git clone https://github.com/your-username/eventhub.git
   ```

2. **Move the Project to Your Server Directory**
   - If you're using XAMPP, move it to `htdocs` folder

3. **Start Apache and MySQL**
   - Open your control panel and start both services

4. **Import the Database**
   - Open phpMyAdmin
   - Create a database (e.g., `eventmanage`)
   - Import the `dbms.sql` file provided in the repo

5. **Run the Project**
   - Go to your browser and type: `http://localhost/eventhub`

---

## 🔐 Login Credentials

### Admin Access
- **Username:** `admin`
- **Password:** `admin123`

### Test User Accounts
- **Username:** `amitkumar` **Password:** `ak123456`
- **Username:** `priyasharma` **Password:** `ps123456`

---

## 💻 Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
- **Backend:** PHP
- **Database:** MySQL
- **Server:** Apache (XAMPP)

---

## 🚀 Future Enhancements

- Email notifications
- Payment gateway integration
- Mobile app development
- QR code tickets
