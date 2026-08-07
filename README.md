# kejal-ranka.github.io

Personal portfolio — Senior Analytics & ML Engineer.

## Structure

```
├── index.html                              ← Homepage (intro + case study links + skills)
├── assets/
│   └── Kejal_Ranka_Resume.pdf              ← Downloadable resume
└── projects/
    ├── professional/                        ← Work case studies (sanitized)
    │   ├── nlp-pipeline.html               ← Self-Improving NLP Classification Pipeline
    │   ├── architecture-redesign.html      ← Monolith → Modular ETL Redesign
    │   └── bias-discovery.html             ← The $5M Bug Nobody Knew Existed
    └── personal/                            ← Personal projects & competitions (add later)
        └── (coming soon)
```

## Deploy

1. Create repo `kejal-ranka.github.io` on GitHub
2. ```bash
   cd ~/Documents/Personal/portfolio
   git remote add origin https://github.com/kejal-ranka/kejal-ranka.github.io.git
   git push -u origin main
   ```
3. Settings → Pages → Source: `main` branch
4. Live at: https://kejal-ranka.github.io

## Adding Personal Projects Later

Drop new `.html` files in `projects/personal/` and add a card to the homepage.
The "Coming soon" placeholder on the homepage will be replaced.

## Resume

Convert .docx to PDF and replace `assets/Kejal_Ranka_Resume.pdf`.
