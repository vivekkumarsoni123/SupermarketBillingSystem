# Supermarket Billing System

A **console-based Supermarket Billing System** written in **C++**, showcasing core **object-oriented programming (OOP)** and **file handling** skills. The system features two distinct user roles—Admin and Buyer—and employs basic file-based storage without a GUI.

---

##  Features

- **User Roles:**  
  - **Admin** — Add, modify, and view product entries.  
  - **Buyer** — Purchase items and generate bills in real-time.

- **Object-Oriented Design:**  
  - Demonstrates encapsulation, inheritance, and class hierarchy in C++.

- **Persistent Storage:**  
  - Uses file I/O to store and retrieve product details across sessions.

- **Efficient Lookup:**  
  - Enables quick searching of products to calculate bill totals.

---
## Screen Shots 
<img width="1146" height="985" alt="image" src="https://github.com/user-attachments/assets/7a115af4-bc71-42d3-babb-937e6f6868fb" />
<img width="1143" height="947" alt="image" src="https://github.com/user-attachments/assets/6e1d0a51-cbed-4a88-baaa-50191bf55922" />

```
##  Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/vivekkumarsoni123/SupermarketBillingSystem.git
   cd SupermarketBillingSystem
````

2. **Compile the code**

   ```bash
   g++ Supermarket.cpp -o supermarket
   ```
3. **Run the program**

   ```bash
   ./supermarket
   ```
4. **Usage Flow**

   * As **Admin**, select option to add or update products.
   * As **Buyer**, purchase items by entering product ID and quantity — the bill is computed instantly.

---

## Code Structure

```
SupermarketBillingSystem/
├── Supermarket.cpp   # Main application logic, class definitions, and file I/O
├── database.txt      # Stores product information persistently
└── README.md         # This documentation
```

---

## Limitations & Future Enhancements

* **Current Limitations:**

  * Console interface only, without GUI.
  * No error-handling for invalid inputs or file corruption.
  * Billing logic is straightforward and not optimized for large datasets.

* **Future Improvements:**

  * Build a UI using Qt or similar framework.
  * Migrate persistence to databases like SQLite or MySQL.
  * Incorporate product search, categories, and discount logic.

---

## Why It Matters

This project demonstrates mastery in **OOP fundamentals**— a key requirement in software engineering roles at companies like Amazon, which highly value strong CS foundations in C++ and structured programming.

---

## Author

**Vivek Kumar Soni**

* [GitHub](https://github.com/vivekkumarsoni123)

