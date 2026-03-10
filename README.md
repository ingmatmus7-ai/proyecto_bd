# Notary Website Documentation

## Overview
This document provides an overview of the HTML and CSS structure for the Notary website project.

## HTML Structure
The HTML is organized into several key sections:

- **Header**: Contains the logo and navigation menu.
- **Main Content**: Includes the main form for user input and any other relevant information sections.
  - **Form Fields**: 
    - **Name**: Input field for the user's name.
    - **Email**: Input field for the user's email address.
    - **Date of Birth**: Input field for the user's date of birth.
    - **Notary Services**: Drop-down selection for types of notary services.
    - **Submit Button**: Button to submit the form.
- **Footer**: Contains copyright information and links to terms of service.

## CSS Structure
The CSS file is designed to ensure the website is responsive and visually appealing:
- **Base Styles**: General styles for body, typography, and links.
- **Header Styles**: Specific styles for header layout and navigation.
- **Form Styles**: Styles for the form layout, input fields, and buttons.
- **Media Queries**: Ensures proper layout on various screen sizes.

## Database Tables
- **Users Table**: Stores user information.
  - **id**: Primary key for the user.
  - **name**: User's full name.
  - **email**: User's email address.
  - **date_of_birth**: User's date of birth.

- **Notary Services Table**: Stores information about the notary services.
  - **service_id**: Primary key for the service.
  - **service_name**: Name of the notary service.

## How to Use the Code
To set up the Notary website:
1. Clone the repository: `git clone https://github.com/ingmatmus7-ai/proyecto_bd.git`
2. Open the `index.html` file in a web browser to view the website.
3. Use the form to input necessary information and submit.

For styling, ensure that the `styles.css` file is linked correctly in the HTML file.