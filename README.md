# Flask Birthdays

Flask Birthdays is a web application built using Flask that allows users to store and keep track of birthdays. Users can view existing birthdays and add new ones to the database.

## Installation

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Create a virtual environment: `python -m venv venv`.
4. Activate the virtual environment:
   - For Windows: `venv\Scripts\activate`
   - For Unix or Linux: `source venv/bin/activate`
5. Install the required dependencies: `pip install -r requirements.txt`.
6. Set the FLASK_APP environment variable: `set FLASK_APP=app.py` (Windows) or `export FLASK_APP=app.py` (Unix/Linux).
7. Run the application: `flask run`.

## Usage

- Access the application by visiting `http://localhost:5000` in your web browser.
- The homepage displays a table of existing birthdays.
- To add a new birthday, fill out the form on the homepage and submit it.
- The new birthday will be added to the database, and the page will be refreshed to display the updated table.

## Features

- View existing birthdays in a table format.
- Add new birthdays to the database.
- Optionally, you can customize the application by adding features like deleting or editing birthday entries.

## Technologies Used

- Python
- Flask
- SQLite

## Contributing

Contributions to Flask Birthdays are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
