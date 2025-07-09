# Currency Converter Application

A simple and intuitive currency converter application built with React, leveraging custom hooks for currency data fetching and styled with Tailwind CSS. This application allows users to convert amounts between various currencies fetched from an external API.

## Features

- **Real-time Conversion:** Converts currency amounts instantly based on up-to-date exchange rates.
- **Dynamic Currency Options:** Fetches and displays a comprehensive list of available currencies using a custom hook.
- **Swap Functionality:** Easily swap the "From" and "To" currencies with a single click.
- **User-Friendly Interface:** Clean and responsive design built with Tailwind CSS, providing a seamless conversion experience.
- **Clear Input/Output:** Dedicated fields for entering the amount to convert and displaying the converted result.

## Technologies Used

- **React.js:** A JavaScript library for building user interfaces.
- **Tailwind CSS:** A utility-first CSS framework for rapid UI development and styling.
- **Custom React Hooks:** Used for abstracting and reusing currency information fetching logic (`useCurrencyInfo`).
- **JavaScript `fetch` API:** For making HTTP requests to external currency rate APIs.
- **`useState` Hook:** For managing component state, such as input amount, selected currencies, and converted amount.
- **`useEffect` Hook:** For performing side effects like fetching data when component dependencies changes.





