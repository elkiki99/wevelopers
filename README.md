# Laravel Flux UI Starter Kit

**Laravel Flux UI Starter Kit** is a powerful foundation for building web applications. Designed for developers with a Flux UI subscription, it offers ready-to-use features such as user and admin dashboards, essential views, and seamless integration with Laravel Breeze. The kit is enhanced with Livewire for dynamic, real-time content, and provides both user and admin middleware for streamlined management.




## Key Features

- **Responsive Design**: Flux UI components ensure a seamless experience across desktops, tablets, and mobile devices with Tailwind CSS.
- **Livewire Integration:**: Real-time data updates and interactive UI components without needing page reloads.
- **Pre-built User & Admin Dashboards**: Ready-to-use dashboards with essential components.
- **Authentication & Authorization**: Built-in user authentication and role-based access control for secure applications.
- **Laravel Breeze Integration**: Comes bundled with Laravel Breeze for fast, simple authentication setup.
- **Admin & User Middlewares**: Pre-configured middleware for user and admin-specific content access and management.

## Getting Started

To use **Laravel Flux UI Starter Kit**, follow these steps:

1. **Fork the repository.**

2. **Clone the repository:**

    ```bash
    git clone https://github.com/elkiki99/laraflix
    cd flux-starter-kit
    ```

3. **Install the dependencies:**

    ```bash
    composer install
    ```
        
4. **Authenticate your Flux UI account:**
      
    ```bash
    Username: your-flux-email
    Password: your-flux-licence-key
    ```
    
5. **Finish installing dependencies and serve**

    ```bash
    npm install && npm run dev
    php artisan serve
    ```

6. **Set up your env file:**
   
    ```bash
     cp .env.example .env
     ```

7. **Generate an application key:**
     ```bash
     php artisan key:generate
     ```

8. **Create database/database.sqlite (if applicable)**
    
9. **Run your migrations and seeder:**
   
   - This will create an Admin account & a User account
   - Emails: admin@laravel.com & user@laravel.com, Password: 12345678

    ```bash
    php artisan migrate && php artisan db:seed
    ```

## Contributions

Contributions are welcome! If you'd like to contribute to **Laravel Flux UI Starter Kit**, please follow these steps:

## Contact

For any inquiries, please reach out at brossani23@gmail.com.
