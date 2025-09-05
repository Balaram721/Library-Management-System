# 📚 Library Management System  

A simple **Library Management System** built using **Python (Tkinter + SQLite)**.  
This project provides a GUI-based solution for managing books, members, and loan records in a small library setup.  

## ✨ Features  
- **Books Management**
  - Add new books with title, author, and quantity  
  - Delete books (restricted if there are active loans)  
  - View all available books  

- **Members Management**
  - Add new members with name, email, and phone  
  - Delete members (restricted if they have active loans)  
  - View all registered members  

- **Loans Management**
  - Create new loans (assign book to a member)  
  - Return books and update loan status  
  - View active and returned loans  

---

## 🛠 Tech Stack  
- **Python 3**  
- **Tkinter** → for GUI  
- **SQLite3** → for database management  

---

## 🚀 How to Run  

1. Clone the repository:
   ```bash
   git clone https://github.com/Balaram721/LibraryManagementSystem.git
   cd LibraryManagementSystem
2. Run the program:
    ```bash
    python library.py
3. The application window will open, and you can start managing the library.

   
## 📂 Project Structure
   
    LibraryManagementSystem/
    │── library.py         # Main application (Tkinter + SQLite)
    │── library.db         # SQLite database (auto-created)
    │── README.md          # Project documentation
    │── requirements.txt   # Dependencies (optional)
    │── .gitignore         # Ignore cache/db files

## 🔮 Future Improvements
Add due date and fine calculation system
Implement user authentication (librarian vs admin)
Export reports (PDF/CSV) for loans and members
Migrate backend to Flask/Django for web version


## 📜 License
This project is licensed under the MIT License.
