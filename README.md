#Angular Notes App

Problem Statement:

The task is to build the Notes module in Angular JS, HTML5 and CSS3. Description of
the expected functionality, Mock-ups and Style-guide follow.
The basic concept is that a user wants to view a list of notes that are created within the
system. There is a form to create or edit a note, and a summary which gives some meta-data total
number of notes, last updated date and the note that was last updated.
The summary is collapsible when the collapse icon is clicked on and the form should expand,
accordion style, pushing the rows of text below it.

Functionality:

Display a list of notes 3 to 5 is sufficient.
1. The header row of the panel for the notes has two icons - a “+” and a “=”.
2. The “+” opens the form to create a new note and changes the “+” icon to a “ - ”.
3. The summary panel has a triangular icon in the upper right corner. Clicking it toggles the summary
panel closed.
4. Clicking a note opens the form and populates the form fields with the data for that note.
5. If the form is already open, it should remain open and any existing data is replaced with the data
for the respective note.
6. Clicking “save” should create a new note, and toggle the form closed. The page should not redraw,
only the new row appended to the list.
7. The list is sorted alphabetically ascending by default.
