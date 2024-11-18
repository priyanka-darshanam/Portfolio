## 3. `client/`

This directory contains the frontend code that allows users to input data and view predictions. The client communicates with the server to submit data and display the results.

### Key Files:

#### 1. `client-app.html`
The HTML file that defines the structure of the user interface. It provides input fields for the user to enter house features like area, number of rooms, location, etc. It also displays the predicted house price after receiving the response from the server.

#### 2. `app.js`
This JavaScript file handles the logic behind the user interface. It includes:
- Sending the input data from the HTML form to the server via a POST request.
- Receiving the prediction from the server.
- Displaying the result on the webpage.

#### 3. `app.css`
The CSS file that styles the frontend application. It makes the user interface visually appealing and responsive, ensuring that users have a good experience while interacting with the application.

---