
# Login Screen Project for HW4 Question 5

## Overview

Welcome to the Login Screen Project for HW4 Question 5! This repository contains an interactive login screen implementation that meets the requirements specified in the task. It demonstrates HTML, CSS, and JavaScript integration to handle user input, authentication, and dynamic page theming.

## Features

- **User Authentication**: Verifies user ID and password against a predefined list.
- **Time Selection**: Allows users to select a time or automatically uses the current time.
- **Dynamic Theming**: Changes the page's theme (background and text color) based on the time of day.
- **Welcome Message**: Displays a personalized welcome message with the login date and time on the next page.
- **Local Storage**: Persists user details across pages using `localStorage`.

## Files in the Repository

- **index.html**: Main login page with user input fields.
- **q5-2.html**: Welcome page displayed upon successful login.
- **q5-style.css**: Stylesheet for theming and animations.

## Instructions

1. Clone this repository.
2. Open `index.html` in a web browser.
3. Test the login functionality using the predefined credentials:
   - **ID**: `dima`, **Password**: `123`
   - **ID**: `daria`, **Password**: `321`
   - **ID**: `vika`, **Password**: `111`
4. Explore the welcome page after successful login.

## How It Works

### Login Page (index.html)
- Input fields for:
  - **User ID** (text)
  - **Password** (password)
  - **Time** (optional; uses the current time if not provided)
- On submission, the script:
  - Validates input fields.
  - Checks credentials against the predefined user list.
  - Saves login details using `localStorage`.
  - Redirects to the welcome page if credentials are valid.

### Welcome Page (q5-2.html)
- Displays a personalized message with the user's ID, login time, and a greeting based on the time of day.
- Implements four themes:
  - **Morning**: 6:00 AM – 12:00 PM
  - **Afternoon**: 12:00 PM – 6:00 PM
  - **Evening**: 6:00 PM – 12:00 AM
  - **Night**: 12:00 AM – 6:00 AM

## Technologies Used

- **HTML**: Structure and layout of pages.
- **CSS**: Styling and animations for interactive visuals.
- **JavaScript**: Logic for authentication, theming, and data persistence.

## Requirements

- A modern web browser that supports HTML5, CSS3, and JavaScript.

## Future Enhancements

- Add user registration functionality.
- Enhance security with encrypted password storage.
- Improve mobile responsiveness.

---

### Author

Dmitriy Yugay  
[GitHub Profile](https://github.com/yudm3)  

Feel free to explore, fork, and contribute to this project!
