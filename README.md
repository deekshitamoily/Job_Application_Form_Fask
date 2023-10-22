# Job_Application_Form_Fask
A job application form created with Flask is a web application that allows users to submit their personal and professional information for job opportunities. It typically includes fields for details like the applicant's name,contact information, employment history,available start date,occupation.

## Features

- Collects applicant information, including first name, last name, email, available start date, and current occupation.
- Stores applicant data in a SQLite database.
- Sends a confirmation email to the applicant with their submitted information.
- Provides user feedback with flash messages on successful submission.

### Prerequisites

Before you can run this application, make sure you have the following prerequisites installed on your system:

- Python (3.7 or higher)
- Pip (Python package manager)

  ### Installation

1. Clone the repository to your local machine:

   git clone https://github.com/your-username/job-application-form.git
   cd job-application-form
2.Install the required packages:

pip install -r requirements.txt

### Usage
1. Run the Flask application:

python app.py
2.Open your web browser and go to http://localhost:5000 to access the job application form.

3.Fill in the required fields, including first name, last name, email, available start date, and current occupation.

4.Click the "Submit" button.

5.After submission, you will receive a success message and a confirmation email with your submitted information.

### Configuration
Configuration
To configure email settings for sending confirmation emails, edit the app.config values for MAIL_SERVER, MAIL_PORT, MAIL_USE_SSL, MAIL_USERNAME, and MAIL_PASSWORD in app.py.

To configure the SQLite database file location, edit the SQLALCHEMY_DATABASE_URI value in app.py.

