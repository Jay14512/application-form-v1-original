# Application Form (original)

A simple PHP application form created during my *PHP Basics* module.  
This version focuses on understanding **server-side validation**, **error handling**, and **basic file processing** without relying on external libraries or frameworks.

**Module:** PHP Basics  
**Goal:** Server-side validation & CSV handling  
**Status:** ✅ Completed  
**Version:** 1.0  
**Tech:** PHP, Bulma CSS  

---

## 📌 Project Overview

The goal of this assignment was to build an application form (`index.php`) that collects user data and validates all inputs using **vanilla PHP**. The form needed to show meaningful error messages, highlight invalid fields, and only accept submissions when all data met the validation rules.

Once validated, the information is stored in a CSV file, and the uploaded CV (PDF) is saved in a dedicated folder without overwriting existing files.

---

## ✨ Features

- Server-side input validation in PHP  
- Custom error messages for each field  
- Highlighting invalid inputs with visual feedback  
- PDF upload validation (type + name handling)  
- Preventing filename collisions  
- Storing submissions in a CSV file  
- Minimal, clean UI using Bulma  

---

## 🧪 Validated Fields

- First Name (min. 2 characters)  
- Last Name (min. 2 characters)  
- Email (valid format)  
- ZIP Code (numeric)  
- City  
- Region  
- Date of Birth (must be ≥ 18 years old)  
- CV Upload (PDF only)  
- General Terms and Conditions (required checkbox)  

---

## 🧠 What I Learned

- How to validate form inputs on the server side  
- How to securely handle file uploads in PHP  
- Working with CSV files for lightweight data storage  
- Managing error states and showing useful feedback  
- Avoiding file overwrites by generating unique filenames  

This project was my first step into backend logic and laid the foundation for the more structured **refactored version (v2)**.
