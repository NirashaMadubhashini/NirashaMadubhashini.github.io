# 📎 Notes — GitHub Pages Site

## How to Upload to GitHub Pages

### Step 1: Create Repository
1. Go to https://github.com → Click **"New"**
2. Name it: `yourusername.github.io` (replace with your actual GitHub username)
3. Set to **Public**
4. Click **Create repository**

### Step 2: Upload Files
1. In your new repo, click **"Add file" → "Upload files"**
2. Upload ALL these files and folders:
   ```
   index.html
   sem1/
   sem2/
   sem3/
   sem4/
   ```
3. Click **"Commit changes"**

### Step 3: Enable GitHub Pages
1. Go to **Settings → Pages**
2. Under "Branch", select **main** and **/ (root)**
3. Click **Save**
4. Wait 1-2 minutes → Your site is live at `https://yourusername.github.io`

---

## Customizing Your Notes

### Add your subject names
Open each `semX/index.html` and edit the subject cards:
```html
<a href="#" class="subject-card">
  <div class="subject-icon">🧮</div>
  <div>
    <div class="subject-name">Mathematics I</div>
    <div class="subject-meta">Calculus · Algebra</div>
  </div>
</a>
```

### Link to a PDF or Google Drive
Change `href="#"` to your link:
```html
<a href="https://drive.google.com/your-link" class="subject-card">
```

### Add more subjects
Copy and paste more `<a href... class="subject-card">` blocks in the grid.

---

## File Structure
```
yourusername.github.io/
├── index.html        ← Home page (semester selector)
├── sem1/
│   └── index.html   ← Semester 1 subjects
├── sem2/
│   └── index.html   ← Semester 2 subjects
├── sem3/
│   └── index.html   ← Semester 3 subjects
└── sem4/
    └── index.html   ← Semester 4 subjects
```
