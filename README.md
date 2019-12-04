### Fulfillment Codes for Dialogflow
- This is by no means an extensive documentation. Some prior knowledge concepts in progamming and web services is assumed.

- The python code (fintech-index.py) is used as a fulfillment web services (using Flask framework) to demonstrate how we can collect information using Dialogflow and write extracted information to a Google Sheet document.

### Dialogflow

- Needs an intent with action='request_callback'
- Intent must collect parameters phone-number and person.
- For the parameters, please use system entities phon-entity-number and person

### Python modules

- Install using the bashcommand $pip install XXXX , where XXX refers to the modules listed in the python program (fintech-index.py).
- Sorry, I did not prepare the requirements text file.

### Google Sheet

- Refer to https://gspread.readthedocs.io/en/latest/ for the guideon how to setup your Google Sheet and get the service account keys.
- You need the service account key to update the python program (fintech-index.py)

### Deploy fintch-index.py as a Flask application (webhook)

- Refer to https://www.pragnakalp.com/dialogflow-fulfillment-webhook-tutorial/ for a simple example to run a flask application.
- Then, repeat but use the python program fintech-index.py
- Update the fulfillment URL in dialogflow with the URL that Flask returns you.
