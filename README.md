#  StockTrackPro – C++ Stock Management System

**StockTrackPro** is an in-development C++ application designed to manage inventory efficiently for small businesses. The goal is to offer a simple yet powerful CLI-based system for tracking stock, adding/removing items, and monitoring inventory status.

>  **Status:** In Development  
> **Language:** C++  
>  **IDE:** Replit (hosted)  
>  [Live Project on Replit](https://replit.com/@shivampathak31/StockTrackPro)

---

##  Key Features (Planned)

-  Add new stock items with name, ID, price, and quantity
- Update item quantities (restock or sell)
- Delete or retire items
- View full inventory list
- File-based persistent storage (coming soon)
- Inventory summary and value tracking (coming soon)
- Sales report generation (planned)

---

##  Project Structure


StockTrackPro/
│
├── main.cpp              # Entry point for the application
├── inventory.cpp         # Inventory logic (add/remove/update)
├── inventory.h           # Inventory class declaration
├── item.cpp              # Stock item logic
├── item.h                # Item class declaration
├── README.md             # Project documentation
└── generated-icon.png    # Replit project icon


---

##  How to Run

If you're using **Replit**:
1. Click the "Run" button at the top of the Replit page  
2. Follow CLI prompts to interact with the inventory

If you're compiling locally:
g++ main.cpp item.cpp inventory.cpp -o StockTrackPro
./StockTrackPro
---

## Current Progress

| Module            | Status       |
|-------------------|--------------|
| Item Class        |  Completed |
| Inventory Class   | Completed |
| CLI Menu System   | Completed |
| Persistent Storage| In Progress |
| Sales Reporting   |  Not Started |

---

## Future Ideas

- GUI version using Qt or C++/CLI
- Database integration (SQLite or MySQL)
- Admin authentication and login system
- Search and filter features

---

##  Author

**Shivam Pathak**   
🔗 [GitHub](https://github.com/shivampathak31) | [Replit Profile](https://replit.com/@shivampathak31)

---

##  License

None
