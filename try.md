Meghana Indukuri

**11.  Connect to Google Translate API**

- **Summary:**
Users should be able to convert their notes from one language to another. The application should utilize the google translate API so the user can do so.
-**Actors:**
    	User and Notes Application
- **Pre-condition:**
User is at the edit notes page
- **Trigger:**
User clicks translate button located on the edits note page
- **Primary Sequence:**
1. System prompts the user to select the language to translate the note to.
2. User clicks on the language they would like to translate the note to.
3. System utilizes the google translate API.
4. Google translate API translates the text in the note, and sends it back to the application
5. The text is then translated using the information provided by the google translate API.
6. The user can then save the note with the translated text.
- **Primary Postconditions:**
The note will have the translated text saved, and when the user decides to edit it again, only the translated text will be shown. User will return to the homepage
- **Alternate Sequence:**
User does not save changes to the note after translation
1. System prompts the user to select the language to translate the note to.
2. User clicks on a language
3. System utilizes the google translate API.
4. Google translate API translates the text in the note, and sends it back to the application
5. The text is then translated using the information provided by the google translate API.
6. The user decides not to the save the note with the translated text
1. The text is not saved, and the user returns back to the homepage
- **Alternate Sequence :**
User tries to translate note from a language to the same language
1. System prompts user to select the language to translate the note to
2. User selects a language the note is already written in.
3. System utilizes the google translate API.
4. Google translate API, makes no translation and informs the application of no new text
5. The application makes no changes to the text
1. The user has no new text to save


Meghana Indukuri

**12.  Edit User Profile**

- **Summary:**
Users should be able to edit their user profile, to change their password, name or username.
-**Actors:**
User and Notes Application
- **Pre-condition:**
User is at the edit user webpage and has an account
- **Trigger:**
User clicks change password,username or name option located on the edit user webpage.
- **Primary Sequence:**
1. User selects which of their personal information they would like to modify.
2. User gets prompted with a textbox to change to a new username, password or name
3. User must enter their new username,password or name in the textbox
4. User must repeat their new username,password or name in the textbox
5. Application prompts the user with an “are you sure?” message
6. User clicks yes
7. User’s username, password or name is permanently modified
- **Primary Postconditions:**
User has a new username, password or name after the modification. Users must use the new username, password or name whenever they sign in from this point forward.
- **Alternate Sequence:**
User tries to change existing personal information with the same information
1. User selects which of their personal information they would like to modify
2. User gets prompted with a textbox to change to a new username, password or name
3. User enters the same username, password or name as the existing ones
1. Application prompts user with an invalid password message
2. User can enter a new password, username or name in the textbox
- **Alternate Sequence :**
User decides to not change information
1. User selects which of their personal information they would like to modify.
2. User gets prompted with a textbox to change to a new username, password or name
3. User must enter their new username,password or name in the textbox
4. User must repeat their new username,password or name in the textbox
5. Application prompts the user with an “are you sure?” message
6. User clicks no
1. No changes are made to the user’s name, username or password

Meghana Indukuri

**13.  Create Tables with Links to Notes**

- **Summary:**
Users should be able to create tables in the application that contain links to existing notes in their account on the application.
-**Actors:**
User and Notes Application
- **Pre-condition:**
User is at the tables webpage in the application
- **Trigger:**
User clicks create table in the tables webpage
- **Primary Sequence:**
1. Web application prompts user to enter number of rows and columns
2. User selects wanted rows and columns
3. Empty Table is created by web application
4. User can type in the cells of the table
5. User selects links of existing notes from the side of the webpage
6. Selected links are inserted into the cells of the table by the user
7. The table is then be saved by the user
- **Primary Postconditions:**
User has a new table that is saved with the information they added while editing the table. The table contains links to notes from their accounts that they have written before.
- **Alternate Sequence:**
User enters invalid rows and columns for each table creation
1. Web application prompts user to enter number of rows and columns
2. User enters invalid row and column values
1. Web application displays an error message
2. User is prompted to enter correct row and column values
- **Alternate Sequence :**
User creates table with no note links
1. Web application prompts user to enter number of rows and columns
2. User selects wanted rows and columns
3. Empty Table is created by web application
4. User saves empty table
1. Table is saved to the application under the user's account, but is empty containing no links to any existing notes.

Meghana Indukuri

**14.  Delete Notes**

- **Summary:**
Users should be able to delete their existing notes
-**Actors:**
User and Notes Application
- **Pre-condition:**
User is at the edit note webpage of the application
- **Trigger:**
User clicks on the delete button located on the edit note webpage.
- **Primary Sequence:**
1. System prompts user to with message asking to confirm deletion, with options yes or no
2. User selects yes
3. Note content is deleted by application
4. User is returned to homepage
5. Application no longer displays deleted note on homepage
- **Primary Postconditions:**
Note is permanently removed from the user's account and cannot be retrieved.
- **Alternate Sequence:**
User decides to not delete note
1. System prompts user to with message asking to confirm deletion, with options yes or no
2. User selects no from prompt
    1. User remains on edit note webpage
    2. Note remains unchanged and not deleted
