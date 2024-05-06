# BookStore Django Project

## Overview
The BookStore Django project is a web application built using Django and Bootstrap. It provides CRUD (Create, Read, Update, Delete) operations for managing a bookstore.

## Installation
To install and run the project locally, follow these steps:
1. Clone the repository: `git clone https://github.com/mohamedtorkey20/BookStore-Django.git`
2. Navigate into the project directory: `cd BookStore-Django`
3. Install dependencies: `pip install -r requirements.txt`
4. Run migrations: `python manage.py migrate`
5. Start the development server: `python manage.py runserver`

## Usage
### CRUD Operations
- **Create**: To add a new book, navigate to the "Add Book" page and fill out the form.
- **Read**: View the list of books on the homepage. Click on a book to view its details.
- **Update**: Edit a book's details by clicking the "Edit" button on the book's detail page.
- **Delete**: Remove a book from the bookstore by clicking the "Delete" button on the book's detail page.

## Code Structure
The project's codebase is organized as follows:
- `bookstore/`: Contains the main Django app.
- `templates/`: HTML templates for rendering pages.
- `static/`: Contains static files such as CSS, JavaScript, and images.

## Dependencies
- Django
- Bootstrap
- (Include any other dependencies)

## Contributing
If you'd like to contribute to the project, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Commit your changes: `git commit -am 'Add new feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request.

## Troubleshooting
If you encounter any issues while running the project, please check the following:
- Ensure all dependencies are installed correctly.
- Check database migrations are applied: `python manage.py migrate`
- Check for any error messages in the terminal or browser console.

## License
This project is licensed under the [MIT License](/LICENSE).
