# Data-analytics-Dashboard

The **Data Analytics Dashboard** is a web application built using the Django framework that provides a user-friendly interface for performing data analysis tasks. This README will guide you through the installation process and how to run the application locally.

## Installation

To get started with the Django Data Analysis Dashboard, follow these steps:

### 1. Prerequisites

Before you begin, ensure that you have the following installed on your system:

- Python (>= 3.6)
- pip (Python package manager)

### 2. Clone the Repository

Clone this repository to your local machine using Git:

```bash
git clone https://github.com/avd1729/Data-analytics-Dashboard.git
```

### 3. Create a Virtual Environment (Optional but Recommended)

Navigate to the project directory and create a virtual environment. This step is optional but highly recommended to isolate dependencies for this project:

```bash
cd dashboard
python -m venv venv
```

Activate the virtual environment:

- On Windows:

```bash
venv\Scripts\activate
```

- On macOS and Linux:

```bash
source venv/bin/activate
```

### 4. Install Dependencies

Install the required Python packages listed in the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 5. Database Setup

Run the following command to create the necessary database tables:

```bash
python manage.py migrate
```

### 6. Running the Application

Start the development server by running the following command:

```bash
python manage.py runserver
```

The application should now be running locally at `http://127.0.0.1:8000/`.

### 7.Sample

<img width="1280" alt="image" src="https://github.com/avd1729/Data-analytics-Dashboard/assets/94891044/c3007d97-6f77-47f0-a106-436c6e2e2c74">


## Usage

Open your web browser and navigate to `http://127.0.0.1:8000/` to access the Django Data Analysis Dashboard. The dashboard provides an intuitive interface to perform various data analysis tasks.
