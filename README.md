# Note Taker

![License Badge](https://img.shields.io/badge/license-MIT-green)

## Description

The Note Taker application allows users to write, save, and delete notes. This application uses an Express.js back end to handle the storage and retrieval of note data from a JSON file. It's designed to help small business owners organize their thoughts and keep track of tasks that need to be completed.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Mock-Up](#mock-up)
- [Acceptance Criteria](#acceptance-criteria)
- [Bonus](#bonus)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

1. Clone the repository to your local machine:

    ```sh
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```sh
    cd note-taker
    ```

3. Install the required dependencies:

    ```sh
    npm install
    ```

4. Start the application:

    ```sh
    npm start
    ```

## Usage

1. Open the application in your web browser by navigating to `http://localhost:3000`.

2. On the landing page, click the "Get Started" button to go to the notes page.

3. On the notes page, you can view existing notes in the left-hand column.

4. To add a new note, enter a note title and note text, then click the "Save Note" button. The new note will be saved and appear in the left-hand column.

5. To view an existing note, click on the note in the left-hand column. The note will be displayed in the right-hand column.

6. To create a new note, click the "New Note" button, which will clear the fields in the right-hand column.

7. To delete a note, click the delete button next to the note in the left-hand column.

## API Routes

The following API routes are available:

- `GET /api/notes`: Retrieves all saved notes as JSON.
- `POST /api/notes`: Saves a new note and returns the saved note.
- `DELETE /api/notes/:id`: Deletes a note with the given ID.

## Mock-Up

The following GIF shows the web application's appearance and functionality:

![Existing notes are listed in the left-hand column with empty fields on the right-hand side for the new note’s title and text.](./Assets/11-express-homework-demo.gif)

## Acceptance Criteria

The application meets the following criteria:

- When the Note Taker is opened, the user is presented with a landing page with a link to a notes page.
- When the link to the notes page is clicked, the user is presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column.
- When a new note title and note text are entered, a "Save Note" button and a "Clear Form" button appear in the navigation at the top of the page.
- When the "Save Note" button is clicked, the new note is saved and appears in the left-hand column with the other existing notes, and the buttons in the navigation disappear.
- When an existing note in the list in the left-hand column is clicked, the note appears in the right-hand column, and a "New Note" button appears in the navigation.
- When the "New Note" button is clicked, the user is presented with empty fields to enter a new note title and the note’s text in the right-hand column, and the button disappears.

## Bonus

As a bonus, the application includes functionality to delete notes. This is achieved through the following route:

- `DELETE /api/notes/:id`: Receives a query parameter containing the ID of the note to delete, removes the note from the `db.json` file, and rewrites the remaining notes to the file.

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please follow the standard GitHub flow for contributing: fork the repository, create a branch, commit your changes, and open a pull request.

## Questions

If you have any questions about the project, please feel free to reach out:

- GitHub: [ICONN21](https://github.com/ICONN21)
- Email: [Ian Connor](mailto:ian.connor0921@gmail.com)


