# Journalku

Journalku is a web-based application designed for managing daily activities, attendance (check-in), and user journals. Built with **Laravel** and **Vite**, it provides a comprehensive dashboard for users and administrators to track productivity and team management.

## 🚀 Features

-   **Authentication System**: Secure login and logout functionality.
-   **Dashboard**: Centralized hub for monitoring activities and updates.
-   **Daily Check-in**: Feature for users to log their attendance or start their day.
-   **Activity Logging**:
    -   manage daily activities.
    -   Add additional activities.
-   **User Management**:
    -   Manage User Profiles.
    -   Role-based access control (RBAC).
    -   Circle/Group management.
-   **People & Reports**:
    -   Directory of people/users.
    -   Generate and view reports.
-   **Settings**: Application-wide and user-specific configurations.

## 🛠️ Tech Stack

-   **Backend**: [Laravel 10+](https://laravel.com)
-   **Frontend**: Blade Templates, [Vite](https://vitejs.dev), [Bootstrap](https://getbootstrap.com) (inferred)
-   **Database**: MySQL
-   **Language**: PHP, JavaScript

## 📦 Installation Management

Follow these steps to set up the project locally:

1.  **Clone the repository**
    ```bash
    git clone https://github.com/Ejre/Journalku.git
    cd kuanta-journalku
    ```

2.  **Install PHP Dependencies**
    ```bash
    composer install
    ```

3.  **Install Frontend Dependencies**
    ```bash
    npm install
    ```

4.  **Environment Setup**
    Copy the example environment file and configure your database settings:
    ```bash
    cp .env.example .env
    ```
    Edit `.env` and set your database credentials (`DB_DATABASE`, `DB_USERNAME`, `DB_PASSWORD`).

5.  **Generate Application Key**
    ```bash
    php artisan key:generate
    ```

6.  **Run Migrations**
    Set up the database tables:
    ```bash
    php artisan migrate
    ```
    *(Optional: Run seeders if available)*
    ```bash
    php artisan db:seed
    ```

## 🖥️ Usage

To run the application locally, you need to run both the Laravel server and the Vite development server:

1.  **Start Laravel Backend**
    ```bash
    php artisan serve
    ```

2.  **Start Vite Frontend** (in a new terminal)
    ```bash
    npm run dev
    ```

Access the application at `http://127.0.0.1:8000`.

## 🤝 Contribution

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
