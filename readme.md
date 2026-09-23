# Children's Hope Junior School – Official Website

Pure static website for **Children's Hope Junior School**, Namukooge, Kaliro District, Uganda.

## Project Structure

```
childrens-hope-school/
├── index.html          ← Main page
├── css/
│   └── style.css       ← All styles
├── js/
│   └── script.js       ← All interactive logic (menu, form, assessment, PDF)
├── images/
│   ├── logo.png
│   ├── director1.jpg
│   ├── director2.jpg
│   ├── gallery1.jpg … gallery5.jpg
└── README.md
```

## Features

- Fully responsive (mobile, tablet, desktop)
- Online admission application with Formspree
- Placement assessment for Primary 1–7 (20 random questions, 40% pass mark)
- Automatic application number generation (localStorage)
- Downloadable PDF admission form (jsPDF)
- Image lightbox gallery
- WhatsApp & phone integration
- Back-to-top button

## How the Admission Flow Works

1. Parent fills parent + child details.
2. Selects class.
   - Baby / Middle / Top Class → no assessment, Submit button appears.
   - Primary 1–7 → assessment appears (20 questions).
3. Must score ≥ 40% to proceed with the chosen class.
   - Below 40% → recommended to go one class lower + options to discuss with directors.
4. On successful submit → Formspree receives the data + application number is shown + PDF download becomes available.

## Publishing Options

### 1. GitHub Pages (Free & Easy)

1. Create a free GitHub account.
2. Create a new repository (e.g. `childrens-hope-school`).
3. Upload the entire folder contents (or push via Git).
4. Go to **Settings → Pages → Source: Deploy from a branch → main / root**.
5. Your site will be live at:  
   `https://YOUR-USERNAME.github.io/childrens-hope-school/`

### 2. Netlify (Recommended – Free, Custom Domain Support)

1. Go to [netlify.com](https://www.netlify.com) and sign up.
2. Drag & drop the whole `childrens-hope-school` folder onto the Netlify dashboard.
3. Instant live URL + free HTTPS.
4. Optional: connect a custom domain (e.g. `www.childrenshopejuniorschool.ug`).

### 3. Vercel

Same as Netlify – drag & drop or connect a Git repo at [vercel.com](https://vercel.com).

### 4. Traditional Hosting (cPanel / Hostinger / etc.)

1. Zip the entire folder.
2. Upload via File Manager or FTP.
3. Extract into `public_html` (or the domain root).
4. Ensure `index.html` is in the root.

### 5. Local Testing

Simply open `index.html` in any modern browser (Chrome, Firefox, Edge).  
Note: Formspree submissions and some localStorage features work best when served over HTTP (use Live Server in VS Code or similar).

## Formspree Setup

The form currently points to:  
`https://formspree.io/f/mvkggoby`

- Log into Formspree and confirm the form is active.
- You will receive email notifications for every application.
- You can change the form ID in `index.html` if you create a new form.

## Custom Domain (Optional)

After publishing on Netlify/Vercel/GitHub Pages:

1. Buy a domain (e.g. from Namecheap, GoDaddy, or .ug registrar).
2. Point the DNS (A / CNAME records) to the hosting provider’s instructions.
3. Enable HTTPS (automatic on Netlify/Vercel).

## Credits

- School: Children's Hope Junior School, Namukooge, Kaliro District, Uganda
- Directors: Mr. Lazarus Semujju & Mr. Moses Kusemererwa
- Built as a pure static website (HTML + CSS + Vanilla JS)

---

**Ready to publish.** Just upload the folder to any of the services above.
