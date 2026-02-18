# # 🪙 Coin Change Dynamic Programming API

A simple and interactive  web application that solves the classic Coin Change Problem using Dynamic Programming (DP).
This project provides both a REST API and a browser-based HTML interface to calculate the minimum number of coins required to make a given amount.

---

## 🚀 Features

* ✅ Dynamic Programming solution for Coin Change problem
* ✅ REST API support (JSON requests)
* ✅ User-friendly HTML form interface
* ✅ Input validation for coins and amount
* ✅ Works in browser or API testing tools (Postman / Thunder Client)

---

## 🧠 Problem Statement

Given a list of coin denominations and a target amount, the application calculates:

👉 Minimum number of coins needed to make that amount

If the amount cannot be formed, the result will be -1.

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* Body-parser
* JavaScript (ES Modules)
* Dynamic Programming (Algorithm)

---

## 📂 Project Structure

```
coin-change-api/
│
├── server.js        # Main Express server
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/coin-change-api.git
cd coin-change-api
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Run Server

```bash
node server.js
```

Server will start at:

```
http://localhost:3000
```

---

## 🌐 Usage

### ▶️ Browser Interface

Open:

```
http://localhost:3000/coin-change
```

Enter:

* Coins (comma separated)
* Amount

Click Calculate to see result.

---

### ▶️ API Endpoint

**POST /coin-change**

#### Example JSON Request

```json
{
  "coins": [1, 2, 5],
  "amount": 11
}
```

#### Example Response

```json
{
  "minimumCoins": 3
}
```

---

## 🧮 Algorithm Used

This project uses Dynamic Programming (Bottom-Up approach):

* Create DP array of size `amount + 1`
* Initialize with Infinity
* Build solution using previously computed values
* Time Complexity: O(N × Amount)

---

## 💡 Learning Outcomes

* Understanding Dynamic Programming concepts
* Building REST APIs using Express
* Handling form and JSON requests
* Backend logic integration with frontend UI

---


