# Python-Google-Spreadsheets
To remove/add/get data from Google Spreadsheets using Python
## Steps

(1) Go to google developers console [link](https://console.developers.google.com) </br>
(2) Create a project </br>
![project-python-google](https://user-images.githubusercontent.com/25201552/69144449-55bbf980-0af1-11ea-9cd6-9112fd082fd3.png)

(3) Then enable few API’s - Google Drive API and Google Sheets API. </br>
(4) Create credentials - ServiceaccountKey </br>

![cred-python-google](https://user-images.githubusercontent.com/25201552/69144227-d62e2a80-0af0-11ea-9c49-fd1d4734fec1.png)</br>
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
