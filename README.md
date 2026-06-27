# CORS Exploit POC

A browser-based tool to detect **CORS misconfigurations** in web applications.

## ⚡ Quick Start

1. Open `index.html` in any browser
2. Enter a target URL (e.g., `https://api.example.com/user`)
3. Click **Exploit** or press `Enter`
4. View the exfiltrated response

## 🎯 How It Works

Sends a credentialed cross-origin request to test if the target reflects `Origin` headers with `Access-Control-Allow-Credentials: true`.

## ⚠️ Disclaimer

For **authorized security testing only**. Don't use against systems without permission.

## 📄 License

MIT © [Milan Gautam](https://github.com/Milan-Gautam)
