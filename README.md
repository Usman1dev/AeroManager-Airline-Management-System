# ✈️ AeroManager – Airline Management System

A high-performance C++ console application designed to simulate a real-world airline ecosystem. This project integrates **Object-Oriented Programming (OOP)** with advanced **Data Structures & Algorithms (DSA)** to handle flight scheduling, passenger prioritization, and route optimization.

---

## 🚀 Key Features
- **Passenger Portal:** Registration, login, and profile management.
- **Flight Engine:** Add, update, delete, and search flights using optimized tree structures.
- **Dynamic Booking:** Real-time seat allocation with an automated **Waitlist System**.
- **Priority Boarding:** Logic-based boarding queues for First Class and frequent flyers.
- **Smart Routing:** Finds the shortest/cheapest path between cities using **Dijkstra’s Algorithm**.
- **Persistence:** Full file-handling support to save and load data across sessions.
- **System Integrity:** Stack-based **Undo** functionality for administrative changes and activity logging.

---

## 🧠 Technical Architecture

### 🛠 Data Structures & Efficiency
| Feature | Data Structure | Why? |
| :--- | :--- | :--- |
| **Flight Search** | Binary Search Tree (BST) | Ensures $O(\log n)$ search time for flight IDs. |
| **Route Optimization** | Graph (Adjacency List) | Models cities as nodes and flights as weighted edges. |
| **Waitlist** | Queue | Processes booking requests in Fair (FIFO) order. |
| **Boarding Queue** | Priority Queue | Sorts passengers by ticket tier/loyalty status. |
| **Undo System** | Stack | Tracks the last state for quick $O(1)$ reversals. |
| **Activity Logs** | Linked List | Provides efficient $O(1)$ insertion for historical logs. |

### 💎 OOP Principles Applied
* **Encapsulation:** Protecting passenger PII and flight internals via private members and getters/setters.
* **Inheritance:** Specialized flight types (e.g., `InternationalFlight`, `DomesticFlight`) extending a base `Flight` class.
* **Polymorphism:** Overriding cost calculation methods for different ticket tiers.
* **Abstraction:** Using abstract classes to define a blueprint for various Manager modules.

---

## 📁 Project Structure
```text
src/
├── ds/          # Custom implementations of Graphs, Trees, and Queues
├── managers/    # Logic for Flight, Booking, and User management
├── models/      # Class definitions (User, Flight, Ticket, etc.)
├── ui/          # Console-based interface and menu logic
└── Main.cpp     # Application entry point
data/            # .txt or .csv files for data persistence
```
---
## Working Screenshots:
<br>

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/e06bdd3f-39a5-46df-9c14-2e1f2a4276c8" width="100%" alt="Screen 1">
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/1d132e4b-8724-4598-9b6e-6d70c2bf3cc4" width="100%" alt="Screen 2">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/ee8fa55e-7d28-4671-8b4d-d3a5f2935e99" width="100%" alt="Screen 3">
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/10c3d08b-f228-4e85-a1b3-bd623040d957" width="100%" alt="Screen 4">
    </td>
  </tr>
</table>

<br>

---

## 👨‍💻Author

**🔹Muhammad Usman Khan**<br>
  GitHub: https://github.com/Usman1dev<br>
  LinkedIn: https://www.linkedin.com/in/usman0310<br>
**🔹Muhammad Bilal**<br>
  GitHub: https://github.com/codeBilal-exe

