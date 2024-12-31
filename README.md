
# Currency Comparison and Conversion Web App

## Overview

This is a currency comparison and conversion web application built using HTML, CSS, and JavaScript. It allows users to:
- Compare an amount in a given currency against several common currencies.
- Convert amounts between various currencies, including a custom selection.
- View country details based on the currency (including country name, population, and GDP).
- Receive AI-generated trading advice for currency conversions.

The application uses real-time exchange rate data from the [Fixer.io API](https://fixer.io/) and country data from the [REST Countries API](https://restcountries.com/). Additionally, it integrates AI-powered trading advice via [Hugging Face API](https://huggingface.co/), specifically the [Qwen2.5-Coder-32B-Instruct Model](https://huggingface.co/Qwen/Qwen2.5-Coder-32B-Instruct).

## Features

- **Currency Comparison**: Compare a given amount in one currency against several other common currencies.
- **Currency Conversion**: Convert an amount from one currency to another with real-time exchange rates.
- **Country Information**: Display country details (e.g., population, GDP) for the selected currency.
- **AI Trading Advice**: Receive trading advice from an AI model on whether to buy, sell, or hold based on the currency pair and conversion amount.
- **Dark Theme**: The app uses a dark theme for a modern and sleek user experience.

## Technologies Used

- **HTML**: Used for the structure of the web pages.
- **CSS**: For styling and layout of the components.
- **JavaScript**: To fetch live data from APIs, handle user input, and perform currency conversion and comparison.
- **APIs**:
  - **Fixer.io API**: Provides real-time exchange rate data.
  - **REST Countries API**: Retrieves country data based on currencies.
  - **Hugging Face API**: Provides AI-generated trading advice.

## Demo

You can view the live demo of the app here: [https://thevirus-limiter.github.io/currency-exchange/](https://thevirus-limiter.github.io/currency-exchange/)
## Installation

To run the project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/TheVirus-Limiter/currency-exchange.git
    ```

2. Navigate to the project folder:

    ```bash
    cd currency-exchange
    ```

3. Open the `index.html` file in your preferred browser:

    ```bash
    open index.html  # On macOS
    # OR
    start index.html # On Windows
    # OR
    xdg-open index.html # On Linux
    ```

No additional setup or server is required as the app is static and uses external APIs to fetch data.

## How to Use

1. **Input Amount**: Enter the amount of currency you wish to compare or convert.
2. **Select Currency**: Choose the currency you want to compare or convert from the dropdown list.
3. **Compare**: Click the "Compare" button to see the equivalent amount in several common currencies.
4. **Custom Conversion**: Choose a custom currency from the second dropdown to convert your amount into that currency.
5. **View Country Information**: After conversion, the app displays the country information (flag, population, GDP) of the selected currency.
6. **AI Trading Advice**: After conversion, you’ll receive AI-generated trading advice on whether to "Buy", "Sell", or "Hold" based on the currency conversion.

## Example Use Case

1. User inputs 100 in the "Amount" field.
2. Select "USD" from the "From Currency" dropdown.
3. Click the "Compare" button to see the equivalent amounts in EUR, GBP, JPY, etc.
4. The user can also choose a custom currency (e.g., CAD) to convert the 100 USD to Canadian Dollars.
5. After conversion, the app displays country details such as the flag, population, and GDP for Canada.
6. AI-powered trading advice is displayed suggesting whether to buy, sell, or hold the USD/CAD pair.

## API Keys

To use the external APIs, you'll need the following API keys:

1. **Fixer.io API Key**: You can get an API key from [Fixer.io](https://fixer.io/).
2. **Hugging Face API Key**: You can sign up and get an API key from [Hugging Face](https://huggingface.co/).

Once you have your keys, replace the placeholders in the script with your own keys:

```js
const apiKey = 'YOUR_FIXER_API_KEY';  // For Fixer.io API
const hfApiKey = 'YOUR_HUGGINGFACE_API_KEY';  // For Hugging Face API
```

## Contributing

Feel free to fork this repository and contribute to it! Here are some ways you can help:

- Report bugs or suggest features.
- Improve the user interface and experience.
- Help with optimizing API requests and error handling.
- Add new features like a broader range of AI models.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

- **Fixer.io API**: Provides real-time exchange rates.
- **REST Countries API**: Supplies detailed country data.
- **Hugging Face**: Powers the AI-generated trading advice.
- **Font Awesome**: For currency and flag icons.
- **Flaticon**: For favicon image.

Thank you

-Rehan Raj

