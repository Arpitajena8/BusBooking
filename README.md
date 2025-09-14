# BusBooking

A Java Swing-based desktop application for managing bus seat reservations.  
This project demonstrates GUI development with Swing, database connectivity using JDBC, and CRUD operations for booking management.

---

## ✨ Features

- **Seat Booking**: Reserve bus seats by entering customer details.  
- **Customer Details**: Capture customer name, mobile number, seat number, and journey date.  
- **Date Picker**: Integrated with `JDateChooser` for selecting travel dates.  
- **Booking Records**: Display all bookings in a table format.  
- **CRUD Operations**: Add, update, and delete bookings directly from the interface.  
- **Database Integration**: Uses JDBC for storing and retrieving booking details.

---

## 🛠 Tech Stack

- **Language**: Java  
- **GUI**: Swing (`JFrame`, `JTable`, `JPanel`, `JTextField`, `JButton`, etc.)  
- **Database**: MySQL (via JDBC)  
- **Date Picker**: `com.toedter.calendar.JDateChooser`  

---

## 📂 Folder Structure

BusBooking/
├── Booking.java # Main JFrame for bookings
├── Booking.form # GUI form definition (NetBeans)
├── busbook.form # GUI form (likely for bus details)
├── seat.form # GUI form (likely for seat management)
├── manifest.mf # Manifest file
├── build.xml # Ant build configuration
└── README.md # Documentation

yaml
Copy code

---

## ⚙️ Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Arpitajena8/BusBooking.git
   cd BusBooking
Open in NetBeans (recommended) or any Java IDE with Swing support.

Add Dependencies

MySQL Connector/J (JDBC driver)

JCalendar (toedter library for JDateChooser)

🗄 Database Setup
Install MySQL (or another supported DB).

Create a database:

sql
Copy code
CREATE DATABASE busbooking;
Create the booking table:

sql
Copy code
CREATE TABLE booking (
    id INT AUTO_INCREMENT PRIMARY KEY,
    customer_name VARCHAR(100),
    mobile_no VARCHAR(15),
    seat_no VARCHAR(10),
    journey_date DATE
);
Update DB connection details in Booking.java inside the Connect() method.

🚀 Build & Run
▶️ Using NetBeans
Open the project and press Run.

▶️ Using Command Line (Ant)
bash
Copy code
ant compile
ant run
🎯 Usage
Launch the application.

Enter Customer Name, Mobile Number, Seat No., and Date.

Click Add to save the booking.

View existing bookings in the table.

Use Update/Delete buttons to modify records.

📌 Future Enhancements
Implement seat availability validation.

Add bus route & schedule management.

Export bookings to PDF/Excel.

Add login/authentication for admins.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📜 License
This project is licensed under the MIT License.

pgsql
Copy code

Would you like me to also add a **"Screenshots" section** (with placeholder image links) so you can later drop in app screenshots?






You said:
