# Proyecto_API_Yeison

COVID-19 Data Retrieval and Visualization
This project fetches and displays COVID-19 case data from the Colombian Open Data API (datos.gov.co) using Socrata. It allows users to specify a department and the number of records to retrieve, then presents the data in a tabular format.

Project Structure
api/api.py → Handles API requests and data retrieval.
ui/ui.py → Manages user input and data display.
main.py → Entry point of the application.
How It Works
The user inputs the number of records (max 500) and the department name.
The system queries datos.gov.co for relevant COVID-19 cases.
The retrieved data is formatted and displayed in a structured table.
Usage Example
bash
Copiar
Editar
python main.py
Requirements
Python 3.8+
Pandas (pip install pandas)
Sodapy (pip install sodapy)
License
This project is open-source and distributed under the MIT License.

