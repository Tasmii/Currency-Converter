
# Currency Converter

A simple web application for converting currencies using real-time exchange rates. The application allows users to input an amount, select the source and target currencies, and get the exchange rate instantly. The exchange rates are fetched from an online API.

## Features

- Convert currency amounts between different currencies.
- Real-time exchange rates fetched from a reliable API.
- Dropdown menus for selecting currencies with country flags.
- Swap functionality to quickly interchange source and target currencies.
- Responsive design suitable for different screen sizes.

## Live Demo

You can check out the live demo of the Currency Converter [here](https://your-live-demo-link.com).

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/currency-converter.git
   ```

2. Navigate to the project directory:

   ```bash
   cd currency-converter
   ```

3. Open the `index.html` file in your browser to use the Currency Converter.

## Files

- `index.html`: The main HTML file that contains the structure of the web application.
- `style.css`: The CSS file that contains the styles for the web application.
- `app.js`: The JavaScript file that handles the currency conversion logic and interacts with the API.
- `code.js`: An additional JavaScript file that might contain helper functions or additional logic.
- `README.md`: This file, providing an overview of the project.

## Usage

1. Open the `index.html` file in your browser.
2. Enter the amount you wish to convert.
3. Select the source currency from the "From" dropdown.
4. Select the target currency from the "To" dropdown.
5. Click the "Get Exchange Rate" button to see the converted amount.
6. Use the arrow icon to swap the source and target currencies.
7. The converted amount and the exchange rate will be displayed below.

## Code Overview

### HTML (`index.html`)

- The HTML file sets up the structure of the currency converter, including the form, input fields, dropdowns, and the swap icon.

### CSS (`style.css`)

- The CSS file styles the application, making it look clean and responsive. It includes styles for the form, buttons, dropdowns, and other elements.

### JavaScript (`app.js`)

- This JavaScript file contains the main logic for the currency converter. It handles fetching exchange rates from the API, updating the DOM with the conversion results, and swapping the currencies.

### JavaScript (`code.js`)

- This file is referenced but not detailed in the provided code. Ensure that it's correctly included if it contains necessary functionality.

## API

The application uses the [Currency API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies) to fetch real-time exchange rates.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## Acknowledgements

- [Font Awesome](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css) for the icons.
- [Flags API](https://flagsapi.com/) for the country flags.
- [Currency API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies) for the exchange rates.
