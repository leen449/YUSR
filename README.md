# YUSR | يسر

**Make Arabic content accessible. Automatically.**

YUSR is an AI-powered tool that turns Arabic PDFs, Word documents and web pages into accessible content that screen readers can use. It is built for universities, government agencies and organizations that publish Arabic content and need it to meet WCAG accessibility standards.

> 🚧 **Pre-launch:** YUSR is not live yet. This repository contains the MVP landing page and an interactive product demo that use sample data. Join the waitlist on the site to get early access.

🔗 **Live site:** [https://leen449.github.io/YUSR/index.html#home]

---

The problem exists on two levels.

**1. The global accessibility gap.** Most digital documents and webpages fail basic accessibility standards. Images have no alt-text, the reading order is wrong, the structure is poor, and tables aren't tagged, so screen readers and other assistive technologies can't use the content.

**2. The Arabic accessibility gap.** Arabic adds challenges that most tools aren't built for:

- Right-to-left text breaks reading-order logic
- Arabic and English mixed in one document create structural confusion
- Alt-text tools work almost only in English
- Multi-column layouts and complex tables, common in government and academic documents, are rarely fixed correctly

Today, organizations fix these problems by hand across several teams and tools. The process is slow, fragmented and inconsistent.

## The solution

One upload, one accessibility workflow, in four stages:

1. **Upload** a document or a webpage URL
2. **Analyze:** AI detects accessibility issues
3. **Transform:** AI generates fixes
4. **Review:** a person approves every change, then exports

| What YUSR fixes | How |
|---|---|
| Alt-text | Generates descriptions for images and figures, including native Arabic alt-text |
| Reading order | Corrects RTL and mixed-language reading sequences |
| Tables | Tags headers and cells so tables read correctly |
| Document structure | Produces properly tagged, accessible PDFs with smooth Arabic–English flow |
| Simpler text | Simplifies content where appropriate |

### Why YUSR is different

- **Arabic-first, fully bilingual.** Arabic isn't an add-on language option.
- **Fixes problems, not just flags them.** It goes beyond detection to generate the corrected content.
- **One platform** for text, images, tables, PDFs and webpages, instead of separate tools.
- **Human review built in.** Nothing changes without approval, which matters for government and compliance work.

### Who it's for

A B2B platform for organizations that publish content at scale: universities and education, government, corporates, digital content and media, and financial services.


---

## What's in this repo

### 1. Landing page (`index.html`)

- Value proposition and "coming soon" messaging
- Feature overview and pricing plans with a monthly/annual toggle
- Embedded explainer video
- Call to action: a waitlist and demo-request form
- Full **English / Arabic** toggle with right-to-left layout

### 2. Interactive demo (`demo.html`)

A walkthrough of the product flow using sample results:

1. **Upload:** drop a file or choose one of three sample documents
2. **Scan:** view an accessibility score and a breakdown of issues by type
3. **Review:** accept, edit or reject each AI-generated fix, individually or in bulk
4. **Export:** compare the score before and after, then download the accessible version

> No files are uploaded or processed. The demo runs entirely in the browser with sample data.

---

## Built with

- HTML, CSS and vanilla JavaScript, with no frameworks or build step
- Google Fonts: DM Sans, EB Garamond, IBM Plex Sans Arabic, Noto Naskh Arabic
- Figma for the original design

The site follows the accessibility practices it promotes: semantic HTML, keyboard navigation with visible focus, `lang`/`dir` switching for Arabic, reduced-motion support, and light/dark themes.

## Project structure

```
YUSR/
├── index.html        # Landing page
├── demo.html         # Interactive product demo
└── images/           # Logo and photos
```

## Run locally

No installation needed. Download or clone the repo and open `index.html` in a browser:

```bash
git clone https://github.com/leen449/YUSR.git
```

---

## About

Developed as the Minimum Viable Product (Milestone 2) for **IT427: Entrepreneurship and Innovation in IT**, King Saud University.

**Team:** 
- Shahad Alotaibi
- Aryam Almutairi
- Leen binmuayqil
-  Nora Alkhudair
-  Shooq Alawdah
-  Noora Alasmeri


© 2026 YUSR. All rights reserved.
