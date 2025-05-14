# Flask Portfolio

This project is a simple Flask web application that serves a portfolio webpage. The portfolio showcases personal information, education, skills, and projects.

## Project Structure

```
flask-portfolio
├── app
│   ├── static
│   │   └── style.css
│   ├── templates
│   │   └── index.html
│   └── app.py
├── requirements.txt
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd flask-portfolio
   ```

2. **Create a virtual environment:**
   ```
   python -m venv venv
   ```

3. **Activate the virtual environment:**
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. **Install the required packages:**
   ```
   pip install -r requirements.txt
   ```

## Running the Application

To run the Flask application, execute the following command in the terminal:

```
python app/app.py
```

The application will be accessible at `http://127.0.0.1:5000/`.

## Usage

Once the application is running, you can navigate to the homepage to view the portfolio. The page includes sections for personal information, education, skills, and projects.

## License

This project is licensed under the MIT License.