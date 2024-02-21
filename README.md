# slack-url-shortener

A simple URL shortening service built using Node.js, Express, and MongoDB.

## Features

- Shorten long URLs to easily share them.
- Track the number of clicks on shortened URLs.
- Simple and intuitive user interface.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/url-shortener.git
    ```

2. Navigate to the project directory:

    ```bash
    cd url-shortener
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Set up environment variables:
   
   Create a `.env` file in the root directory and add the following variables:

   ```plaintext
   PORT=5000
   MONGODB_URL=mongodb://localhost/urlShortener
   ```

   Replace `MONGODB_URL` with your MongoDB connection string.

5. Start the server:

    ```bash
    npm start
    ```

6. Open your web browser and navigate to `http://localhost:5000` to access the application.

## Usage

- Enter a long URL into the input field on the homepage and click the "Shorten" button to generate a shortened URL.
- Copy the generated shortened URL and share it with others.
- Click on the shortened URL to redirect to the original long URL.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Bootstrap (for styling)

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to contribute to this project.

## License

This project is licensed under the [MIT License](LICENSE).

