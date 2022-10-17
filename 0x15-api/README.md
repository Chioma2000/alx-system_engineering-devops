API
This project was further practice in working with API's. I collected data from the JSONPlaceholder REST API, and learned how to export it to either CSV or JSON format.

Tasks 📃
0. Gather data from an API

0-gather data from an API.py: Python script that returns information on the to-do list progress of a given employee ID.
Usage: python3 0-gather data from an API.py <employee ID>.
Output: Employee <employee name> is done with tasks(<# completed tasks>/<total # tasks>):

1. Export to CSV

1-export to CSV.py: Python script exports to-do list information of a given employee ID to CSV format.
Usage: python3 1-export to CSV.py <employee ID>
File name: <user id>.csv.
Format: "<user id>","<username>","<task completed status>","<task title>".

2. Export to JSONi

2-export to JSON.py: Python script that exports to-do list information of a given employee ID to JSON format.
Usage: python3 2-export to JSON.py <employee ID>
File name: <user id>.json
Format: { "<user id>": [ {"task": "<task title>", "completed": <task completed status>, "username": "<username>"}}, ... ]}

3. Dictionary of list of dictionaries

3-dictionary of list of dictionaries.py: Python script that exports to-do list information for all employees to JSON format.
Usage: python3 3-dictionary of list of dictionaries.py
File name: todo all employees.json
Format: { "<user id>": [ {"username": "<username>", "task": "<task title>", "completed": <task completed status>}, {"username": "<username>", "task": "<task title>", "completed": <task completed status>}, ... ], "<user id>": [ {"username": "<username>", "task": "<task title>", "completed": <task completed status>}, {"username": "<username>", "task": "<task title>", "completed": <task completed status>}, ... ]}
