# Day 13 — PHP Superglobals & Database Introduction

## What I practiced
- Working with superglobal variables
- Handling form data safely
- Understanding cookies and sessions
- Learning database fundamentals
- Exploring SQL and query types
- Reviewing PHP database connection methods

---

## Global vs Superglobal

### Global Variables
Defined outside functions.

Inside functions:
- Pass as parameter (clean approach)
- Use `global` keyword (less recommended)

⚠ Overusing globals creates hidden dependencies and makes debugging harder.

---

## Superglobals

Predefined PHP variables accessible everywhere.

Main ones:
- $_GET
- $_POST
- $_FILES
- $_SERVER
- $_COOKIE
- $_SESSION

Used to communicate with browser and server.

---

## $_GET

Retrieves query string parameters from URL.

Use cases:
- Search
- Filtering
- Pagination

⚠ Not suitable for sensitive data.

---

## $_POST

Sends data in request body.

Better for sensitive inputs like passwords.

⚠ POST alone is not security.
Requires:
- HTTPS
- Validation
- Protection against CSRF/XSS/SQLi

---

## isset()

Checks if variable exists and is not null.
Prevents undefined index warnings.

---

## $_FILES

Handles file uploads.

Important requirements:
- method="post"
- enctype="multipart/form-data"

Security measures:
- Validate type
- Limit size
- Rename files
- Store safely
- Block executable files

---

## $_SERVER

Provides request metadata:
- Request method
- IP address
- URL
- User agent
- File paths

Used for debugging and request handling.

---

## Cookie vs Session

### Cookie
Stored in browser.
Can be modified by user.

Important flags:
- httponly
- secure

---

### Session
Stored on server.
Session ID stored in cookie.

Used for:
- Login state
- Sensitive user data

Can be cleared using:
- unset()
- session_destroy()

---

# Database Fundamentals

## DBMS
Software managing databases:
- MySQL
- PostgreSQL
- SQL Server

---

## RDBMS
Stores related tables connected via keys.

Example:
- users
- orders
- products

Connected using foreign keys like user_id.

---

## SQL

Language used to manage relational databases.

Main query types:
- INSERT
- SELECT
- UPDATE
- DELETE

Each operation is called a Query.

---

## Database Structure Basics

### Character Set
Use utf8mb4 to support full Unicode and emojis.

### Primary Key
Usually:
- id column
- Primary Key
- Auto Increment

Ensures unique row identification.

---

### VARCHAR vs TEXT
- VARCHAR → Short text
- TEXT → Long text

---

### NULL vs NOT NULL
- NULL → Optional
- NOT NULL → Required

---

## PHP Database Connection Methods

1) mysql (deprecated)
2) mysqli (procedural or OOP)
3) PDO (recommended for professional architecture)

---

## Final Summary

Today I learned how PHP interacts with users via superglobals and forms, how state is managed using cookies and sessions, and how databases work conceptually using DBMS, RDBMS, and SQL.
This marks the real beginning of backend development.
