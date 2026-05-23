# Random User Generator

A simple web application that fetches and displays random user information using the Random User API. Generate realistic user profiles instantly and explore dynamically rendered data such as names, email addresses, locations, phone numbers, identification numbers, and profile pictures.

## Live Demo

https://fakeidentity.netlify.app/

## Features

- Generate random user profiles instantly
- Display profile picture
- View full name
- View email address
- View location and country
- View phone number
- View passport/ID number
- Fetch fresh data on every button click
- Responsive and lightweight design

## Project Structure

```bash
Random_User/
│
├── index.html
├── styles.css
└── README.md
```

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Fetch API
- Random User API

## API Used

https://randomuser.me/

## How It Works

1. A request is sent to the Random User API.
2. The API returns user data in JSON format.
3. JavaScript extracts the required information.
4. The DOM is updated dynamically.
5. Users can generate a new profile with a button click.

## Concepts Practiced

- Async/Await
- Fetch API
- JSON Parsing
- DOM Manipulation
- Event Handling
- Template Literals
- Error Handling with Try/Catch

## Challenges Faced

One of the main challenges was working with nested JSON objects returned by the API and extracting only the relevant information for display. Another challenge was dynamically updating page content without reloading the browser.

## What I Learned

This project strengthened my understanding of:

- Consuming third-party APIs
- Handling asynchronous JavaScript
- Working with JSON data
- Updating the DOM dynamically
- Building interactive web applications

## Future Improvements

- Dark mode support
- Loading spinner while fetching data
- Copy user information to clipboard
- Generate multiple users simultaneously
- User history tracking
- Enhanced card-based UI

## Author

Built by **Jubilant Shonhayi** as part of a JavaScript API integration and DOM manipulation practice project.
