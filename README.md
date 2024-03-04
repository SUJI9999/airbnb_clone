# Airbnb Clone with React, Vite, Express, and MongoDB

This project is a simplified clone of Airbnb built with modern technologies:

## Frontend 
- React
- Vite
- Tailwind CSS

## Backend 
- Express
- Node.js
- MongoDB

## Additional Features 
- User authentication
- Image upload to S3
- Booking management

## Getting Started

1. Clone the repository 
    ```
    git clone https://github.com/your-username/airbnb-clone.git
    ```

2. Install dependencies
    ```
    cd airbnb-clone
    npm install
    ```

3. Set up environment variables
    Create a `.env` file in the root directory and add the following variables:
    ```
    MONGO_URL=your_mongodb_connection_string
    S3_ACCESS_KEY=your_aws_s3_access_key
    S3_SECRET_ACCESS_KEY=your_aws_s3_secret_access_key
    ```

4. Start the development server
    ```
    npm run dev
    ```

This will start both the frontend and backend servers. The frontend will be accessible at `http://localhost:5173` and the backend at `http://localhost:4000`.

## Features

- Users can create accounts and log in to manage their bookings and accommodations.
- Users can browse a list of available accommodations with photos, descriptions, and prices.
- Each accommodation has a dedicated page with detailed information, a photo gallery, and a booking widget.
- Users can book accommodations for specific dates and manage their bookings in their account.
- Users can upload photos of their accommodations using either a link or direct upload. Images are stored in an S3 bucket.

## Screenshots

[Add screenshots of the application here]

## Contributing

Contributions are welcome! Please see the `CONTRIBUTING.md` file for guidelines.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
