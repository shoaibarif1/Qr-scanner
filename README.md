# QR Code Generator using Node.js

This project is a **simple and interactive QR Code Generator** built using **Node.js**. It prompts the user to enter a URL and generates a **QR code image** of the provided URL. Additionally, it stores the entered URL in a text file for future reference.

---

## 🚀 Features

- **Interactive User Input:** Uses the `inquirer` package to prompt the user for a URL.  
- **QR Code Generation:** Uses the `qr-image` package to generate a QR code.  
- **File Storage:** Uses the native `fs` (File System) module to:
  - Save the QR code image as **`qr_img.png`**.
  - Save the entered URL as **`URL.txt`**.  
- **Error Handling:** Handles any unexpected errors gracefully.  

---

## 🛠️ Technologies Used

- **Node.js**: JavaScript runtime environment.  
- **Inquirer**: Interactive command-line prompt library.  
- **QR-Image**: QR code generation library.  
- **FS (File System)**: Native Node.js module to handle file operations.  

---

## 🗃️ Project Structure

