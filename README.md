# Quarterly Earnings Report - RevealJS Presentation

A professional interactive presentation created with RevealJS for financial stakeholders.

## Features Included

✅ **Email**: 24f1002416@ds.study.iitm.ac.in displayed in presentation
✅ **Markdown Slide**: Executive Summary written in Markdown
✅ **Animated Fragments**: Multiple slides with fade-in and highlight animations
✅ **Code Samples**: Python and JavaScript code with syntax highlighting
✅ **Mathematical Equations**: Financial formulas (ROE, EPS, P/E ratio) using KaTeX
✅ **Speaker Notes**: Each slide includes presentation guidance notes

## Local Testing

To view the presentation locally:

1. Open `index.html` in a web browser
2. Use arrow keys or space bar to navigate
3. Press 'S' to open speaker notes view
4. Press 'F' for fullscreen mode
5. Press 'ESC' for overview mode

## Publishing to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the '+' icon → 'New repository'
3. Name your repository (e.g., `earnings-report` or `Week8GA_TDS`)
4. Make it **Public**
5. DO NOT initialize with README (we already have files)
6. Click 'Create repository'

### Step 2: Push Your Code to GitHub

Open your terminal/command prompt in this directory and run:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Add RevealJS quarterly earnings presentation"

# Add your GitHub repository as remote (replace USERNAME and REPO with your values)
git remote add origin https://github.com/USERNAME/REPO.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on 'Settings' tab
3. Scroll down to 'Pages' in the left sidebar
4. Under 'Source', select 'Deploy from a branch'
5. Under 'Branch', select 'main' and '/root' folder
6. Click 'Save'
7. Wait 1-2 minutes for deployment

### Step 4: Access Your Presentation

Your presentation will be available at:
```
https://USERNAME.github.io/REPO/
```

Replace `USERNAME` with your GitHub username and `REPO` with your repository name.

## Presentation Navigation

- **Next Slide**: Arrow Right, Space, or N
- **Previous Slide**: Arrow Left or P
- **Speaker Notes**: Press S
- **Overview Mode**: Press ESC
- **Fullscreen**: Press F
- **Help**: Press ?

## Slide Structure

1. **Title Slide** - Introduction with email
2. **Executive Summary** - Markdown formatted content
3. **Key Financial Metrics** - Animated fragments
4. **Financial Formulas** - Mathematical equations
5. **Revenue Analysis** - Python code with syntax highlighting
6. **Portfolio Optimization** - JavaScript code sample
7. **Future Initiatives** - Animated strategic roadmap
8. **Thank You** - Closing slide

## Technologies Used

- RevealJS 4.5.0
- KaTeX for mathematical rendering
- Highlight.js for code syntax highlighting
- Markdown plugin for content formatting

## Contact

24f1002416@ds.study.iitm.ac.in
