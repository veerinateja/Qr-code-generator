# 🧠 QR Code Generator using Node.js

This is a simple Node.js project that generates a **QR code image** from any user-provided URL.  
It was built to understand how Node.js handles **modules, user input, and file systems**.

## 🔧 Technologies Used
- **Node.js**
- **Inquirer** (for user input)
- **qr-image** (for QR code generation)
- **fs** (for file handling)

## 🚀 How It Works
1. The user is prompted to enter a URL.  
2. The app generates a QR code for that URL.  
3. The QR code is saved as an image file (`qr_img.png`).

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/your-username/qr-code-generator.git

# Navigate to the project folder
cd qr-code-generator

# Install dependencies
npm install inquirer qr-image

#▶️ Run the Project
node index.js
