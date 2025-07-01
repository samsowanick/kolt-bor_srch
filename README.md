# kolt
Koha Offline Library Tool

This tool is a standalone webpage that can create a Koha offline circulation file (.koc) when your internet connection is down.

To install, just download kolt.html to your desktop. That's it!

To use the tool, just scan item barcodes and library cards like normal with your cursor in the correct text field. This tool doesn't do payments, or hold information, as these require an internet connection to access the database. It only handles basic check-in and check-out functionality. The tool will save the data to the local browser cache until either the cache is cleared, or you click the "Clear" button. When this happens the data cannot be recovered, so make sure you have exported the data using the "Download Data" button first!

To upload the .koc file to Koha when you are back online:

- Click the "Download Data (.koc)" button. (You can name the file whatever you would like, by default it uses the current date and time on the computer.)
- Next, log-in to Koha through the staff interface and click on "Circulation." 
- Then click on "Upload offline circulation file (.koc)" at the bottom of the screen.
- Select your file using the "Choose File" button.
- Click "Upload File" then "Add to offline circulation queue."
- From there click "View pending offline circulation actions", then "Check all", then "Process."
