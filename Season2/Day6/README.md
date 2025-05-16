# FILE: /flask-app/flask-app/README.md
# Flask Application

This project is a simple Flask application that demonstrates how to set up a web server using Flask. It includes a home route that welcomes users.

## Prerequisites

- Python 3.x
- pip (Python package installer)

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/flask-app.git
   cd flask-app
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

## Running the Application

To run the application, execute the following command:

```bash
python app.py
```

The application will be accessible at `http://0.0.0.0:5000`.

## GitHub Actions

This project includes a GitHub Actions workflow for continuous integration. The workflow is defined in `.github/workflows/python-app.yml` and will automatically run tests and checks on each push to the repository.

## License

This project is licensed under the MIT License.