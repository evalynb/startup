## Records: Recorded
Startup application for CS 260

## Specification Deliverable

### Elevator Pitch

Do you enjoy streaming music? Do you also have a vinyl record collection? Have you ever wished that you could have a "Spotify Wrapped" esque music recap at the end of the year but specifically for your vinyl records? Well, if these things sound interesting to you, the Records: Recorded application makes it so that you can have a place to log which albums you listen to, tallies up how many times you have listened to them, what genres you listen to, and more! This application makes it easy and fun to create a space where you can keep track of your analog listenings and have a summary to share with your friends at the end of the year.  

### Design

![mock](starup_mock.jpg) 
![mock](https://github.com/[evalynb]/[startup]/blob/[branch]/mock_startup.jpg?raw=true)


### Key features

- Secure login with HTTPS
- Ability to input the names, artists, length, and genre of albums you have in your collection
- A display of the names, artists, length, and genre of albums in your collection
- Ability to tally up how many times you have listened to an album
- Total of times and minutes spent listening are displayed
- Ability for a user to sort their collection by name, artist, genre, or minutes listened
- Information is stored
- A display "summary" of the top five albums with optional user uploaded images, along with total minutes listened and top artists genres can be genereated

### Technologies

I will use the required technologies in these following ways:

- **HTML** - HTML structure will be used for the application. There will be one HTML page for the login and another one for the user to view and update their music log.
- **CSS** - The application's style will look appealing on different screen sizes. Good use of color, whitespace, and general design.
- **React** - This will provide the login, display of albums in the log, applying inputs of data, and use of React for routing and components.
-  **WebService** - Backend service with endpoints for the following;
-  login
-  retreving data
-  submitting data
-  displaying the summary
- **DB/Login** - Stores the users, album names, artists, genres, and lengths. Registers and login users. Credentials securely stored in database. Can't input your data unless authenticated.
- **WebSocket** - As each user inputs their data, it is saved and will be compilied into a final summary when prompted. 
