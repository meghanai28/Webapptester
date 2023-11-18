## Functional Requirements
1. Sign In
2. Sign out
3. Register an account
4. Create Folders
5. Edit notes
6. Export Notes
7. Attach Images
8. Search notes by note names
9. Delete user profile
10. Search with advanced expressions
11. Connect to Google Translate API
12. Edit user profile
13. Create Tables with Links to Notes
14. Delete Notes

# UI Sketch with Functionals
1. [Account Page](images/ui1.png)
2. [Delete User Page](images/ui2.png)
3. [Edit Note Page](images/ui3.png)
4. [Edit Table Page](images/ui4.png)
5. [Edit User Profile Page](images/ui5.png)
6. [Index Page](images/ui6.png)
7. [Register Account Page](images/ui7.png)

## Non-functional Requirements
1. Only work expect to work Google Chrome
2. Multilingual Support
3. Dark mode
4. Change font colors


Yousef Asad

**1. Sign in**
- **Summary:**
This use case outlines the steps a User follows to sign in to the Notes Application, allowing them to access their personalized notes, settings, and other features.
- **Actors:**
User and Notes Application
- **Pre-condition:**
User has the app installed and loaded to sign in page
- **Trigger:**
User clicks sign in button on apps login page
- **Primary Sequence:**
1. The Notes Application displays the sign-in interface, prompting the User to enter their username and password.
2. The User enters their registered email address and password
3. The Notes Application validates the entered information by verifying it against the stored database.
4. If the entered credentials are valid, the User is logged in
- **Primary Postconditions:**
User Logs in
-The User is signed in and can access their stored notes, preferences, and other personalized features within the Notes Application.
User is not logged in
-User is stuck at login page
- **Alternate Sequence:**
Invalid Password
1. User inputs invalid password
    1. Systems prompts forgot password option
    2. System sends link to email with password recovery tool
- **Alternate Sequence:**
User has not registered an account yet
1.  Select the "Sign Up" option to create a new account.
2. Input credentials


Yousef Asad

**2. Sign Out**

- **Summary:**
This use case outlines the steps a User follows to sign out of the Notes Application, allowing them to exit their session.
- **Actors:**
User and Notes Application
- **Pre-condition:**
The User has the Notes Application installed and is currently logged in, viewing the application's interface.
- **Trigger:**
User clicks sign out button
- **Primary Sequence:**
1. Pop up prompts if user wants to sign out
2. User clicks sign out
3. App redirects user to sign in page
- **Primary Postconditions:**
User is signed out
-The User is redirected to sign in page
User not signed out
-User remains on page where they had been last
- **Alternate Sequence :**
User Cancels signout procedure
1. Sign out window closes
2. System displays page where user was


Yousef Asad

**3.  Register an account**
- **Summary:**
This use case outlines the steps a User follows to register an account on the notes app
- **Actors:**
  User and Notes Application
- **Pre-condition:**
User has the app installed and loaded to sign in page
- **Trigger:**
User clicks register account button
- **Primary Sequence:**
1. User clicks register account
2. System opens new registration page
3. System Prompts user to enter personal information
4. User clicks register account
5. App redirects user to sign in page
6. User signs in with credentials
- **Primary Postconditions:**
User is signed in with newly registered account
-The User is redirected to home page
User is not registered
-User remains on signup page
- **Alternate Sequence :**
User input Email that is already in use
1. App displays error to user
2. Prompts user to login with email or use different







Yousef Asad

**4.  Create Folders**

- **Summary:**
This use case outlines how Users can organize their notes using a folder system directly on the home page of the Notes Application
- **Actors:**
User and Notes Application
- **Pre-condition:** The User has the Notes Application installed and is on the home page
- **Trigger:** User clicks on homepage
- **Primary Sequence:**
1. User creates folder and names it
2. User drags or uploads notes in specified folder
3. User toggles through different folders on home menu
- **Primary Postconditions:**
The User can efficiently organize their notes
-using a folder system on the home page, enhancing their ability to categorize and navigate their content effectively.
User does not change anything on home layout
-User home page remains the same
- **Alternate Sequence :**
User does not change home layout
1. Home page remains organized in a standard grid or list format.


