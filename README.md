## Vehicle Website Documentation

### 1. Introduction
The Vehicle Website is designed to provide information about various vehicle models, allow users to contact the organization, and provide an overall appealing and user-friendly experience. This documentation outlines the structure, design, and functionality used in the website, built with HTML, CSS, and JavaScript.

### 2. Project Structure
The project is divided into several key directories:
- **CSS**: Contains all the styling rules that define the layout and appearance of the website.
- **JavaScript**: Includes scripts that add interactivity and dynamic features to the website.
- **HTML**: The core structure of the website, holding the content and semantic elements.

### 3. HTML
HTML (HyperText Markup Language) is the backbone of the website, structuring the content in a meaningful and accessible way.

#### **index.html**
- **Header**: Contains the website's title and navigation links to different sections of the site (Home, Models, Contact).
- **Main Content**:
  - **Home Section**: Provides a welcome message and introduction to the website.
  - **Models Section**: Displays information about different vehicle models.
  - **Contact Section**: Features a contact form for users to fill out (Name, Email).
- **Footer**: Includes copyright information and is fixed at the bottom of the page.
- **Scripts**: JavaScript files are linked at the bottom of the HTML to ensure the document loads before scripts are executed.

### 4. CSS
CSS (Cascading Style Sheets) is used to style the HTML and ensure the website is visually appealing and user-friendly.

#### **styles.css**
- **Body**: Sets the default font and removes margin/padding.
- **Header**: Styles the header with background color, text color, and padding for a better appearance.
- **Nav**: Formats the navigation links to remove bullets and space them evenly.
- **Main**: Adds padding to the main content for readability.
- **Footer**: Styles the footer to match the header and remain fixed at the bottom of the page.

### 5. JavaScript
JavaScript is used to add interactivity to the website, making it more dynamic and engaging.

#### **scripts.js**
- **Form Submission**: Adds an event listener to the contact form to handle user input:
  - Prevents the default form submission behavior to handle data.
  - Checks if the name and email fields are filled out.
  - Displays a custom alert thanking the user or asking them to complete the form as needed.

---