# 🚀 How to Publish This Portfolio on GitHub

Follow these steps to get your portfolio live at `https://yourusername.github.io/qa-portfolio`

---

## Step 1: Create a GitHub Account

If you don't have one: https://github.com/signup

Pick a professional username (e.g. your name or initials).

---

## Step 2: Create a New Repository

1. Click the **+** icon (top right) → **New repository**
2. Repository name: `qa-portfolio`
3. Set to **Public**
4. Do NOT check "Add a README" (we already have one)
5. Click **Create repository**

---

## Step 3: Upload the Files

**Option A — GitHub Web Upload (Easiest, No Git Required):**

1. On your new empty repo page, click **"uploading an existing file"**
2. Upload ALL files from the `qa-portfolio` folder
3. For files inside `docs/` folders, you'll need to upload maintaining the folder structure:
   - Click "Add file" → "Upload files"
   - Drag and drop entire folders, or upload file by file

**Upload order:**
- `index.html`
- `README.md`
- `docs/test-plans/TP-001-ecommerce-checkout-test-plan.md`
- `docs/test-plans/TP-002-mobile-app-regression-test-plan.md`
- `docs/test-cases/TC-001-user-authentication.md`
- `docs/test-cases/TC-002-shopping-cart-functionality.md`
- `docs/test-cases/TC-003-responsive-layout-cross-browser.md`
- `docs/test-cases/TC-004-mobile-app-onboarding.md`
- `docs/bug-reports/BUG-001-checkout-total-miscalculation.md`
- `docs/bug-reports/BUG-002-005-reports.md`

4. Write a commit message: `Initial portfolio upload`
5. Click **Commit changes**

---

## Step 4: Enable GitHub Pages (Makes the website live)

1. Go to your repo → **Settings** tab
2. Scroll down to **Pages** (left sidebar)
3. Under "Source" → select **Deploy from a branch**
4. Branch: `main`, Folder: `/ (root)`
5. Click **Save**

⏳ Wait 1–2 minutes, then your site is live at:
`https://yourusername.github.io/qa-portfolio`

---

## Step 5: Personalize Before Sharing

Open these files and replace placeholder text:

**In `README.md`:**
- Replace `your.email@example.com` with your real email
- Replace `linkedin.com/in/yourprofile` with your LinkedIn URL
- Replace `yourusername` in the GitHub Pages URL

**In `index.html`:**
- Line with `href="mailto:your.email@example.com"` — update email

---

## Step 6: Share the Link

When applying for the job, share:
- **GitHub repo:** `https://github.com/yourusername/qa-portfolio`
- **Live portfolio site:** `https://yourusername.github.io/qa-portfolio`

Both show professional QA work!

---

## Tips

- The live website (`index.html`) is what makes the best first impression — share that link first
- The markdown files (bug reports, test cases) show your detailed documentation skills
- You can keep updating and adding more bug reports over time as you do more testing
