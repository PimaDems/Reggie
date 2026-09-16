# Reggie

Static Voter Registration Application:

1. Scans the PDF417 barcode on the back of an Arizona Driver License (mobile or desktop browser camera).
2. Parses and displays Name, Date of Birth, and Address.
3. Lets the user cancel or generate a pre-filled PDF download containing only the last page of the Arizona voter registration form.

## Form PDF file

Place a trusted local copy of the form PDF in the repository root (next to `index.html`) as:

`AZ-State-Voter-Registration-Form-Dec2025-fillable.pdf`

Download it from the official Arizona Secretary of State URL:

`https://azsos.gov/sites/default/files/docs/AZ-State-Voter-Registration-Form-Dec2025-fillable.pdf`

The app reads this local file to avoid runtime dependency on an externally hosted PDF.
