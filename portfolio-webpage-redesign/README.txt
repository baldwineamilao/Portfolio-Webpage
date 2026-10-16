PORTFOLIO-WEBPAGE REDESIGN

FILES
- index.html: page content and structure
- styles.css: dark navy / electric blue responsive design
- script.js: mobile menu, scroll reveal, active nav, and current year

HOW TO USE
1. Back up your current portfolio files.
2. Copy index.html, styles.css, and script.js into the folder that Vercel serves (usually the repository root, or the configured Root Directory).
3. If the HTML files are inside a subfolder, ensure the Vercel Root Directory points to that folder.
4. Add your actual résumé PDF to the same folder as index.html and name it resume.pdf. The Download résumé button links to ./resume.pdf. If you use another filename, update href="resume.pdf" in index.html.
5. Open index.html locally to test, or use VS Code Live Server.
6. Commit and push the changes to GitHub; Vercel should deploy the update automatically if the repository is connected.

NOTES
- This is a static site: no build command or server-side runtime is required.
- The project cards intentionally do not invent repository or live-demo links. Add verified links when ready.
- The Student Management System and MyStatus descriptions should be adjusted if your actual implementations differ.
- Google Fonts is loaded online; the page falls back to generic sans-serif fonts if unavailable.
