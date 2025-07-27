
---

## 🔐 Admin Login
- Database Name : - hotel.sql
- user name : - Admin
- password  : - 1234
  
- Accessed via `/admin/` directory.
- Admins can view and manage room bookings, availability, customer info, and room categories.

---

## 💾 Database Setup
1. Start **XAMPP** and enable **Apache** and **MySQL**.
2. Open **phpMyAdmin** and create a new database (e.g., `hotel`).
3. Import the provided `hotel.sql` file to set up the tables.
4. Ensure `db.php` contains correct credentials (typically: `localhost`, `root`, `""` for no password).

---

## 🚀 How to Run
1. Copy the `Hotel` folder into `htdocs` of your XAMPP installation.
2. Start XAMPP and launch Apache & MySQL.
3. Visit `http://localhost/Hotel/` in your browser to access the system.
4. To access the admin panel: `http://localhost/Hotel/admin/`

---

## ✅ Features
### User Panel
- View available rooms
- Submit booking requests
- Browse hotel services

### Admin Panel
- Secure login for admin
- View and manage:
  - Room details
  - Bookings
  - Customer information
  - Room categories and availability

---

## 📄 Notes
- Default credentials may be provided in `admin` folder or `db.php` (you may configure them as needed).
- Images and styles are customizable in their respective directories.
- Ensure you have XAMPP installed to run the local server.

---

## 📌 Future Enhancements (Suggestions)
- Add email confirmation for bookings
- Implement payment gateway integration
- Add calendar-based booking view
- Enhance UI with modern CSS frameworks (e.g., Bootstrap, Tailwind)

---

## 📧 Contact / Credits
This project was developed as part of the **Final Year Project** requirement.  
For academic use only.

---
