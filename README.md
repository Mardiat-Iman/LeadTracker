# LeadTracker
A Lead Tracker chrome extension and web-mobile app.
In a recent internship, one of my main tasks was getting leads. To keep track, I manually copied and pasted into an Excel sheet. 
In the Scrimba JavaScript course I built a lead tracker extension. With this you can copy and paste leads into the tracker without going back and forth with your website and your excel sheet. The tracker also saves the leads inputed.

Right now the data is stored locally within the user's browser using localStorage. localStorage is a web storage API that allows web applications to store data persistently in the browser. This means that the data, such as the saved leads (URLs), will remain even after the browser is closed and reopened. The data is stored as key-value pairs, where both the key and value are strings.
The project utilizes JSON.stringify() to convert JavaScript objects (like arrays of leads) into strings before storing them in localStorage, and JSON.parse() to convert them back into JavaScript objects when retrieving them.
Next steps would be to store the data in a database where the information can then be downloaded.
