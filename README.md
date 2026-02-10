# Employee Events Dashboard
# Motivation

Employee productivity and engagement are key factors in organizational performance. Understanding how employee events relate to productivity can help organizations identify patterns, risks, and opportunities for improvement.

The motivation of this project is to build a simple yet extensible Python dashboard that connects to an employee events database, computes productivity-related metrics, and presents them through tables and visualizations. This dashboard supports exploratory analysis and demonstrates object-oriented design applied to data-driven applications.

# Dataset

This project uses a SQLite database (employee_events.db) that contains employee-related event data. The database stores information about employee activities and event counts, which are used to compute productivity metrics and generate visual summaries.

The dataset is accessed through a custom Python package installed in the project environment.

# Software Dependencies

The project was developed using Python and the following main libraries:

Python 3.x

pandas

numpy

matplotlib

scikit-learn

uvicorn

fasthtml

The dashboard is served as a local web application.

File Descriptions

report/dashboard.py: Main dashboard application that defines routes, components, and visualizations.

python-package/employee_events/: Python package used to access the employee events database and compute metrics.

employee_events.db: SQLite database containing employee event data.

README.md: Project documentation and overview.

How to Interact with This Project

Clone the repository

Create and activate a virtual environment

Install the required Python dependencies

Run the dashboard application:

python -m report.dashboard


Open a browser and navigate to:

http://localhost:5001/employee/1



# Results Summary

This project demonstrates how a lightweight Python dashboard can be built using object-oriented design to visualize employee-related data.

Key outcomes include:
- Successful integration of a custom Python package with a SQLite database
- Clear separation of concerns between data access, business logic, and presentation
- Functional dashboard displaying metrics, tables, and charts
- A modular structure suitable for future extensions

Overall, the project shows how data engineering, OOP, and visualization can be combined into a simple but effective dashboard application.

# Licensing
This project is provided for educational purposes only.
The dataset is used locally for demonstration and learning.

# Authors
Aina Lluís Huelmo

# Acknowledgments
- Udacity Data Scientist Nanodegree program
- Course instructors and materials for guidance on object-oriented programming and dashboard development
