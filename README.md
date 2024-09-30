This project contains the developed solution for the given challenge at https://github.com/gems-st-ib/powerplant-coding-challenge.

Made by Alvaro Gonzalez Mendez.

In order to execute the REST service you must:

1. Make sure you have installed:
    - Python
    - Poetry (https://python-poetry.org/)

2. Use the following command on the project's path:
    poetry install

3. Run the REST service using flask by executing the following command:
    poetry run python3 app.py 

In order to make a Request the user must POST to 

    localhost:8888/productionplan 

with the desired payload as the body of the request.