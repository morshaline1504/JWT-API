

# JWT Authentication Lab 

This is a template-based Express.js project demonstrating **JWT-based authentication and authorization** without using a database. Users are stored in an in-memory array with hashed passwords using bcrypt.

---

## **Project Structure**



jwt-auth-lab/

├── server.js // Main application file

├── users.js // In-memory user storage

├── authMiddleware.js // Authentication & authorization logic

├── package.json

└── README.md


---

## **Users**

Two example users are included:

| ID | Username  | Password     | Role   |
|----|-----------|-------------|--------|
| 1  | admin     | admin123    | admin  |
| 2  | student   | student123  | student|

Passwords are hashed using `bcrypt`.

---

## **Installation**

1. Clone the repository:

```bash
git clone <https://github.com/morshaline1504/JWT-API>


Install dependencies:

npm install


Start the server:

node server.js


Server will run on http://localhost:3000
