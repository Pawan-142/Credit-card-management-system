#Contact Manager JavaScript Project
This project is a simple contact manager application built using JavaScript. The application allows users to add, edit, delete, and view contacts. The project is hosted on Firebase, which provides a real-time database to store the contacts and enables immediate updates to the contact list for all users.

##Usage
To use the contact manager, you can either open the live version at https://ourcontacts-6b243.web.app/#/ or download the code from the repository and open the index.html file in your browser. Once the application is open, you will be presented with a list of contacts and options to add, edit, and delete contacts.

##Adding a Contact
To add a contact, click the "Add Contact" button and enter the contact information in the form. Once you have entered the contact information, click "Save" to save the contact.

##Editing a Contact
To edit a contact, click the "Edit" button next to the contact you wish to edit. Edit the contact information in the form and click "Save" to save the changes.

##Deleting a Contact
To delete a contact, click the "Delete" button next to the contact you wish to delete.

##Installation
To install the project, simply clone the repository and open the index.html file in your browser.

bash
Copy code
git clone https://github.com/<username>/contact-manager.git
cd contact-manager
File Structure
The project's file structure is as follows:

python
Copy code
contact-manager/
├── css/
│   ├── bootstrap.min.css
│   └── style.css
├── js/
│   ├── app.js
│   ├── bootstrap.min.js
│   ├── jquery-3.6.0.min.js
│   └── popper.min.js
├── index.html
├── LICENSE
└── README.md
The css/ directory contains the bootstrap.min.css file, which is a CSS framework used to style the contact manager, and the style.css file, which contains additional custom styles.

The js/ directory contains the app.js file, which contains the main JavaScript code for the contact manager, as well as the bootstrap.min.js, jquery-3.6.0.min.js, and popper.min.js files, which are JavaScript libraries used to enhance the functionality of the contact manager.

The index.html file is the main HTML file for the contact manager.

The LICENSE file contains the license information for the project.

The README.md file contains information about the project and instructions for installing and using the contact manager.

Firebase Integration
The live version of the contact manager at https://ourcontacts-6b243.web.app/#/ is hosted on Firebase and uses Firebase Realtime Database to store the contacts. Firebase is a powerful platform for building web and mobile applications, and it provides a wide range of features, including hosting, databases, authentication, and more.

To integrate Firebase into your own project, you will need to create a Firebase account and follow the instructions for setting up Firebase in your project. Once Firebase is set up, you can use the Firebase SDKs to access Firebase services in your JavaScript code.

Contributing
If you would like to contribute to the project, please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT license. See the LICENSE file for more details.
