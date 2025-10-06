# Offline Double Calculator

A stylish **double calculator** built with **HTML, CSS, and JavaScript**.  
This calculator works **offline**, shows numbers properly, handles decimal precision, and is ready to be used in **web browsers** or **Android WebView**.

---

## Features

- ✅ Two calculators side-by-side
- ✅ Numbers and operators displayed properly
- ✅ Stylish gradient buttons with hover effects
- ✅ Decimal calculations fixed (e.g., 0.1 + 0.2 = 0.3)
- ✅ Offline compatible
- ✅ Easy to use for Android WebView or browser

---

## Screenshots

![Calculator Screenshot](screenshot.png)  
*Replace `screenshot.png` with your actual screenshot.*

---

## How to Use

### In Browser:
1. Download the repository.
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge).
3. The calculator works offline without internet.

### In Android App (WebView):
1. Open **Android Studio** and create a new project.
2. Enable JavaScript in WebView:
   ```java
   webView.getSettings().setJavaScriptEnabled(true);
   webView.setWebViewClient(new WebViewClient());
   webView.loadUrl("file:///android_asset/index.html");
