
/**
* CEN 3024C - 13950 - Software Development 1
* */

This project is a Data Management System (DMS). The data that is being managed is Patient information. Each Patient object is stored in an ArrayList with the attributes of 
a unique 7-digit ID, a name, address, attending doctor, Insurance provider, and the day they attend for sessions. Users can perform the CRUD operations of Adding, Removing, 
Updating, and displaying all the patients. Additionally, I have created a custom function that counts the total number of patients that attend on a certain day. This day is 
given by the user, and the system outputs the total number of patients attending for that day.

To create a new patient to add to the system, users can either add in bulk by uploading a file (that meets the format criteria) or manually adding a single patient by filling 
out their attribute information. Removing a patient can be done by entering the patient that needs to be removed. Updating a patient's attribute works similarly, in that the 
patient's ID is required before the user chooses which attribute to change and what to change it to. Displaying the patients simply displays the list of the patients.

The program is structured so wrong input does not break it at any point. All interactions occur through the Command-Line Interface (CLI).

Also contains the Unit test file.
