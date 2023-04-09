# Chrome Extension - MyLeads
## Introduction
This Chrome extension, called MyLeads, allows the user to save and store URLs for later viewing. The user can save the URL of the current tab by clicking the "Save Tab" button. Additionally, the user can save custom URLs by typing the URL into the input field and clicking the "Save Input" button. The saved URLs are displayed in a list on the page and can be clicked on to open the corresponding website.

## Getting Started
To use this extension, simply download and install it from the Chrome Web Store. Once installed, click the extension icon to open the MyLeads page.

## Usage
The MyLeads page has two main sections: "Current Tab" and "My Leads". The "Current Tab" section displays the URL of the currently active tab, along with a "Save Tab" button that allows the user to save the URL for later viewing. The "My Leads" section displays a list of all the URLs that the user has saved.<br><br>

To save a custom URL, type the URL into the input field and click the "Save Input" button. The URL will be added to the list of saved URLs in the "My Leads" section.<br><br>

To view a saved URL, click on the URL in the list. This will open the corresponding website in a new tab.<br><br>

To delete all saved URLs, double-click the "Delete All" button. This will clear the list of saved URLs and remove them from local storage.

## Code
The MyLeads extension is built using HTML, CSS, and JavaScript. The main JavaScript file, index.js, contains all the code for saving, retrieving, and displaying the saved URLs.<br><br>

The extension uses the Chrome API to access the current tab's URL and to open new tabs. It also uses the localStorage API to store the saved URLs on the user's local machine.
