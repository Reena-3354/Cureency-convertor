# Currency Converter
A simple currency converter web application built using HTML, CSS, and JavaScript. It uses the [ExchangeRate API](https://exchangerate-api.com/) to fetch live currency exchange rates.
## Features
- Convert between multiple currencies
- Real-time exchange rates
- Simple and responsive UI
- Error handling for invalid input

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/currency-converter.git
    ```
2. Navigate to the project directory:
    ```bash
    cd currency-converter
    ```
3. Open `index.html` in your browser.

## API Key Setup (If required)
- This project uses **ExchangeRate API**. Ensure you have an API key from their website if necessary.
- Update the API URL in `script.js` like this:
    ```javascript
    const response = await fetch('https://api.exchangerate-api.com/v4/latest/USD');
    ```

## Project Structure
```bash
currency-converter/
├── index.html
├── style.css
├── script.js
└── README.md
