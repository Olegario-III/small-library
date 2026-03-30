# Small Library

A simple web-based book library manager built with HTML, CSS, and Vanilla JavaScript.

## Features

- Add new books to your personal library
- Input fields for:
  - Book Title
  - Book Author
  - Year Published (using date picker)
- Clean and minimal user interface
- Books are displayed dynamically on the page

## Project Structure
small-library/
├── index.html      ← Main HTML file
├── styles.css      ← Stylesheet
├── Script.js       ← JavaScript logic (adding books + DOM updates)
└── README.md


## How It Works

1. Click the **"Add a Book"** button to reveal the form
2. Fill in the book details (Title, Author, Year)
3. The book is added to the library and displayed in the `#books` section
4. All data is managed in-memory using JavaScript (refreshes on page reload)

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript (no frameworks or libraries)

## How to Run

1. Download or clone the project
2. Make sure all files are in the same folder:
   - `index.html`
   - `styles.css`
   - `Script.js`
3. Open `index.html` in your browser (double-click or use Live Server)

No installation required.

## Future Improvements (Ideas)

- Add a "Delete Book" button
- Save books to `localStorage` so they persist after refresh
- Add search/filter functionality
- Display books in a card/grid layout
- Add book status (Read / Reading / To Read)
- Edit existing book details

## License

Free to use for learning and personal projects.

Made with ❤️ for learning DOM manipulation and basic CRUD operations.
