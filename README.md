# lab1
This is a simple Flask project using the Waitress server. The project includes a single endpoint that returns "Hello World 4" when accessed.

# Prerequisites

- [Python](https://www.python.org/downloads/) installed on your machine.
- [Pipenv](https://pipenv.pypa.io/en/latest/) for managing dependencies.
- [PyCharm](https://www.jetbrains.com/pycharm/) or any other code editor of your choice.

# Getting Started

1. Create new project using pipenv.
2. Clone the repository:
   ```bash
   git clone <repository_url>
3. Activate the virtual environment:
   pipenv shell
4. Install waitress:
   pipenv install waitress
5. Run the Flask app with the Waitress server:
   python main.py
6. Open your browser and go to http://localhost:5000/api/v1/hello-world-4 to see the "Hello World 4" response.

# Project Structure

main.py: The main Python script containing your Flask app.
Pipfile and Pipfile.lock: Pipenv files specifying project dependencies.

# Notes

This project uses the Waitress server to serve the Flask app. Waitress is a production-ready WSGI server that can be used as an alternative to the development server.
Ensure that the virtual environment is activated when running the Flask app.
