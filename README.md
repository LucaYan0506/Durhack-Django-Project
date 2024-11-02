# Durhack Django Starter

## Project Description
This repository provides a Django starter template prepared for the Durhack hackathon. It includes a basic Django setup, ready to support rapid development for our project ideas.

## Live Demo
A live version of the project will be available at:
[Live Demo URL](https://lucayan5.pythonanywhere.com/)

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

## Development Workflow
To maintain code quality and avoid breaking changes, please follow these guidelines:
1. **Create a New Branch** for each feature or bug fix:
```bash
git checkout -b feature/your-feature-name
```
2. **Do Not Push to the Main Branch Directly**. Instead, create a pull request after committing your changes to the new branch.
3. **Push Changes** to the Branch:
```bash
git push origin feature/your-feature-name
```
4. Submit a **Pull Request** for review before merging.

## License
This project is licensed under the MIT License.
