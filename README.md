# TravelBloom

**TravelBloom** is a travel recommendation platform designed to help users discover their next dream destination. Whether you're looking for a relaxing beach getaway, a spiritual journey to ancient temples, or exploring a new country, TravelBloom provides personalized suggestions to make your trip planning easier.

## Features

-   **Destination Search**: Search for terms like "beach", "temple", or "country" to get tailored recommendations.
-   **Dynamic Recommendations**: View curated lists of destinations with high-quality images and descriptions.
-   **Responsive Design**: A seamless experience across desktop and mobile devices.
-   **Informative Pages**: Dedicated "About Us" and "Contact Us" pages to learn more about our mission and get in touch.

## Grading Criteria Met

This project fulfills the requirements for the Coursera final project:
-   [x] **GitHub Repository**: Hosted publicly.
-   [x] **Site Structure**: Includes Home, About Us, and Contact Us pages.
-   [x] **Navigation Bar**: Consistent navigation across all pages.
-   [x] **Hero Section**: Engaging introduction on the homepage.
-   [x] **About Us**: Mission statement and team details.
-   [x] **Contact Us**: Functional contact form layout.
-   [x] **Search Logic**:
    -   "Beach" returns at least 2 beach recommendations.
    -   "Temple" returns at least 2 temple recommendations.
    -   "Country" returns country-based recommendations.

## Tech Stack

-   **HTML5**: Structure and semantic markup.
-   **CSS3**: Styling, Flexbox/Grid layouts, and responsive design.
-   **JavaScript (ES6)**: DOM manipulation, Fetch API for data retrieval.

## Setup & Usage

1.  Clone the repository:
    ```bash
    git clone https://github.com/Juthishsan/Travel-Application.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd Travel-Application
    ```
3.  Because this project uses the `fetch` API to load JSON data, you must run it on a local server (browsers block local file access for security).
    -   **VS Code**: Use the "Live Server" extension.
    -   **Python**:
        ```bash
        python -m http.server
        ```
    -   **Node.js**:
        ```bash
        npx http-server
        ```
4.  Open your browser to the local server address (e.g., `http://localhost:8000`).

## License

This project is for educational purposes as part of a Coursera certification.
