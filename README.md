# Currency Converter

A simple web-based currency converter application that allows users to convert amounts between different currencies using real-time exchange rates.

## Features

- **Real-Time Exchange Rates**: Fetches live exchange rates using the [Currency API](https://github.com/fawazahmed0/currency-api).
- **Dynamic Dropdowns**: Automatically populates currency dropdowns with country codes.
- **Flag Display**: Displays country flags dynamically based on the selected currency.
- **Responsive Design**: Styled for a clean and user-friendly interface.

## Project Structure

app.js # Main JavaScript logic for the application ├── codes.js # Contains the list of country codes and their corresponding flags
├── index.html # HTML structure of the application ├── style.css # CSS for styling the application

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/currency-converter.git
   cd currency-converter
2. Open index.html in your browser.
3. Enter the amount, select the currencies to convert from and to, and click the "Get Exchange Rate" button.

#Dependencies
Font Awesome: Used for icons.
Currency API: Provides real-time exchange rates.

#Future Enhancements
Add support for historical exchange rates.
Include error handling for API failures.
Improve mobile responsiveness.

#License
This project is licensed under the MIT License. See the LICENSE file for details.

#Acknowledgments
Flags API: Used for displaying country flags.
Currency API: For providing exchange rate data.
Feel free to contribute to this project by submitting issues or pull requests!
