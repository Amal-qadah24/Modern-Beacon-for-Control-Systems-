Modern Beacon — Amman night slideshow

The three uploaded photos replace the existing static city background on all pages:
Home, About, Services, Contact, Projects, Products and the other inner pages.
The title and buttons remain static; photos change every 5 seconds with a smooth fade.

To switch every 3 seconds instead, open assets/js/site.js and change:
    const delay = 5000;
to:
    const delay = 3000;

Open the folder in VS Code and run index.html with Live Server.
All new pictures are in assets/images/ as amman-night-1.jpg, amman-night-2.jpg, amman-night-3.jpeg.
Do not mix these files with a different version of site.js/style.css without checking.
