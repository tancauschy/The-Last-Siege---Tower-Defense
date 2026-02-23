# Legal Pages – The Last Siege - Tower Defense

Terms & Conditions, Privacy Policy, Account Deletion, and Information for Parents.

## Deploy to GitHub Pages

### Option A: User/org site (e.g. `username.github.io`)

1. Create a repo named `username.github.io` (replace with your GitHub username)
2. Push the contents of this folder to the `main` branch
3. In repo **Settings → Pages**, set source to **Deploy from a branch**
4. Branch: `main`, folder: `/ (root)`
5. Your site will be at `https://username.github.io`
6. Add a folder for the game, e.g. `thelastsiege/`, and put these files inside:
   - URLs: `https://username.github.io/thelastsiege/terms.html`, etc.

### Option B: Project site (e.g. `thelastsiege` repo)

1. Create a repo (e.g. `thelastsiege` or `the-last-siege`)
2. Push this folder's contents to the `main` branch (or create a `gh-pages` branch)
3. In repo **Settings → Pages**, set source to **Deploy from a branch**
4. Branch: `main` (or `gh-pages`), folder: `/ (root)`
5. Your site will be at `https://username.github.io/thelastsiege/` (or repo name)
6. URLs: `https://username.github.io/thelastsiege/terms.html`, `.../privacy.html`, `.../account-deletion.html`

### Option C: Use `docs` folder in this project

1. Copy these files into a `docs` folder in your BNB/docs repo
2. In repo **Settings → Pages**, set source to **Deploy from a branch**
3. Branch: `main`, folder: `/docs`
4. URLs will be `https://username.github.io/repo-name/terms.html`, etc.

## URLs to use after deployment

Once live, update:

- **Unity Player Accounts (UGS):** Terms URL, Privacy Policy URL
- **Google Play Console:** Terms, Privacy, Account Deletion URL
- **App Store Connect:** Terms, Privacy, Account Deletion URL (if account creation)
- **In-app:** `LegalUrls.cs` base URL (if you add "View online" links)

Example base URL: `https://username.github.io/thelastsiege`
