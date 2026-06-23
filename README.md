> [!WARNING]
  **This repo is deprecated and no longer maintained. Security updates are not supported. We recommend avoiding its use.**

# Contentstack getting started React App

## Description

This is a React starter app that integrates with Contentstack's Content Delivery API. It provides a foundation for building dynamic web applications that fetch and display content from Contentstack's headless CMS.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/contentstack/contentstack-getting-started-react-app.git
   ```

2. Navigate to the project directory:

   ```
   cd contentstack-getting-started-react-app
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Rename `.env.sample` as `.env` file in the root directory and add your Contentstack API keys:

   ```
   VITE_CONTENTSTACK_API_KEY=YOUR_STACK_API_KEY
   VITE_CONTENTSTACK_DELIVERY_TOKEN=YOUR_DELIVERY_TOKEN
   VITE_CONTENTSTACK_ENVIRONMENT=YOUR_ENVIRONMENT
   VITE_CONTENTSTACK_REGION=YOUR_STACK_REGION
   ```

5. Run the development server:
   ```
   npm run dev
   ```

## Configuration

To configure the app with your Contentstack account:

- Replace `YOUR_STACK_API_KEY`, `YOUR_DELIVERY_TOKEN`, `YOUR_ENVIRONMENT` and `YOUR_STACK_REGION` in the `.env` file with your Contentstack API key, delivery token, environment name and region respectively.

**Supported Regions:**

- **AWS North America:** `US`
- **AWS Europe:** `EU`
- **Azure North America:** `AZURE_NA`
- **Azure Europe:** `AZURE_EU`
- **GCP North America:** `GCP_NA`

## Usage

1. Once the app is running, navigate to `http://localhost:3000` in your web browser.
2. Explore the app to see how it fetches and displays content from Contentstack.
3. Customize and extend the app as needed for your project requirements.

## Features

- Integration with Contentstack's Content Delivery API.
- Dynamic rendering of content fetched from Contentstack.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or feedback, feel free to [open an issue](https://github.com/contentstack/contentstack-getting-started-react-app/issues).
