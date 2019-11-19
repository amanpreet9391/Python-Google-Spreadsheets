# Python-Google_Spreadsheets
To remove/add/get data from Google Spreadsheets using Python
## Steps

(1) Go to google developers console [link](https://www.youtube.com/redirect?q=https%3A%2F%2Fconsole.developers.google.com&v=7I2s81TsCnc&event=video_description&redir_token=JVX1cS-KrucXR1BzKHqzTXJj2Pl8MTU3NDI0OTY2NkAxNTc0MTYzMjY2) </br>
(2) Create a project </br>
(3) Then enable few API’s - Google Drive API and Google Sheets API. </br>
(4) Create credentials - ServiceaccountKey </br>
(5) Then it will download a json file which will contain credentials. </br>
(6) From that json file copy the “CLIENT EMAIL ADDRESS” </br>
(7) Then create a google spreadsheet and share the sheet with client email address. </br>
(8) Now install the required python library </br>
`pipenv install gspread` , `pipenv install oauth2client` , `pipenv install PyOpenSSL` </br>
This are few modules we need in our python script.
Then Start writing the python script.`example.py` is the script with the help of which we print or delete or append the data in Google Spreadsheet.
![python-google2-2](https://user-images.githubusercontent.com/25201552/69143876-075a2b00-0af0-11ea-9afa-41b84df81521.png)
This is screenshot of the spreadsheet, which includes few entries. 
![python-gooogle2](https://user-images.githubusercontent.com/25201552/69143917-25279000-0af0-11ea-81ab-f59167e5382d.png)
And here are the values returned by our python script. Actually data is stored as a dictionery( having key-value pairs).</br>
