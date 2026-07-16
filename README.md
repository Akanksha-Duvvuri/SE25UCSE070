# File Upload and Storage Service

Upload a file / multiplefiles and it gets saved to the database

**Stack:** Express · MongoDB · JavaScript· EJS · CSS · BootStrap

---

## Features

|Feature|
|---|
|Upload files|
|View uploaded files|
|Download files|
|Delete files|
|Stores files metadata in a database|

---

## Project Structure

SE25UCSE070/
├── db
│   └── file.js
├── index.js
├── node_modules
├── package.json
├── package-lock.json
├── public
│   └── home.css
├── README.md
├── uploads
│   └── 84a04d1fd5130960bf1e85c6348d8ffe
└── views
    ├── home.ejs
    ├── new.ejs
    └── view.ejs

---

## Database Schema
```mongosh

    File ID
    Original Filename
    Stored Filename
    File Size
    MIME Type
    Upload Timestamp

```
---