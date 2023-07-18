# RSS_Parser
1. Ensure you have the 'all-rss.xml' file:
   - Place the 'all-rss.xml' file in the root directory of the project.
   - This file should contain the XML data that will be parsed by the app.

2. Install additional dependencies:
   - Node.js: Make sure you have Node.js installed on your machine. You can download it from [https://nodejs.org](https://nodejs.org).
   - In addition to the dependencies required for a basic React app, you need to install the some other dependencies.
   - Run the following command in the terminal to install the required dependencies:

     npm install google-map-react
     npm install xml2js
     npm install axios
     npm install react-router-dom


3. Configure Google Maps API key:
   - Open the 'SimpleMap.js' file.
   - Replace the empty string "" in the 'bootstrapURLKeys' prop with your Google Maps API key.

4. Start the development server:
   - Run the following command in the terminal:
    
     npm start

   - This will start the development server and the app will be accessible at 'http://localhost:3000'.

5. Access the app:
   - Open a web browser and go to 'http://localhost:3000'.
   - You should see the RSSParserComponent page.
   - Click on the "Map" link in the navigation bar to navigate to the SimpleMap page.
