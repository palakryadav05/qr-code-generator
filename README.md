# 📷 QR Code Generator

A simple command-line tool that takes any URL and converts it into a QR code image — built with Node.js.

## ⚙️ How It Works

1. Run the app in your terminal
2. Enter any URL when prompted
3. It generates a `qr_img.png` QR code image
4. It also saves your URL to a `URL.txt` file

## 🛠️ Built With

- Node.js
- [Inquirer.js](https://www.npmjs.com/package/inquirer) — for the interactive terminal prompt
- [qr-image](https://www.npmjs.com/package/qr-image) — for generating the QR code
- fs (Node.js built-in) — for saving files

## 🚀 How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/https://palakryadav05/qr-code-generator.git
   ```

2. Navigate into the folder
   ```bash
   cd qr-code-generator
   ```

3. Install dependencies
   ```bash
   npm install
   ```

4. Run the app
   ```bash
   node index.js
   ```

5. Enter your URL when prompted and find your QR code saved as `qr_img.png`

## 📁 Project Structure

```
qr-code-generator/
├── index.js
├── package.json
├── .gitignore
├── qr_img.png      ← generated after running
└── URL.txt         ← generated after running
```

## 📌 Note

`qr_img.png` and `URL.txt` are generated at runtime — they won't exist until you run the app.

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
