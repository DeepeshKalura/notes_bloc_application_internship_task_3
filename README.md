# notes_bloc_application

Use flutter_bloc package and proper repository pattern for the app, Through
the note taking application, a user must be able to create a note and view the list of notes. User should be able to click on the note to view. 

## What to build?

Screens:
1. Notes Screen

    a. It shows list of all the notes. (each note card with title and max 2 lines of description)

    b. Add a floating action button to navigate to "add note screen".

    c. Clicking on note should open note details.

2. Add Note Screen

    a. Add 2 text input fields for title and description respectively.

    b. A button to save the note, after saving the previous screen should show the new note being added.

3. Using Firebase-Firestore for the app:

    a. Create a firebase project on your account to build this app

    b. Inside the app, firestore's persistent storage should be disabled.

    c. Use proper queries for showing the on the screen. (ex: for displaying list of trash note you should not query all the documents)


## Images of Application