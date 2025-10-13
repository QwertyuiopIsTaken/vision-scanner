# Image-Data-Analyzer

Utilizing Google Cloud Vision API, this program can effectively scan image files (jpg, jpeg, png) and extract data and put them into a CSV file.

This program requires you to have a Google API key to access Cloud Vision.

## Installation

1. Install Node.js
1. Create an API key on console.cloud.google.com.
	1. Look for "API Library" on the search bar
	2. Search "Cloud Vision API" and press Enable
	3. Next look for "Service accounts" on the search bar
	4. Press "Create Service Account" on the top
	5. Give your service account a name and press Done
	6. Under the Actions column, press the three dots and press "Manage keys"
	7. Press Add key and create new key.
2. Place the API json file inside the "api_key" folder.

## Instructions

1. Upload all image files inside the "pages" folder.
2. In the command line run `node index.js`.
3. Check for the exported CSV file inside the "results" folder.
