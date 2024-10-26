# ConversionDataType

Clone the repository to you local machine using the command: 
git clone https://github.com/AishwaryaSimhaPraveen/ConversionDataType.git

Python 3.x: A programming language required for running the Django framework. You can download it from python.org.

Django: A high-level Python web framework that encourages rapid development and clean, pragmatic design. It can be installed via pip (included with Python):
pip install django

npm (Node Package Manager): A package manager for JavaScript, typically installed with Node.js. You can download it from nodejs.org.

Virtual Environment (venv): A tool to create isolated Python environments. It's included with Python 3.3 and later. Create a virtual environment with:
python -m venv venv

Pandas: A data manipulation and analysis library for Python. Install it via pip:
pip install pandas

django-cors-headers: A Django app for handling Cross-Origin Resource Sharing (CORS). Install it with pip:
pip install django-cors-headers

Axios: A promise-based HTTP client for the browser and Node.js. It can be installed via npm:
npm install axios

Backend-Setup
Follow these steps to set up the backend for your project:
Activate the Virtual Environment:
Navigate to your project directory and activate the virtual environment you created:

On macOS/Linux:
source venv/bin/activate
On Windows:
.\venv\Scripts\activate

Run Database Migrations:
After activating the virtual environment, run the following command to apply database migrations:
python manage.py migrate

Run the Django Development Server:
Finally, start the Django development server with the following command:
python manage.py runserver
By default, the server will be accessible at http://127.0.0.1:8000/

Frontend-Setup
Follow these steps to set up the frontend for your project:
Navigate to the Frontend Directory:
Change to the directory where your frontend code is located:
cd data-type-inference-app
Install npm Packages:
If you haven't already initialized npm in this directory, run the following command to create a package.json file:
npm init -y

Then, install any missing packages listed in your package.json file or any other dependencies you need:
npm install

Start the Development Server:
Once the packages are installed, start the development server with:
npm start
This will start the development server, and it should be accessible at http://localhost:3000 (or another port if configured differently).

Upload a CSV or Excel File:
After the development server is running, you can upload a CSV or Excel file to see the detected data types.
