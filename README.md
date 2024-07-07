# Trading Exchange

Welcome to the Trading Exchange project! This application is built using Next.js and leverages various libraries and tools to create a performant and feature-rich trading platform.

## Features

- **Real-time Trading**: Experience seamless trading with real-time data updates.
- **User Authentication**: Secure login and registration.
- **State Management**: Efficient state management using Redux.
- **Caching**: Improved performance with Redis caching.
- **Responsive Design**: Beautiful and responsive UI using Lucidev, ShadcnUI, and DaisyUI.

## Tech Stack

- **Next.js**: React framework for server-side rendering and static site generation.
- **Redux**: State management library for predictable state updates.
- **Redis**: In-memory data structure store for caching and fast data retrieval.
- **Lucidev**: Frontend library for icons and components.
- **ShadcnUI**: Component library for sleek UI design.
- **DaisyUI**: Tailwind CSS component library for rapid UI development.

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

- Node.js
- npm or yarn
- Redis

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/trading-exchange.git
    cd trading-exchange
    ```

2. **Install dependencies:**

    ```bash
    npm install
    # or
    yarn install
    ```

3. **Set up Redis:**

    Follow the [Redis installation guide](https://redis.io/download) to install Redis on your system.

4. **Create an `.env` file:**

    ```env
    REDIS_URL=redis://localhost:6379
    ```

### Running the Application

1. **Start the development server:**

    ```bash
    npm run dev
    # or
    yarn dev
    ```

2. **Open your browser:**

    Navigate to `http://localhost:3000` to see the application in action.

### Building for Production

1. **Build the project:**

    ```bash
    npm run build
    # or
    yarn build
    ```

2. **Start the production server:**

    ```bash
    npm start
    # or
    yarn start
    ```

## Project Structure

- **/components**: React components.
- **/pages**: Next.js pages.
- **/redux**: Redux store and slices.
- **/styles**: Styling files.
- **/utils**: Utility functions.

## Contributing

We welcome contributions! Please fork the repository and submit pull requests.

1. **Fork the repository**
2. **Create a new branch**

    ```bash
    git checkout -b feature/your-feature-name
    ```

3. **Make your changes**
4. **Commit your changes**

    ```bash
    git commit -m 'Add some feature'
    ```

5. **Push to the branch**

    ```bash
    git push origin feature/your-feature-name
    ```

6. **Open a pull request**

## License

This project is licensed under the MIT License.

## Contact

For any questions or inquiries, please contact Rahul Anand at rahul@example.com.

---

Happy Trading!
