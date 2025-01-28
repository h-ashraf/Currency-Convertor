# 🌟 Currency Converter ReactJS Setup Guide 🌟

Follow this step-by-step guide to get your **Currency Converter** project up and running without a hitch! 🚀

---

## 🛠️ **Prerequisites**
Before starting, ensure you have:

- **Node.js** and **npm** installed on your computer.
- An account on [ExchangeRate-API](https://www.exchangerate-api.com/).

---

## 🔑 **Step 1: Get Your API Key**
1. **Sign Up**: Create an account at [ExchangeRate-API](https://www.exchangerate-api.com/).
2. **Generate Key**: Navigate to the **API Key** section and generate a new key.

> ⚠️ **Note**: The API is free but has a limited number of requests per day. Use it wisely!

---

## 📝 **Step 2: Insert Your API Key**

1. Open your project folder in **VS Code** (or any code editor).
2. Navigate to the file:  
   `components/ConverterForm.jsx`
3. Look for this line of code:  

   ```javascript
   const API_KEY = "YOUR-API-KEY";
4. Replace "YOUR-API-KEY" with your API key from ExchangeRate-API.

## 💻 Step 3: Install and Run**

1. Open the terminal in VS Code by pressing Ctrl + J (or Cmd + J on macOS).

2. Run the following commands:
    ``` npm install

    Installs all required dependencies. 📦
    ```npm run dev

    Starts the development server. 🌐

3. Open your browser and click the localhost link shown in the terminal to view your app. 🎉

## 🔍 Testing**

Test the app by converting different currencies. 💸

If something doesn’t work, ensure the API key is correctly added and check the browser console for errors. 🛠️
