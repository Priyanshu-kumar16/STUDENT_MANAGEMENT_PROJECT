# 📘 Student Management & Attendance System

A **Flask + MySQL** based web application for managing student data,
attendance, departments, and user authentication.

## 🚀 Project Overview

This is a Student Database Management System featuring: - Student CRUD
operations - Attendance management - Department module - Login/Signup
using Flask-Login - MySQL triggers for auditing - SQLAlchemy ORM

### Database

-   MySQL / MariaDB with Triggers

## 📦 Installation & Setup

### 1️⃣ Create Virtual Environment

    python -m venv venv
    venv\Scripts\activate   # Windows
    source venv/bin/activate  # Linux/Mac

### 2️⃣ Install Requirements

    pip install -r requirements.txt

### 3️⃣ Set Up MySQL Database

    CREATE DATABASE studentdbms;
    USE studentdbms;
    SOURCE students.sql;

### 4️⃣ Update DB URI in main.py

    app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql://root:@localhost/studentdbms'

### 5️⃣ Run Application

    python main.py

App will start at:

    http://127.0.0.1:5000/

## 📁 Project Structure

    main.py
    students.sql
    requirements.txt
    templates/
    static/

