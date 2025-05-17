# 📚 Library Management System

A modern web-based library management system built with React, TypeScript, and Tailwind CSS. This application helps libraries manage their book inventory, member registrations, and loan operations efficiently.

## 🌟 Features

### For Librarians
- Add and remove books from the catalog
- Register new members and librarians
- Issue and return books
- Track overdue books
- View complete member directory

### For Members
- Browse and search the book catalog
- Borrow available books
- View personal loan history
- Track current loans and due dates



## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/AddankiGanesh/library_management_system_python.git
cd library-management-system
```

2. Install dependencies
```bash
pip install bcrypt
```

3. Start the development server
```bash
python main.py
```





## 💾 Data Storage

The application uses browser's localStorage to persist data. The following data structures are maintained:

- Books: ISBN, title, author, total copies, available copies
- Members: ID, name, email, join date, role
- Loans: ID, member ID, ISBN, issue date, due date, return date

## 🔒 Security Features

- Password hashing for user accounts
- Role-based access control
- Session management
- Input validation and sanitization

## 📝 Business Rules

- Loan period: 14 days
- Books can only be issued if copies are available
- Members can only borrow one copy of a book at a time
- Overdue tracking for unreturned books

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



