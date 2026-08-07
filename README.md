# kejal-ranka.github.io

Personal portfolio website — Senior Analytics & ML Engineer.

## Deploy to GitHub Pages

1. Create a repo named `kejal-ranka.github.io` on GitHub
2. Push this code:
   ```bash
   git remote add origin https://github.com/kejal-ranka/kejal-ranka.github.io.git
   git push -u origin main
   ```
3. Go to repo Settings → Pages → Source: Deploy from branch → `main` / `/ (root)`
4. Site will be live at: https://kejal-ranka.github.io

## Structure

```
├── index.html                  ← Main portfolio page
├── assets/
│   └── Kejal_Ranka_Resume.pdf  ← Downloadable resume (replace placeholder with actual PDF)
└── projects/
    ├── nlp-pipeline.html       ← Voice of Customer NLP Platform
    ├── ranking-engine.html     ← Entity Ranking & Recommendation Engine
    ├── architecture.html       ← ETL Architecture Modernization
    ├── bias-detection.html     ← Statistical Bias Discovery
    └── sustainability.html     ← AI-Enhanced Emissions Analytics (VIZCON)
```

## To Update

- Edit HTML files directly
- Commit and push — GitHub Pages auto-deploys

## Resume PDF

Convert the .docx to PDF and replace `assets/Kejal_Ranka_Resume.pdf`:
- Open `.docx` in Word → File → Export as PDF
- Or: `libreoffice --headless --convert-to pdf Kejal_Ranka_Resume_Senior_BIE.docx`
