RENZ SIKAT — PERSONAL PORTFOLIO WEBSITE
========================================

PROJECT FILES
-------------
1. index.html
   The main webpage. It contains the page structure, personal information,
   navigation, portfolio sections, and certificate preview dialog.

2. style.css
   The visual design: dark developer-terminal theme, colors, typography,
   responsive layouts, card styling, and animations.

3. script.js
   JavaScript for the mobile menu, active navigation state, scroll reveals,
   certificate detail modal, and automatic footer year.

4. index_html_code.txt
   A plain-text copy of index.html. It is kept identical to the HTML file.

5. assets/images/
   Place optional profile and certificate image files here. The current
   website uses clearly labeled placeholders because no actual images
   or certificate scans were provided.

HOW TO OPEN THE WEBSITE
-----------------------
1. Extract the ZIP file.
2. Open the renz_portfolio folder.
3. Double-click index.html.
4. The website will open in your default browser.

For editing, open the folder in Visual Studio Code or another code editor.
Keep index.html, style.css, and script.js in the same folder.

ADDING YOUR IMAGES
------------------
Profile photo:
- Put your image in assets/images/ and name it profile.jpg.
- The hero profile illustration is currently a placeholder. To use your
  photo, replace the .avatar-placeholder block in index.html with:
  <img class="profile-photo" src="assets/images/profile.jpg"
       alt="Portrait of Renz Cedrick M. Sikat">

Certificates:
- Put your actual certificate images in assets/images/.
- Suggested filenames: certificate-c-language.jpg and
  certificate-c-sharp.jpg.
- The certificate cards currently show placeholders. Replace each
  .certificate-art block with an image, for example:
  <img src="assets/images/certificate-c-language.jpg"
       alt="C Language certificate">
- Add the image styling in style.css if needed:
  .certificate-art img { width: 100%; height: 210px; object-fit: contain; }

GITHUB PAGES PUBLISHING
-----------------------
1. Sign in to GitHub and create a new repository, for example:
   renz-personal-portfolio
2. Upload all project files and the assets folder to the repository's
   root directory. Make sure index.html is at the root.
3. Open the repository's Settings.
4. Select Pages from the left sidebar.
5. Under "Build and deployment", choose "Deploy from a branch".
6. Select the main branch and the /(root) folder, then click Save.
7. Wait for GitHub Pages to publish the site. The published address will
   appear in the Pages settings, usually in this format:
   https://YOUR-USERNAME.github.io/renz-personal-portfolio/

NOTES
-----
- Replace placeholder certificate areas only with your real certificate
  images. No certificates or achievements have been fabricated.
- Add real projects to the Projects section when you have completed them.
- The Google Fonts connection is optional; the site uses fallback fonts
  if the fonts cannot load.
- Update your information in index.html whenever details change.
