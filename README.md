# Adolescncia re Saudee — Academic Journal Website Prototype

This is a static, responsive website prototype for **Adolescncia re Saudee**. It includes:
- Responsive homepage and navigation
- Searchable sample article cards
- Article detail modal with article ID, abstract, keywords and PDF link
- Archive-year filtering
- Editorial board section
- Author guidelines and contact section
- Custom original ARS-inspired book mark (not the logo of another journal)

## Important before publishing
All article records, abstracts, editorial details, ISSN and contact information are demonstrative placeholders. Do not present them as real publications. Replace them with verified information and genuine PDFs. Confirm that you have the right to use the chosen journal name and branding, and check name/domain/trademark conflicts. The sample email `editor@example.org` is not a real contact address.

## Test locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Search for an article ID such as `ARS-2026-001`, open a record and use its PDF link.

## Free hosting with GitHub Pages
1. Sign in or create an account at https://github.com/.
2. Create a new public repository, for example `adolescncia-re-saudee`.
3. Upload `index.html`, `styles.css`, `script.js`, the `pdfs` folder and this README. Keep the folder structure unchanged.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. The Pages screen will show the live URL.
7. Test the live website on mobile and desktop, and confirm each PDF opens.

## Add or update articles
Edit the `articles` array near the top of `script.js`. Each record uses:
- `id`: unique article ID
- `year`, `volume`, `issue`
- `title`, `authors`, `keywords`, `abstract`
- `pdf`: path to the PDF inside the website folder

Upload the genuine PDF to `pdfs/` and set the `pdf` path to its filename. Keep IDs unique. After changes, upload/commit the updated files to GitHub.

## Limitations
This is a static website, not a full journal management system. It does not provide author accounts, manuscript submission, peer review workflows, DOI registration, Crossref metadata deposits, indexing, or an admin dashboard. Those features require additional services or a platform such as Open Journal Systems (OJS). A contact form would also need a form service or backend.


## Article added in this update
- Article ID: `ARS-2026-004`
- Title: *Fuzzy Logic-Based Queuing Models for Uncertain and Imprecise Queueing Environments*
- Authors: Ravi Siwach, Pawan, and Vinod Kumar
- PDF file: `pdfs/fuzzy-logic-queueing-models.pdf`
- Citation shown from the uploaded PDF: *Adolescencia e Saude*, Volume 21, Issue 9s, pages 1065–1074. The source PDF does not clearly state a publication year, so verify it before treating 2026 as the original publication year; 2026 is the website listing year in this prototype.

The new article record includes the abstract and keywords transcribed from the uploaded PDF. Confirm that you have permission to host and redistribute the published PDF before making the website public.
