# Personal Portfolio Website

## Overview
This project is a personal portfolio website designed to showcase the work and skills of a Computer Science student. The website includes sections for home, about, projects, and contact information, allowing visitors to learn more about the individual and their work.

## Features
- **Responsive Design**: The website is designed to be mobile-friendly and adjusts to different screen sizes.
- **Admin Dashboard**: An admin panel for managing projects and viewing contact messages.
- **Database Integration**: Utilizes a MySQL database to store project and contact information.
- **User  Authentication**: Admin login functionality to secure the admin dashboard.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Frameworks/Libraries**: None (pure PHP and MySQL)

## File Structure
```
MultipleFiles/
│
├── db.php                # Database connection class
├── admin.php             # Admin dashboard for managing projects and contacts
├── contacts.php          # Class for handling contact messages
├── projects.php          # Class for managing projects
├── user.php              # User authentication class
├── index.php             # Main website page
├── adminstyle.css        # CSS for admin dashboard
├── indexstyle.css        # CSS for main website
├── profile.jpg           # Profile image
├── github.png            # GitHub icon
├── liknee.png            # LinkedIn icon
├── insta.jpg             # Instagram icon
├── tele.png              # Telegram icon
└── README.md             # Project documentation
```

## Installation
1. Clone the repository to your local machine.
2. Create a MySQL database named `portfolios`.
3. Import the necessary SQL tables for `projects` and `contacts`.
4. Update the database connection details in `db.php` if necessary.
5. Open `index.php` in your web browser to view the portfolio.

## Usage
- **Viewing Projects**: Navigate to the "Projects" section to view all projects.
- **Contacting**: Use the contact form in the "Contact Me" section to send messages.
- **Admin Access**: Access the admin dashboard via `admin.php` to manage projects and view contact messages.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License
This project is open-source and available under the MIT License.

## Author
- **Name**: Michael
- **Email**: mike3456@gmail.com

## Acknowledgments
- Thanks to all the resources and tutorials that helped in the development of this portfolio website.
