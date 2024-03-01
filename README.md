Text To Data Retriever - Gemini AI App
=====================================

This repository contains the code for a text-to-data retrieval app that uses the Gemini AI model to retrieve data from a database based on a natural language query. The app allows users to input a natural language description of the data they are looking for, and the model generates the corresponding SQL query to retrieve that data from the database.

Getting Started
---------------

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

-   Python 3.9
-   pip (Python package manager)
-   virtualenv (Python virtual environment manager)
-   A SQL database (e.g. PostgreSQL, MySQL)

### Installing

A step by step series of examples that tell you how to get a development environment running

1. Clone the repository to your local machine

```
git clone https://github.com/christinestraub/Text-To-Data-GeminiAI-App.git
```

2. Create a virtual environment and activate it

```
virtualenv venv
source venv/bin/activate
```

3. Install the required packages

```
pip install -r requirements.txt
```

4. Set up the database connection

-   Create a new database and user for the app
-   Update the `config.py` file with the database connection details

5. Run the app

```
python app.py
```

Using the App
-------------

The app will prompt you to enter a natural language description of the data you are looking for. For example, you might enter "Show me the names and salaries of all employees in the sales department." The model will then generate the corresponding SQL query and retrieve the data from the database.

Built With
----------

-   [Python](https://www.python.org/) - Programming language
-   [Streamlit](https://streamlit.com/) - Web framework
-   [Gemini AI Model](https://huggingface.co/babelscape/gemini) - AI model for generating SQL queries
-   [MySQL](https://www.mysql.org/) - Database toolkit and Object-Relational Mapping (ORM) system for Python


License
-------

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
