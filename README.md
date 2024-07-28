# CRUD(create, read, update, delete)System

## Overview

This project is a simple CRUD (Create, Read, Update, Delete) system implemented using Flask, Python, and MongoDB. It provides a basic web interface to manage a collection of items (e.g., users, products, tasks).

## Features

- Create new items
- Read and display items
- Update existing items
- Delete items
- User-friendly web interface built with Bootstrap

## Technologies Used

- Flask: A lightweight WSGI web application framework in Python.
- MongoDB: A NoSQL database for storing data.
- PyMongo: A Python distribution containing tools for working with MongoDB.
- Bootstrap: A popular CSS framework for responsive web design.

## Installation

### Prerequisites

- Python 3
- MongoDB

### Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Huzaifa17/CRUD-Create-read-update-delete-System
   cd CRUD-Create-read-update-delete-System
   
2. **Create a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   
3. **Install Dependencies:**
   ```bash
   pip install -r Flask, pymongo

4. **Setup MongoDB:**
   1.Ensure MongoDB is installed and running on your local machine or accessible via a connection string
   
   2.Update the MongoDB connection URI in app.py

