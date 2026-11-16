# Manas College Pithoragarh — Smart Library Management System

## Run it on GitHub Pages
1. Create a GitHub repository, for example `manas-smart-library`.
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for the Pages deployment and open the URL shown in Settings → Pages.

You can also test locally by double-clicking `index.html`.

## Demo logins
- Admin: `admin` / `admin123`
- Librarian: `librarian` / `lib123`

## Included features
- Dashboard and department-wise inventory summaries.
- Book catalogue with add/edit/delete, search and department/semester filters (semesters 1–6).
- Add Book form opens above the available-book list.
- Publisher/Place field label.
- Student registration without Mobile Number or Address fields; faculty details remain unchanged.
- Student and faculty records, ID verification, issue/return, stock updates, fines and reissue history.
- Reports, print and CSV exports.
- JSON data backup export and JSON backup import.
- Change-password option under **Settings & Data**.
- Non-blue green/neutral theme.
- Footer credit: **Manas College Pithoragarh · Powered by Manshi Joshi**.

## Login interface updates
- Uses the supplied original MCSTM logo on the login screen and sidebar.
- Adds a show/hide password control and discourages browser autofill on the demo login form.
- Clears the login fields on logout and re-checks the browser session when a cached page is restored.

## Important limitations
This version is for GitHub Pages/browser testing. Data is saved in the current browser's `localStorage`; it is not shared between computers and can be lost if browser storage is cleared. Importing a JSON backup replaces the current browser data, so export a backup first. Login credentials are demo-only and are not securely hashed. Client-side role checks are not real security. Do not enter sensitive real student/faculty information.

GitHub Pages cannot run PHP, Node.js, or MySQL. A production database and secure authentication require a backend/API connected to a database.
