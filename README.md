# Wild-oasis

**Wild-oasis** is a modern web-based application designed for dynamic and efficient user interaction. This project utilizes cutting-edge web technologies to provide an optimal user experience.

## Live Demo

Check out the live demo: [Wild-oasis](https://wild-oasis-three.vercel.app/)

## Technologies Used

- **Frontend**
  - **Next.js** (App Router)
  - **Tailwind CSS** for styling
- **Database**
  - **Supabase** (shared with the admin app)
- **Authentication**
  - **NextAuth.js** with Google sign-in
- **Utilities**
  - **Date-fns** for date handling

## Features

- View all available cabins with detailed descriptions and images.
- Book a cabin for specific dates and select the number of guests.
- Sign in with Google to manage your bookings securely.
- Manage your reservations: view, edit, or cancel bookings.
- Update your personal profile information.
- Fully responsive and mobile-friendly for an optimal experience.


## Project Structure

```plaintext
Wild-Oasis-main/
├── app/                # Main application pages and layouts
├── public/             # Static assets (images, fonts, etc.)
├── middleware.js       # Middleware for requests
├── next.config.mjs     # Next.js configuration
├── tailwind.config.mjs # Tailwind CSS configuration
├── package.json        # Node.js dependencies
└── .gitignore          # Ignored files for Git
```

## How to Run

1. Clone the repository or download the project files:

    ```bash
    git clone <repository-url>
    cd Wild-Oasis-main
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm run dev
    ```

4. To build the application for production:

    ```bash
    npm run build
    npm start
    ```

## Screenshots

## Screenshots

### Home Page
![Dashboard](https://github.com/Redline1e/Wild-Oasis/blob/main/public/screenshots/dashboard.png)

### Cabin Page
![Cabin](https://github.com/Redline1e/Wild-Oasis/blob/main/public/screenshots/cabin.png)

### User Edit Page
![Transactions](https://github.com/Redline1e/Wild-Oasis/blob/main/public/screenshots/user-edit.png)
