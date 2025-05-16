# Currency Converter 🌍💱

A simple and elegant currency converter web application that lets users convert amounts from one currency to another using real-time exchange rates from the [Currency API](https://github.com/fawazahmed0/currency-api).
The application also displays country flags based on the selected currencies.

---


## 🔧 Features

- Real-time currency conversion using an open-source API.
- Supports multiple currencies globally.
- Automatically sets USD to INR as default for convenience.
- Displays national flags for selected currencies using FlagsAPI.
- Clean and responsive UI with Font Awesome icons.

---

## 💻 Tech Used

- **HTML5** – for page structure  
- **CSS3** – for styling and responsive layout  
- **JavaScript (Vanilla JS)** – for API interaction and dynamic behavior  
- **Fawaz Ahmed Currency API** – for real-time exchange rates  
- **FlagsAPI** – to fetch country flags  
- **Font Awesome** – for UI icons

---

## 📁 Project Structure
```
Currency-Converter/
│
├── index.html # Main HTML structure
├── style.css # Styling for the app
├── app.js # JS logic to fetch and display currency rates
├── codes.js # Stores country-code mapping for flags
├── Assets/ # Image used in the project

```
## 🚀 How to Use

1. Clone or download this repository.
2. Make sure you have internet access (to load external APIs and fonts).
3. Open `index.html` in any modern web browser.
4. Enter the amount to convert.
5. Choose the source ("From") and target ("To") currencies.
6. Click **Get Exchange Rate**.

---

## 🔗 API Used

- [Fawaz Ahmed Currency API (via jsDelivr CDN)](https://github.com/fawazahmed0/currency-api)
  - Endpoint example: `https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/usd/inr.json`
- [Flags API](https://flagsapi.com/)
  - Used for displaying country flags next to currency selectors.

---

## 📌 Notes

- If you see a `404 Not Found` error for the currency API, ensure the URL structure is correct and the currencies exist in the dataset.
- If flags are not displaying, double-check the `countryList` mapping and the URL format used with FlagsAPI.


