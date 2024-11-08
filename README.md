# Disability Support Web App

This is a Flask web application created to provide support and resources for disabled individuals dealing with mental health challenges, self-harm, and substance misuse. The site includes an informative homepage and contact information for those seeking assistance or wanting to volunteer.

- Project debrief is available in debrief.pdf

## Prerequisites

Before you start, ensure you have the following installed:
- [Python 3](https://www.python.org/downloads/)
- [Git](https://git-scm.com/)

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/AmirrezaMir/va-task-project.git
    cd va-task-project
    ```

2. **Set up a virtual environment**:
    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment**:

    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```

4. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Application

1. **Set the Flask app environment variable** (if needed):
    ```bash
    export FLASK_APP=app.py     # On macOS/Linux
    set FLASK_APP=app.py        # On Windows
    ```

2. **Run the Flask app**:
    ```bash
    flask run
    ```

3. **Access the app**:

   Open your browser and go to: [http://127.0.0.1:1234](http://127.0.0.1:1234)
