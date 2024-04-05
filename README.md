# Event Management App

## Introduction

Hey there! Welcome to the Event Management App, your go-to solution for browsing upcoming events and posting your own. This app is built using Laravel, providing a secure and user-friendly experience for event management.

## Features

- Browse upcoming events
- Post new events (authentication required)
- Secure authentication system
- Tested with Postman for API endpoints

## Installation

To run this Event Management App locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone git@github.com:zulhusni2003/Event-Management-App.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Event-Management-App
    ```

3. Install Composer dependencies:

    ```bash
    composer install
    ```

4. Copy the example environment file and make the required configuration changes:

    ```bash
    cp .env.example .env
    ```

5. Generate a new application key:

    ```bash
    php artisan key:generate
    ```

6. Set up your database configuration in the `.env` file.

7. Run database migrations:

    ```bash
    php artisan migrate
    ```

8. Optionally, seed the database with sample data:

    ```bash
    php artisan db:seed
    ```

## Usage

Once the local server is running, you can start browsing upcoming events and post your own. Remember to sign in to access posting functionality.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request.

