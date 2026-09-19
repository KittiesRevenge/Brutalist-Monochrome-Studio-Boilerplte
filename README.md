# Arcana Writing Studio

## Project: The Soul Tie that never was

This is a therapeutic sanctuary for processing trauma, rejection, and reclaiming self-worth through the power of writing. 

### Current Projects:
- **The Soul Tie that never was**: A memoir exploring unrequited cosmic connections.
- **War Letters**: A collection of historical correspondence (In Progress).

Built with the **Arcana Writing Studio** framework.
# Brutalist Monochrome Studio — Full Codebase & App Boilerplate 🖤

> **A stark, local-first web application template and manuscript archive built specifically for authors, memoirists, researchers, and creators seeking a distraction-free writing sanctuary.**

---

## 📌 Overview

The **Brutalist Monochrome Studio** is a minimalist, high-aesthetic web application designed to help creators process heavy narrative data, raw journal archives, scanned letters, and long-form manuscript drafts. 

Built with a local-first philosophy, this application keeps sensitive creative work secure on your local machine or private GitHub repository—freeing you from bloated SaaS subscriptions, privacy risks, and cluttered cloud interfaces.

---

## ✨ Key Features & Technical Capabilities

* **Stark "Brutalist Monochrome" UI:** High-contrast, dark-mode design engineered specifically to eliminate eye strain and maximize deep creative focus[cite: 5].
* **Dual-Pane Manuscript Comparison:** Integrated split-screen workspace to analyze raw source fragments (letters, journal entries, scanned notes) directly alongside active drafts[cite: 5].
* **Local-First Privacy Architecture:** Complete data ownership—your private text and manuscript entries remain stored locally or within your secured repository[cite: 5].
* **Structured Data Pipelines (`JSON` & `Markdown`):** Clean separation of UI styling and source data schema (`manuscript_data.json`), allowing seamless content updates without breaking application code[cite: 5].
* **OCR & Letter Archiving Pipeline:** Designed for easy integration with image-to-text translation tools and redaction filters to manage physical letter archives securely.
* **Zero Host Lock-In:** Free host compatibility—deploy in under 5 minutes to Vercel, Netlify, or GitHub Pages[cite: 5].

---

## 🛠️ Technical Specifications & Tech Stack

| Component | Technology / Specification |
| :--- | :--- |
| **Frontend Framework** | React / Next.js (App Router compatible)[cite: 5] |
| **Styling Engine** | Tailwind CSS / Brutalist CSS Layouts[cite: 5] |
| **Data Schema** | Local JSON Mapping & Markdown Files[cite: 5] |
| **Deployment Targets** | Vercel, Netlify, GitHub Pages, or Local Runtime[cite: 5] |
| **Environment Security** | Configured `.gitignore` and `.env.local` support[cite: 5] |

---

## 📁 Repository Structure

```text
├── manuscript/             # Raw Markdown chapter files & text archives
├── data/
│   └── manuscript_data.json # Structured JSON data for timeline & letter entries
├── components/             # Reusable Brutalist UI elements & dual-pane layout
├── public/                 # Static branding & visual asset placeholders
├── .env.example            # Environment variable template for API keys
└── .gitignore              # Pre-configured security filters for private keys & data
