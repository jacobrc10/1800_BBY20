## My Web Application (Title)

- [General info](#general-info)
- [Technologies](#technologies)
- [Contents](#content)

## General Info

This browser based web application to provide students with a simple and intuitive calendar and reminder system.

- Hi, my name is Simar. I am excited about this project since I will learn many things about programming and gain insight on how developers work together
- Hi my name is Jacob. I'm excited about this project because I get to learn more about how to create web applications.
- Hi my name is Owen. I'm excited about this project because...

## Technologies

Technologies used for this project:

- HTML, CSS
- JavaScript
- Bootstrap
- Calendar.js
- Firebase

## Content

Content of the project folder:

```
 Top level of project folder:
├── .gitignore               # Git ignore file
├── index.html               # Initial landing page with instant redirect to inner HTML files.
└── README.md

It has the following subfolders and files:
├── .git                            # Folder for git repo
├── html                            # Folder for html pages
    /about.html                     # About page with development team descriptions
    /add-class.html                 # Field entry for adding a course to the database
    /add-event.html                 # Field entry for adding an event to the database
    /add-recurring.html             # Field entry for adding a recurring event to database
    /calendar.html                  # Calendar system, displays the events from the database
    /chat.html                      # Online chat forum system, reads/writes to database
    /edit-class.html                # Reads the chosen course from the database and updates the doc
    /help.html                      # FAQ page for users
    /index.html                     # Landing page for introduction of app to non-users
    /links.html                     # Dynamically displays current courses of user
    /main.html                      # Landing page for returning users
    /mocktest.html                  # Page for the timer/practice test function
    /outline.html                   # Template containing the key elements of every page within the app
    /profile.html                   # Settings for the user's account, with option of deletion.
    /to-do.html                     # List-view of user's events.
├── images                          # Folder for images
    /account.png                    # Default account picture
    /Coming Soon.png                # Placeholder image for incomplete pages
    /default pfp 2.jpg              # Alternate default user icon
    /iconBlue.png                   # Course icon option
    /iconCyan.png                   # Course icon option
    /iconGreen.png                  # Course icon option
    /iconRed.png                    # Course icon option
    /iconYellow.png                 # Course icon option
    /jacob.jpg                      # Development Team Member Photo
    /owenpraying.jpg                # Development Team Member Photo
    /simar.jpg                      # Development Team Member Photo
    /square images.jpg              # Development Team Member Photo
    /square owen.jpg                # Development Team Member Photo
    /Student.png                    # Example student image
    /transparent task list.webp     # Tasklist visual element
├── scripts                         # Folder for scripts
    /calendarjs.js                  # Sourcecode for the calendar system.
    /my_script.js                   # Functions utilized throughout the app.
├── styles                          # Folder for styles
    /about.css                      # Stylings used for the about page.
    /calendarjs.css                 # Source stylings native to the calendarjs app
    /chatbox.css                    # Stylings catered for the chat feature
    /my_style.css                   # Stylings used to override bootstrap presets
    /signin.css                     # Stylings used for the sign-in elements

Firebase hosting files:
├── .firebaserc              # Firebase generated file for deployment.
├── 404.html                 # Firebase generated page for Error 404 cases.
├── firestore.indexes.json   # Firebase generated json file for deployment.
├── firestore.rules          # Firebase generated file for deployment.
├── storage.rules            # Firebase generated file for deployment.


```

Tips for file naming files and folders:

- use lowercase with no spaces
- use dashes (not underscore) for word separation
