# Stock Screener
Stock screener to grab live data from a stock exchange that we will then use to personalize certain indicators and notifications to use to trade. 

Create a website / program that will use APIs to offers access to a wide range of financial information, including stock prices, economic indicators, and alternative data

https://www.nasdaq.com/solutions/data-link-api

# Define Requirements and features.

1. at least a 2 page front end, one landing page and one for dashboard.
2. dashboard with widgets 
3. customizable with a UI 
4. must save users dashboard at the end. 


Step 1: Define Requirements and Features
Sit down with your teammate and discuss what features your dashboard will have.
List out the functionalities you want to include, such as displaying stock and crypto data, customizing widgets, user authentication, etc.
Step 2: Design the User Interface (UI)
Sketch out the layout of your dashboard on paper or using a design tool.
Decide on the overall look and feel, including color scheme, typography, and component placement.
Step 3: Set Up Your Development Environment
Install necessary tools and software, such as a text editor, Git for version control, and any frameworks or libraries you'll be using.
Step 4: Frontend Development
Start by creating the basic structure of your HTML pages for the dashboard.
Use CSS to style your pages according to the UI design you created.
Implement interactivity and dynamic behavior using JavaScript, such as fetching data from APIs and updating the UI accordingly.
Step 5: Backend Development
Choose a Python web framework like Flask or Django for your backend.
Set up routes to handle requests from the frontend and serve the appropriate responses.
Implement logic to retrieve stock and crypto data from APIs or databases.
Step 6: Integrate APIs
Find suitable APIs for fetching stock and crypto data. Services like Alpha Vantage or CoinGecko provide APIs for this purpose.
Write functions in your backend to fetch data from these APIs and return it to the frontend.
Step 7: Database Setup (Optional)
If you need to store user data or any other information, set up a database using tools like SQLite (for small projects) or PostgreSQL (for larger projects).
Define the database schema and create tables to store data.
Step 8: User Authentication (Optional)
If your dashboard will have user accounts, implement user authentication functionality.
Use libraries like Flask-Login (for Flask) or Django's built-in authentication system to handle user login and registration.
Step 9: Testing
Test each component of your application thoroughly to ensure everything works as expected.
Write unit tests for your backend logic and integration tests for your frontend components.
Step 10: Deployment
Choose a hosting platform for your application, such as Heroku, AWS, or DigitalOcean.
Deploy your frontend and backend code to the hosting platform.
Set up any necessary configurations, such as environment variables and domain settings.
Step 11: Continuous Integration and Deployment (CI/CD) (Optional)
Implement a CI/CD pipeline to automate the testing and deployment process.
Tools like Jenkins, Travis CI, or GitHub Actions can help you set up automated workflows for testing and deploying your code.







# Project Structure

my_flask_app/
|-- app.py
|-- templates/
|   |-- index.html
|-- static/
|   |-- css/
|   |   |-- styles.css
|   |-- js/
|   |   |-- script.js


