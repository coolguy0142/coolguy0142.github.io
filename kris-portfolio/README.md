# Kris Ram — Portfolio

A responsive, multi-page website with no installation or build step.

## Preview
Open index.html in your browser, or run `python3 -m http.server 8000` in this folder.

## Publish on GitHub Pages
1. Extract this ZIP.
2. Upload the CONTENTS of this folder to your USERNAME.github.io repository. index.html must be at the repository root.
3. Settings → Pages → Deploy from a branch → main → /(root) → Save.

## Edit your site
- index.html: home page
- projects.html: project collection
- robot.html and sensor-board.html: detailed project pages
- skills.html: languages and tools
- about.html: biography
- contact.html: contact information (currently intentionally unconnected)
- assets/style.css: colours, spacing and typography

## Add photos
Put your photos in assets/, then replace the project-art element with:
<img class="banner" src="assets/robot-photo.jpg" alt="My line-following robot">
Use the same filename and capitalisation in the HTML and assets folder.

## Add contact links
Replace the coming-soon section in contact.html with your real links:
<a class="big-link" href="https://github.com/YOUR-USERNAME">GitHub</a>
<a class="big-link" href="https://www.linkedin.com/in/YOUR-PROFILE/">LinkedIn</a>
<a class="big-link" href="mailto:YOUR-EMAIL">Email me</a>

## Add a project
Duplicate robot.html and change the filename, page title and text. Add a link to it in projects.html. Update the selected-work cards on index.html too.

The descriptions are starting points based on your shared work; edit them to match your exact role and outcomes. No invented results, contact details or live submission forms are included.
