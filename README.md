I'm# 🔐 CYBER_DOCS - Cybersecurity Documentation Website

A stylish, hacker-themed documentation website for your cybersecurity assignments and research. Built with HTML, CSS, and vanilla JavaScript - ready to deploy on Vercel!

## 🎨 Features

- **Hacker-Style Terminal Aesthetic**: Matrix-inspired green-on-black color scheme with glowing effects
- **Scanline & CRT Effects**: Authentic retro terminal feel
- **Responsive Design**: Works perfectly on desktop and mobile
- **Easy to Update**: Simple HTML structure - just add new assignment files!
- **Smooth Animations**: Glitch effects, hover states, and transitions
- **Production-Ready**: Optimized and clean code

## 📁 Project Structure

```
your-repo/
├── index.html              # Main landing page
├── style.css               # All styling and animations
├── docs/
│   ├── assignment1.html    # Example assignment (Network Penetration Testing)
│   ├── assignment2.html    # Add your assignments here!
│   └── assignment3.html    # Add more as needed
└── README.md              # This file
```

## 🚀 Deployment Guide (Step-by-Step for 5-Year-Olds!)

### Step 1: Upload Your Files to GitHub

1. **Go to your GitHub repository** (the one you already created!)
2. **Click "Add file"** → **"Upload files"**
3. **Drag and drop** these files:
   - `index.html`
   - `style.css`
   - `README.md`
4. **Create a folder called `docs`** and upload:
   - `assignment1.html` (the example assignment)
5. **Click "Commit changes"** at the bottom

### Step 2: Connect to Vercel (The Magic Part!)

1. **Go to [vercel.com](https://vercel.com)**
2. **Click "Sign Up"** (or "Login" if you have an account)
3. **Click "Continue with GitHub"** 
   - This gives Vercel permission to see your GitHub repos
4. **Click "Import Project"**
5. **Find your repository** in the list and click "Import"
6. **Click "Deploy"** (leave all settings as default!)

### Step 3: Wait for Magic! ✨

Vercel will build your website (takes about 30 seconds). When done, you'll see:

```
🎉 Congratulations! Your site is live!
https://your-project-name.vercel.app
```

That's your website address! Share it with anyone! 🌐

## 📝 How to Add New Assignments

### Quick Method (Copy & Paste):

1. **Copy** `docs/assignment1.html`
2. **Rename** it to `assignment2.html` (or whatever number you're on)
3. **Edit the content**:
   - Change the title
   - Update the assignment details
   - Add your findings, code snippets, etc.
4. **Save** and **push to GitHub**
5. **Vercel automatically updates** your website! (No need to deploy again!)

### Update the Homepage:

1. **Open** `index.html`
2. **Find** the assignments grid section
3. **Copy** one of the existing `.doc-card` blocks
4. **Paste** it and update:
   - Assignment ID (e.g., `ASSIGNMENT_002`)
   - Title
   - Description
   - Date
   - Link to your new file

Example:
```html
<div class="doc-card">
    <div class="card-header">
        <span class="card-id">ASSIGNMENT_002</span>
        <span class="card-status active">ACTIVE</span>
    </div>
    <h3 class="card-title">Your Assignment Title</h3>
    <p class="card-desc">Your assignment description here</p>
    <div class="card-meta">
        <span class="meta-item">📅 2024.03.22</span>
        <span class="meta-item">🔒 Severity: HIGH</span>
    </div>
    <a href="docs/assignment2.html" class="card-link">
        <span>ACCESS_FILE</span>
        <span class="arrow">→</span>
    </a>
</div>
```

## 🎨 Customization Tips

### Change Colors:

Open `style.css` and modify these variables at the top:

```css
:root {
    --text-primary: #00ff41;      /* Main green color */
    --text-secondary: #00d9ff;    /* Cyan accent */
    --accent-red: #ff0080;        /* Red for critical items */
}
```

### Change Fonts:

Replace the Google Fonts link in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=YOUR_FONT&display=swap" rel="stylesheet">
```

## 🔧 Auto-Deployment

Every time you push changes to GitHub:
1. Vercel **automatically detects** the changes
2. Vercel **rebuilds** your site
3. Your website **updates** in about 30 seconds!

No manual deployment needed! 🎉

## 📱 Mobile Friendly

Your website automatically adjusts to different screen sizes:
- Desktop: Full grid layout
- Tablet: 2-column grid
- Mobile: Single column

## 🆘 Troubleshooting

**Problem:** My website doesn't update after pushing to GitHub
- **Solution:** Wait 30-60 seconds. Vercel needs time to rebuild.

**Problem:** Images don't show up
- **Solution:** Make sure all image files are uploaded to GitHub

**Problem:** Links are broken
- **Solution:** Check that your file paths are correct (e.g., `docs/assignment1.html`)

**Problem:** CSS isn't working
- **Solution:** Make sure `style.css` is in the same folder as `index.html`

## 🎯 What's Next?

1. **Add your own assignments** using the template
2. **Customize the colors** to match your style
3. **Add more sections** (tools, research, blog posts)
4. **Share your website** with friends and colleagues!

## 📚 Resources

- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Guide](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Vercel Documentation](https://vercel.com/docs)
- [GitHub Help](https://docs.github.com)

---

**Built with ⚡ for cybersecurity research**

Made by N∅eljnrscript 🚀
