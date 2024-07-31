# E-Bookopolis

## Introduction
E-Bookopolis is a web-based platform that allows users to engage in discussions about various types of books, read books for free, and upload their own poems or stories. The platform is designed to help writers gain recognition and attract publisher attention. This README outlines the system's design, implementation, and performance analysis.

## Features
- **Discussion Forum:** Users can discuss different types of books.
- **Free Reading:** Users can read books available on the platform for free.
- **Content Upload:** Users can upload their own poems or stories to gain recognition and publisher attention.
- **User Interaction:** Users can like, comment, and share content.
- **User Feedback:** Users can view ratings and provide feedback.
- **Admin Dashboard:** Admins can manage users, publishers, and content on the platform.

## Installation Guide
Follow these steps to set up the project locally:

### Prerequisites
- **Web Server:** Install a web server like Apache or Nginx.
- **PHP:** Ensure PHP is installed on your server.
- **Database:** A MySQL database is recommended.

### Steps
1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-username/E-Bookopolis.git
    cd E-Bookopolis
    ```

2. **Database Setup:**
    - Create a new database in MySQL.
    - Import the provided SQL file (if any) to set up the necessary tables.

3. **Configure Database Connection:**
    - Open `db.php` and update the database connection details (hostname, username, password, database name).

4. **Run the Website:**
    - Place the project files in your web server's root directory (e.g., `htdocs` for XAMPP or `www` for WAMP).
    - Start the web server and navigate to `http://localhost/E-Bookopolis/index.html` to access the website.

5. **Login/Registration:**
    - Users need to register via the `registration.html` page before they can log in and access other features.

## Admin View
Admins have special access to manage the website's content and user base. The following features are available to admins:

- **User Management:** Admins can view and manage user profiles, including deleting or suspending accounts if necessary.
- **Publisher Management:** Admins can add, view, and manage publishers on the platform.
- **Content Management:** Admins can monitor and manage all uploaded content, including books, poems, and stories. They can remove any content that violates the platform's guidelines.

## User View
Users have access to various features that enhance their experience on the platform:

- **Browse and Search:** Users can search for books and other content based on their preferences.
- **Content Interaction:** Users can like, comment, and share posts. They can also rate and review books or stories.
- **Upload Content:** Users can upload their own poems, stories, or other literary works to share with the community.
- **Profile Management:** Users can view and update their profile information, including uploading a profile picture and managing their uploaded content.

## Performance Analysis
For optimal performance, ensure that:

- The web server is configured correctly.
- Database queries are optimized.
- The website is tested on different browsers and devices.
