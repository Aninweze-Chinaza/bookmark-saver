# Bookmark Saver

A simple browser-based bookmark manager built with HTML, CSS, and JavaScript.

This project allows users to save useful websites directly in their browser, open saved links in a new tab, and remove bookmarks when they are no longer needed. Bookmarks are stored using the browser's `localStorage`, so they remain available even after refreshing or reopening the page.

## Features

* Add a bookmark with a custom name and URL
* Validate that a URL uses `http://` or `https://`
* Save bookmarks to browser `localStorage`
* Automatically restore saved bookmarks when the page loads
* Open saved bookmarks in a new browser tab
* Remove bookmarks from the list
* Simple and responsive interface

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Browser Local Storage API

## How It Works

When a user enters a bookmark name and URL, JavaScript validates the information before adding it to the bookmark list.

The bookmark is then stored in `localStorage` as an array of objects containing the bookmark name and URL.

For example:

```javascript
{
  name: "FreeCodeCamp",
  url: "https://www.freecodecamp.org/"
}
```

When the application loads, the saved bookmarks are retrieved from `localStorage` and displayed again.

Removing a bookmark also removes it from browser storage.

## Project Structure

```text
bookmark-saver/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## Getting Started

No installation or dependencies are required.

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Open the project folder.

3. Open `index.html` in your browser.

4. Enter a bookmark name and URL.

5. Click **Add Bookmark**.

The bookmark will be saved locally in your browser.

## What I Practiced

This project gave me practical experience with:

* DOM manipulation
* Event listeners
* Form/input handling
* JavaScript functions
* Arrays and objects
* JSON serialization and parsing
* `localStorage`
* Creating and removing DOM elements
* Basic URL validation
* Working with browser APIs

## Learning Note

This project was built as part of my JavaScript learning journey while following a FreeCodeCamp tutorial.

Rather than treating the tutorial as the end goal, I used the project as an opportunity to understand how JavaScript interacts with the DOM and browser storage.

## Future Improvements

Possible improvements include:

* Add an edit bookmark feature
* Add bookmark categories
* Add search/filter functionality
* Add better form validation and error messages
* Add a confirmation before deleting a bookmark
* Improve accessibility
* Add a dark mode
* Add favicon previews for saved websites
* Improve the overall UI/UX

## Author

**Aninweze Chinaza**

Computer Science Student | Frontend Development Learner

---

Built as part of my continued journey learning and practicing frontend development.
