# Dev Hub Exercise

This is a sample project using Bootstrap and JavaScript to create an interactive interface with dynamic themes and modals.

## Project Structure

-   **index.html**: Main HTML file.
-   **package.json**: Project settings and dependencies.
-   **public/**: Contains public resources, such as images and icons.
    -   `vite.svg`: Vite icon.
-   **src/**: Contains source code files.
    -   `main.js`: Main JavaScript file.
    -   `scss/`: Contains SCSS style files.
        -   `_bootstrap.scss`: Styles related to Bootstrap.
        -   `_variables.scss`: Custom style variables.
        -   `styles.scss`: Main project styles.

## Features

1. **New Post Modal**:

    - Button to open a modal where the user can create a new post.
    - The input field in the modal automatically receives focus upon opening.

2. **Theme Toggle**:
    - Button to switch between light and dark themes.
    - Dynamic icons that change according to the selected theme.

## Technologies Used

-   **Bootstrap**: For ready-to-use components and styles.
-   **JavaScript**: For DOM manipulation and interactivity.
-   **SCSS**: For custom styles and CSS organization.

## How to Run the Project

1. Make sure you have Node.js installed.
2. Install the project dependencies:
    ```bash
    npm install
    ```
3. Start the development server:
    ```bash
    npm run dev
    ```
4. Open your browser and access the address provided by the terminal.

## Style Structure

The styles are organized into SCSS files to facilitate maintenance and reuse. The `styles.scss` file imports other SCSS files, such as `_bootstrap.scss` and `_variables.scss`.

## Contribution

Feel free to contribute with improvements or new features. Fork the repository, create a branch for your changes, and submit a pull request.

## License

This project is for educational purposes only and does not have a specific license.
