# Reggie

## Voter Registration Application:

0. Application is written in HTML, and works on Phones and Desktops.
1. Scans the PDF417 barcode on the back of a Driver License.
   1. Hard Coded for Arizona.
   2. Can use a cheap 2D Barcode Scanner or can use Camera.
2. Writes data to Arizona Voter Registration Page.
   1. Performs basic checks like Date of Birth and State.
   2. Auto Highlights required Fields.
3. User can then Print or Download as PDF file.
4. Usage Scenarios:
   1. Can be run in Kiosk Mode ( mode=autoprint ) on Windows Machine.</br>
   Use Barcode Reader, app will parse then automatically print to default printer.
   2. Can be run on Smart Phone. </br>
   User can input extra fields like E-Mail, Phone, Last4SSN, then print.
   3. Can be run on ANY Smart Phone. (After being directed by QR Code)</br>
   User can input all fields on their personal Smart Phone, and submit themselves

## Future:

* Use gathered data and query website to get up to date Voter Registration Status.
  * What public API's are available?
* Allow users to write their signature using finger on screen and add to form.
* Allow users to select approve on the remaining CheckBoxes.
* Allow for PDF forms to be sent (with verification) to:
  * Other Printers (as defined by QR Code)
  * 3rd party Servers (Party Servers)
  * County Registrars (Registration drives)
  