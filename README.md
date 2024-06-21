# Note-Taking Application

This is a simple note-taking application built with HTML, CSS, and JavaScript. Users can create, edit, and delete notes, with all changes automatically saved to `localStorage` for persistence. This ensures that notes are retained even after the page is reloaded.

## Features

- **Create Notes:** Add new notes by clicking the "Create Note" button.
- **Edit Notes:** Click on a note to edit its content. Changes are saved automatically.
- **Delete Notes:** Click the delete icon on a note to remove it.
- **Persistent Storage:** Notes are saved in `localStorage`, ensuring they persist across page reloads.

## Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/note-taking-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd note-taking-app
    ```
3. Open `index.html` in your browser to use the application.

## File Structure

- `index.html`: The main HTML file containing the structure of the application.
- `styles.css`: The CSS file for styling the application.
- `script.js`: The JavaScript file for handling the functionality of the application.
- `images/`: A directory containing the delete icon image.

## Code Overview

### HTML (index.html)

Defines the structure of the application, including a container for notes and a button to create new notes.

### CSS (styles.css)

Styles the application, giving it a clean and modern look.

### JavaScript (script.js)

Handles the creation, deletion, and updating of notes, ensuring that all changes are saved to `localStorage` for persistence.
