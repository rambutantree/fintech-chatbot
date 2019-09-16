# fintech-chatbot
This is by no means an extensive documentation.

The python code is used as a fulfillment web services (using Flask framework) to demonstrate how we 
can collect information using Dialogflow and write to Google Sheet document.


Dialogflow
- Needs a intent with action='request_callback' and sending a request with parameters phone-number and person. 
- Use the default system entities

Python modules
- Install using the pip install XXXX , where XXX refers to the modules listed in the python file. 
- Sorry, i did not prepare the requirements text file

Google Sheet
- Refer to https://gspread.readthedocs.io/en/latest/ for documentation on to setup the Google Sheet and get the service account keys.

Flask application (webhook)
- Refer to https://www.pragnakalp.com/dialogflow-fulfillment-webhook-tutorial/ for a simple example to run a flask application.
- Then, repeat but use the python code found in this file.
             
