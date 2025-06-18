![image](https://github.com/user-attachments/assets/a333a456-4607-4288-ab59-a551b605bd7b)

# Task:
1. Correct all of the deficiencies in index.html <br/>
2. "Sectors" selectbox:<br/>
2.1. Add all the entries from the "Sectors" selectbox to database<br/>
2.2. Compose the "Sectors" selectbox using data from database<br/>
3. Perform the following activities after the "Save" button has been pressed: <br/>
3.1. Validate all input data (all fields are mandatory)<br/>
3.2. Store all input data to database (Name, Sectors, Agree to terms)<br/>
3.3. Refill the form using stored data <br/>
3.4. Allow the user to edit his/her own data during the session <br/>

According to eSim team technologies, next technologies were chosen
.NET 6.020, React (VITE), MS SQL

## Repository Helmes-Task-Backend
### Uses MS SQL as a database. 
Connection to database: "DefaultConnection": "Server=tcp:helmestask-webapp-server.database.windows.net,1433;Initial Catalog=helmestask-webapp-database;Persist Security Info=False;User ID=helmestask-webapp-server-admin;Password=dmB3bsUuyK$GlzXK;MultipleActiveResultSets=False;Encrypt=True;TrustServerCertificate=False;Connection Timeout=30;"<br/>

Github pipeline to deploy dockerfile and run application tests. <br/>
database bacpac file is in .github repository of this organization.<br/>
Azure link : https://helmestask-webapp-d4gudgaqareth2eh.northeurope-01.azurewebsites.net/swagger/index.html

## Repository Helmes-Task-React
Upon all the sectors are loaded from backend.<br/>
User can insert name, pick wanted sectors and accept terms. <br/>
After filling out all required fields, user can press the update information button that register's the user (name and terms) and it's chosen sectors.<br/>
After that a session is created and the user can only edit and save chosen sectors.<br/>
Session stays even if the tab is reloaded.<br/>

You can start a new session by opening a new browser tab.<br/>

Azure link : https://nice-plant-0953f0503.6.azurestaticapps.net/





