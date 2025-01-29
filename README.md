# Integrating-API-using-python
Download and unzip the folder.
Install all the dependencies using pip install fastapi uvicorn requests python-dotenv in the terminal.
Logon to fatsecret api integration and go to api credentials.get the client id and client secret code.
Enter these details in  .env file.
Run uvicorn main:app --reload in the terminal inorder to start fastapi app.
Chech your authentication by running http://127.0.0.1:8000/auth in the browser.
Run http://127.0.0.1:8000/search_food?food_name=apple in your browser to find the desired output.
