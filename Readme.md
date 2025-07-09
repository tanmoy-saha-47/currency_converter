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

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js (LTS version recommended)
- npm (Node Package Manager) or Yarn

### Installation

1.  **Clone the repository:**

    ```bash
    git clone <repository_url>
    cd currency-converter-app
    ```

    (Replace `<repository_url>` with the actual URL of your GitHub repository.)

2.  **Install dependencies:**

    ```bash
    npm install
    # or if you use yarn
    yarn install
    ```

    This will install all the necessary React, Tailwind CSS, and other project dependencies.

3.  **Initialize Tailwind CSS configuration (if not already present):**
    If `tailwind.config.js` and `postcss.config.js` files are not in your project root, run:

    ```bash
    npx tailwindcss init -p
    ```

4.  **Configure `tailwind.config.js`:**
    Ensure your `tailwind.config.js` file is configured to scan your source files for Tailwind classes. It should look similar to this:

    ```javascript
    /** @type {import('tailwindcss').Config} */
    export default {
      content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
      theme: {
        extend: {},
      },
      plugins: [],
    };
    ```

5.  **Add Tailwind Directives to your CSS:**
    Make sure your main CSS file (e.g., `src/index.css` or `src/App.css`) includes the Tailwind directives at the top:
    ```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```
    And ensure this CSS file is imported into your `src/main.jsx` (or `src/App.jsx` if that's your entry point).

### Running the Application

To start the development server:

```bash
npm run dev
# or if you use yarn
yarn dev
```
