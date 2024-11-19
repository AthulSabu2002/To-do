# To-Do App

Welcome to the To-Do Web App! This is a simple and beautiful web application to manage your daily tasks.

## Features

- Add new tasks
- Update tasks
- View all tasks
- Complete tasks
- Delete multiple tasks
- Responsive design

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/AthulSabu2002/To-do.git
    ```

2. Navigate to the project directories and install dependencies:

    ```bash
    cd to-do/frontend
    npm install
    cd ../server
    npm install
    ```

3. Create a `.env` file in the `server` directory for the server and add your environment variables:

    ```bash
    touch .env
    ```

    Example `.env` file:

    ```env
    PORT=5000
    MONGODB_URI=your_mongodb_uri
    ```

4. Create a `.env` file in the `frontend` directory for the frontend and add your environment variables:

    ```bash
    cd frontend
    touch .env
    ```

    Example `.env` file:

    ```env
    VITE_REACT_APP_BASE_URL=http://localhost:5000
    ```

## Usage

1. Start the server:

    ```bash
    cd server
    npm start
    ```

2. Start the frontend (react):

    ```bash
    cd frontend
    npm run dev
    ```

3. Open your browser and navigate to `http://localhost:5173`

## Technologies Used

- React
- CSS Modules / Styled Components
- Axios / Fetch API

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.


## Contact

If you have any questions or suggestions, feel free to reach out to me at [athulsabu75@gmal.com](mailto:athulsabu75@gmal.com).

Enjoy using the To-Do App!
