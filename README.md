# AZVoteReg

Static web app that:

1. Scans the PDF417 barcode on the back of an Arizona Driver License (mobile or desktop browser camera).
2. Parses and displays Name, Date of Birth, and Address.
3. Lets the user cancel or generate a pre-filled PDF download containing only the last page of the Arizona voter registration form.

## Run locally

From the repository root:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in a browser with camera access.
