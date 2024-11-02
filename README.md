# Durhack Django Starter

## Project Description
This repository provides a Django starter template prepared for the Durhack hackathon. It includes a basic Django setup, ready to support rapid development for our project ideas.

## Getting Started

### Prerequisites
- Python 3.x
- Git
- Virtual environment tools (optional but recommended)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/LucaYan0506/Durhack-Django-Project.git
   cd .\Durhack-Django-Project\
   ```

2. **Create and Activate Virtual Environment**
   ```bash
   pip install pipenv
   pipenv shell
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Database**
   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**
   ```bash
   python manage.py runserver
   ```

### Project Structure
- **`/`** - Root directory with the basic setup files.
- **`requirements.txt`** - Python packages required for the project.
- **`manage.py`** - Django’s command-line utility.

## Usage
1. Run `python manage.py runserver` to start the server.
2. Access the server at `http://127.0.0.1:8000`.

## License
This project is licensed under the MIT License.
