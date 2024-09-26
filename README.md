# Real Estate Multi-Search Tool

This project is a **Real Estate Search Tool** developed to perform multi-search operations using data from **Bazarki**. It features a robust frontend and backend architecture to provide a fast, efficient, and user-friendly experience for users searching real estate listings.

## Project Overview

- **Frontend**: Built with **React** and **Redux** for state management, styled with **CSS** and **HTML**. Interactive data visualization is powered by **Chart.js**.
- **Backend**: Developed using **Symfony** to handle server-side operations and API integrations.
- **Database**: Data is stored and managed using **MySQL**.

## Features

- Multi-property search functionality
- Advanced filtering options for real estate listings
- Interactive data visualization using Chart.js
- Optimized and responsive UI
- Fast data fetching with efficient state management via Redux

## Tech Stack

### Frontend
- **React** - A JavaScript library for building user interfaces.
- **Redux** - State management for React apps.
- **CSS** - Styling the user interface.
- **HTML** - Structuring the web pages.
- **JavaScript** - Dynamic behavior and interactivity.
- **Chart.js** - Data visualization library for interactive charts.

### Backend
- **Symfony** - PHP framework for web applications and APIs.

### Database
- **MySQL** - Relational database for storing real estate data.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/real-estate-search-tool.git

2. Install dependencies for the frontend:
   ```bash
   cd frontend
   npm install

3. Install dependencies for the backend:
   ```bash
   cd backend
   composer install

4. Set up the MySQL database:

- Create a new database in MySQL.
- Update the .env file in the backend with your database credentials.
- Run migrations:
   ```bash
   php bin/console doctrine:migrations:migrate

5. Run the development servers:
- frontend:
   ```bash
   npm start

- backend:
   ```bash
   symfony server:start



## Usage
1. Search for real estate listings using advanced filtering options.

2. View property listings and relevant details.

3. Explore data visualizations with Chart.js for more insights.

## Contributions
Contributions are welcome! Please open an issue or submit a pull request if you'd like to improve the project.

## License
This project is licensed under the MIT License.