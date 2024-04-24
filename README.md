

# Crime Management and Surveillance System

This is a Django web application designed to assist law enforcement agencies in managing criminals' records, conducting CCTV surveillance, and sending alerts when a registered criminal is detected.

## Installation

1. Clone the repository to your local machine:
   ```
   git clone <https://github.com/hema-achuta/Crime-Person-Location>
   ```

2. Navigate to the project directory:
   ```
   cd crime_management_surveillance
   ```

3. Create a virtual environment and activate it:
   ```
   python3 -m venv venv
   source venv/bin/activate (For Unix/macOS)
   venv\Scripts\activate (For Windows)
   ```

4. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

5. Set up the database:
   ```
   python manage.py migrate
   ```

6. Create a superuser account to access the admin panel:
   ```
   python manage.py createsuperuser
   ```

## Usage

1. Start the development server:
   ```
   python manage.py runserver
   ```

2. Access the application in your web browser at `http://localhost:8000/`

3. Police officers can log in using their credentials and register criminals along with their photos in the system.

4. Once registered, the system will use CCTV surveillance to detect registered criminals. When a match is found, an email and message alert will be sent to notify the concerned authorities, including the person's location.

## Features

- **Authentication**: Secure login system for police officers.
- **Criminal Registration**: Register criminals along with their photos.
- **CCTV Surveillance**: Automated surveillance using CCTV cameras.
- **Alert System**: Email and message alerts sent when a registered criminal is detected.
- **Admin Panel**: Administrators can manage users, criminals, and system settings through the Django admin interface.

## Technologies Used

- Python
- Django
- HTML
- CSS
- Bootstrap (optional for styling)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your enhancements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README file further based on your project's specific needs and additional features. Let me know if you need further assistance!
