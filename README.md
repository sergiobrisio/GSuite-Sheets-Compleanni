# GSuite-Sheets-Compleanni
Code for launching birthday email from Sheets on GSuite

The application allows you to automatically send your birthday greetings to registered athletes, taking the data from the birth date field of one Google Sheet file.
Birthday should simply stay in the second column of the sheet.
The google script then proceeds to send the email from the gmail account.
The sendEmail () function is launched every day between 7 and 8 am checking if there is a match between day and month of the current date with the day and month of each athlete on the list.
The code refers to 2 document templates, the first (templateId) to be used for under 13, the second for over 13.
In the templates the name of the boy who turns years old, his age and date is dynamically replaced sending.
In the current implementation, the email is also sent to BCC to the author of the script and to the a list of other emails, for a verification of correct operation.
