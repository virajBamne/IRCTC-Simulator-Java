# 🚂 IRCTC-Simulator-Java

**A complete console-based application simulating a simplified railway ticket booking service, built purely with Core Java.**

---

## ✨ Features

* **User Management:** Register and log in with unique usernames.
* **Train Search:** Find available trains between a specified source and destination.
* **Ticket Booking:** Reserve seats on a selected train, with automatic seat availability checks.
* **Ticket Cancellation:** Cancel an existing booking, which automatically frees up seats on the train.
* **Data Persistence:** Utilizes Java Collections (`List`, `Map`, `ArrayList`, `HashMap`) to manage train, user, and ticket data in-memory.

---

## 🛠️ Technology Stack

* **Language:** Java
* **Environment:** Console/Command-Line Application
* **Concepts:** Object-Oriented Programming (OOP), Data Structures (Lists, Maps), Scanner for Input.

---

## 🚀 How to Run Locally

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/IRCTC-Simulator-Java.git](https://github.com/YourUsername/IRCTC-Simulator-Java.git)
    cd IRCTC-Simulator-Java
    ```
2.  **Compile the Java Files:**
    Compile all `.java` files located in the `src` directory.
    ```bash
    javac *.java
    ```
    *(Note: Depending on your project structure, you might need to adjust the path or use an IDE like IntelliJ or Eclipse to run the main class.)*
3.  **Run the Application:**
    Execute the main class, `IRCTCAPP`.
    ```bash
    java IRCTCAPP
    ```

---

## 📐 Project Structure & Class Diagram

The system is organized around several key classes:

| Class | Responsibility |
| :--- | :--- |
| **`IRCTCAPP.java`** | Main entry point; handles all console I/O and user interaction. |
| **`UserService.java`** | Manages user registration, login, and the current session state. |
| **`BookingService.java`** | Manages train data, search logic, ticket creation, and cancellation. |
| **`User.java`** | Data model for a railway user. |
| **`Train.java`** | Data model for a train, including seat booking/cancellation logic. |
| **`Ticket.java`** | Data model for a booked ticket. |
