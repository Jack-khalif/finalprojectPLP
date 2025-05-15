
#Final Project: E-Commerce Website by Jack Khalif
1. Project Overview
This project is a fully functional E-Commerce Website developed as part of the PLP Web Technologies course (Feb 2025). It showcases product listings, detailed product views, a shopping cart, and dynamic interactivity using JavaScript.

The website is designed with responsive HTML, CSS styling, and JavaScript for client-side dynamic content management.

2. Live Website URL
Access the live deployed website here:

👉 https://finalproject-plp.vercel.app/

3. GitHub Repository URL
All source code, including HTML, CSS, JavaScript files, images, and assets, are hosted on GitHub:

👉 https://github.com/PLP-WebTechnologies/feb-2025-final-project-and-deployment-Jack-khalif/tree/main

4. File Structure Overview
bash
Copy
Edit
/ (root)
├── index.html                # Main homepage
├── contentDetails.html       # Product details page
├── css/
│   └── contetDetails.css     # CSS for product details page
├── js/
│   └── contentDetails.js     # JavaScript for dynamic content rendering
├── images/                   # Images used in the website (product images, icons)
└── README.md                 # This documentation file
5. Features
Dynamic product listing and detailed views fetched via API calls.

Interactive image preview with clickable thumbnails.

Shopping cart with item count displayed as a badge.

Cookie-based cart item persistence across sessions.

Responsive design with clean layout.

External fonts and icons loaded via CDN (Google Fonts, FontAwesome).

6. How to Run Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/PLP-WebTechnologies/feb-2025-final-project-and-deployment-Jack-khalif.git
Navigate into the project folder:

bash
Copy
Edit
cd feb-2025-final-project-and-deployment-Jack-khalif
Open index.html or contentDetails.html in your preferred browser (you can open directly or serve via a local server).

7. Notes / Troubleshooting
The project uses vanilla JavaScript and XMLHttpRequest for fetching product data.

The live API endpoint is: https://5d76bf96515d1a0014085cf9.mockapi.io/product/

For development, ensure that you are serving your files on a local HTTP server rather than opening via file:// protocol to avoid CORS or path issues.

Example local server (Python):

bash
Copy
Edit
python -m http.server
Then visit http://localhost:8000 in your browser.

8. Acknowledgements
Product data API provided by MockAPI

Fonts by Google Fonts (Lato)

Icons by FontAwesome
