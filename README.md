# Network & Cloud Engineer Portfolio

A professional portfolio website showcasing network engineering, cloud architecture, and data science projects with AI/ML focus.

## 🚀 Your Portfolio is Ready!

This portfolio has been customized with:
- ✅ Your professional background (5+ years at Visa, ThreatConnect)
- ✅ Four featured projects with real metrics
- ✅ Complete case study for Contract Gap Analysis project
- ✅ Skills organized into Network/Cloud, Data Science/AI, and Security
- ✅ Certifications section (AWS AI Practitioner, CCNA, upcoming certs)

## Quick Setup (5 minutes)

### Option 1: GitHub Pages (Recommended - Free & Easy)

1. **Create a GitHub account** (if you don't have one)
   - Go to https://github.com/join

2. **Create a new repository**
   - Click the `+` icon in the top right → "New repository"
   - Name it: `username.github.io` (replace `username` with your actual GitHub username)
   - Make it Public
   - Click "Create repository"

3. **Upload these files**
   - Click "uploading an existing file"
   - Drag and drop these 3 files:
     - `index.html`
     - `style.css`
     - `script.js`
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Under "Source", select "main" branch
   - Click Save
   - Your site will be live at `https://username.github.io` in 1-2 minutes!

### Option 2: Using Git (If you're comfortable with command line)

```bash
# 1. Create a new repository on GitHub named username.github.io

# 2. In your terminal, navigate to this folder and run:
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main

# 3. Enable GitHub Pages in repository settings
```

## Customization Guide

### Priority Updates (Do These First!)

**1. Add Your Contact Information (index.html)**
- Line 220-222: Replace `your.email@example.com` with your actual email
- Lines 39-41 & 224-230: Update GitHub and LinkedIn URLs

**2. Update Project GitHub Links (index.html)**
Replace the placeholder GitHub URLs with your actual repositories:
- Contract Gap Analysis: Line ~90
- Jira Triage Automation: Line ~120
- AWS Asset Database: Line ~150
- Network Threat Detection: Line ~180

**3. Add Your Name/Branding**
Currently uses "Portfolio" as the logo. You can replace with your initials or full name:
- index.html Line 16
- contract-gap-analysis-case-study.html Line 93

### Optional Enhancements

**Add More Projects**
The template shows 4 projects. Based on your resume, you could add:
- **Integrated Compliance Library Database** (AWS Textract/Comprehend + TensorFlow)
- **Network Automation via Netbrain AI & Chatbot APIs** 
- **NHS Tutoring Portal** (SQL database + Node.js backend)

Copy a project card in index.html (lines ~85-105) and customize.

**Add a Resume Download**
Add this to your hero section (around line 42):
```html
<a href="resume.pdf" class="btn btn-secondary" download>Download Resume</a>
```

**Google Analytics** (Track Visitors)
See instructions at bottom of this README.

## File Structure

```
portfolio-website/
├── index.html                              # Main landing page
├── contract-gap-analysis-case-study.html  # Detailed case study
├── style.css                               # All styling
├── script.js                               # Smooth scrolling & animations
└── README.md                               # This file
```

## What's Included

## What's Included

### Main Portfolio (index.html)
- **Hero Section**: Network/Cloud Engineer title with your background
- **About Section**: 5+ years experience, current role, education
- **Skills Grid**: 
  - Network & Cloud (Cisco, AWS, Terraform)
  - Data Science & AI (Python, LLMs, TensorFlow)
  - Security & Operations (Wireshark, Splunk, PKI)
- **Certifications**: AWS AI Practitioner, CCNA, upcoming Security+ and AWS Data Engineer
- **4 Featured Projects**:
  1. Contract Gap Analysis (with detailed case study)
  2. Jira Triage Automation
  3. AWS Asset Database
  4. Network Threat Detection

### Case Study Page
- Full technical deep dive on the Contract Gap Analysis project
- Problem statement, solution architecture, results
- Prompt engineering strategy, RAG implementation details
- Challenges, learnings, and what you'd do differently
- Professional layout that tells the story of your ML work

### Design Features
- Dark theme optimized for technical roles
- Distinctive typography (Playfair Display + JetBrains Mono)
- Smooth scroll animations and hover effects
- Fully responsive (mobile, tablet, desktop)
- Professional metrics displays

## Next Steps After Going Live

1. **Update Your Resume**: Add the portfolio URL
2. **LinkedIn**: Add to Featured section and contact info
3. **GitHub Profile**: Add to pinned repositories
4. **Create Project READMEs**: Make sure each GitHub repo has:
   - Clear description of what it does
   - Setup/installation instructions  
   - Screenshots or demos
   - Technologies used
   - Results/metrics
5. **Build Case Studies**: Create similar pages for your other major projects
6. **Blog Posts** (Optional): Write about technical challenges you solved

## Tips for Standing Out

Based on your background at Visa and ThreatConnect:

1. **Quantify Everything**: "Reduced triage time from 3-4 hours to <1 hour" is more powerful than "improved efficiency"
2. **Show Production Systems**: Emphasize that you worked on systems handling billions of transactions
3. **Highlight Security Focus**: Your PKI, TLS/SSL, and Zero Trust work is valuable—make it visible
4. **Deploy Something**: Even a simple Streamlit demo of your ML models shows you can ship
5. **Write About Your Work**: Technical blog posts on Medium/Dev.to boost credibility

## Career-Specific Advice

For Network/Cloud + ML roles:

**Target Companies:**
- Cloud providers (AWS, GCP, Azure) - Infrastructure + ML teams
- Cybersecurity (Palo Alto, CrowdStrike, Datadog) - Data-driven security
- Fintech (Stripe, Square, Plaid) - Need both network expertise and ML
- Network vendors (Cisco, Juniper) - Network automation & AI teams

**Resume Positioning:**
- Lead with "Network/Cloud Engineer with Data Science expertise" (not just one or the other)
- Emphasize the unique combination of infrastructure AND AI skills
- Highlight your ability to apply ML to network/security problems (rare skillset!)

**For Applications:**
- Customize your project descriptions based on the role (emphasize network automation for infrastructure roles, ML aspects for data roles)
- Use this portfolio to show you can code, architect systems, AND communicate technical work
- Line 7: Change page title
- Line 16: Change initials in logo (`YN` → your initials)
- Lines 26-27: Update links to your GitHub and LinkedIn
- Lines 34-36: Customize hero title
- Line 37: Update subtitle
- Lines 39-40: Add your actual profile links
- Lines 46-53: Write your about section
- Lines 72-197: Replace project cards with your actual projects
- Line 207: Update email and contact info

**Important links to update:**
- GitHub URL: Replace `yourusername` with your GitHub username
- LinkedIn URL: Replace `yourprofile` with your LinkedIn profile name
- Email: Replace with your actual email

### 2. Add Your Projects

Each project card needs:
- **Project name**: Clear, descriptive title
- **Tags**: Technologies used (PyTorch, NLP, FastAPI, etc.)
- **Description**: 2-3 sentences about what it does and why it matters
- **Metrics**: Quantifiable results (accuracy, speed, improvement)
- **Links**: GitHub repo link and optionally a live demo or case study

**Where to link:**
- Main GitHub repo: Shows your code
- Case study: Can be a detailed README, blog post, or separate page
- Live demo: Link to deployed Streamlit app, API, or notebook

### 3. Style Customization

**Colors** (in `style.css` lines 1-6):
```css
--color-accent: #00d9ff;  /* Change to your preferred accent color */
```

**Fonts**: Current setup uses:
- Display headings: Playfair Display (elegant serif)
- Body text: JetBrains Mono (code-style monospace)

To change fonts, replace line 9-10 in `index.html` with fonts from [Google Fonts](https://fonts.google.com/)

## Adding More Sections

### Blog/Writing Section
Add between projects and contact:
```html
<section id="blog" class="section">
    <div class="container">
        <h2 class="section-title">Writing</h2>
        <!-- Add blog post cards here -->
    </div>
</section>
```

### Case Study Pages
Create separate HTML files like `project1-case-study.html` and link from your project cards.

## Tips for Success

1. **Keep it updated**: Add new projects as you complete them
2. **Show real results**: Include metrics, demos, or deployed links whenever possible
3. **Clean GitHub repos**: Make sure your project READMEs are clear and code is well-commented
4. **Mobile-friendly**: This template is responsive, test on your phone
5. **Analytics**: Add Google Analytics to track visitors (optional)

## Adding Google Analytics (Optional)

1. Create a Google Analytics account
2. Get your tracking ID
3. Add this before `</head>` in index.html:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-ID');
</script>
```

## Troubleshooting

**Site not showing up?**
- Wait 2-3 minutes after enabling GitHub Pages
- Check Settings → Pages shows a green success message
- Make sure repository name is exactly `username.github.io`

**Fonts not loading?**
- Check your internet connection
- Fonts load from Google Fonts CDN

**Need help?**
- GitHub Pages documentation: https://docs.github.com/en/pages
- Create an issue in this repo

## Next Steps

After your site is live:
1. Share the link on your LinkedIn
2. Add it to your resume
3. Link to it from your GitHub profile README
4. Consider writing blog posts about your projects
5. Add project video demos to really stand out

---

Built with HTML, CSS, and vanilla JavaScript. No frameworks, no build process, just simple and effective.
