# n8n Website Scraper Automation

An advanced end-to-end website scraping and content aggregation workflow built using n8n.

This automation scrapes an entire website, extracts all internal page URLs, loops through every page, cleans the extracted content, aggregates the results, and automatically saves the final structured data into Google Docs.

Perfect for:
- AI Knowledge Bases
- RAG Pipelines
- LLM Training Data
- SEO Research
- Documentation Extraction
- Competitor Analysis
- Content Aggregation

---

# 📌 Features

✅ Scrapes complete websites automatically  
✅ Extracts all internal/subpage URLs  
✅ Iterates through every discovered page  
✅ Cleans and structures extracted content  
✅ Removes unnecessary HTML/noise  
✅ Aggregates all page content into one dataset  
✅ Exports final cleaned data to Google Docs  
✅ Fully automated workflow in n8n  

---

# 🛠️ Tech Stack

- n8n
- HTTP Request Node
- JavaScript Code Nodes
- Google Docs Integration
- Workflow Automation
- Web Scraping

---

# ⚙️ Workflow Overview

The workflow follows this pipeline:

```text
Start Workflow
      ↓
Fetch Homepage
      ↓
Extract All Page URLs
      ↓
Loop Over Pages
      ↓
Fetch Each Page
      ↓
Clean & Extract Content
      ↓
Aggregate All Pages
      ↓
Final Merge & Report
      ↓
Save to Google Docs
```

# 📂 Repository Structure

```text
n8n-website-scraper/
│
├── workflow.json
├── README.md
├── screenshots/
│   └── workflow.png
├── demo/
│   └── demo-video.mp4
└── docs/
    └── setup-guide.md
```

---

# 📥 Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Ali-Zia3500/n8n-web-scraping-automation.git
```

---

## 2️⃣ Import Workflow into n8n

1. Open n8n
2. Click:
   - Workflows
   - Import from File
3. Select:

```text
workflow.json
```

---

## 3️⃣ Configure Credentials

You may need to configure:

- Google Docs Credentials
- Google Drive Credentials
- HTTP Request Permissions

---

# 🔑 Required Credentials

| Service | Required |
|---|---|
| Google Docs API | Yes |
| Google Drive API | Optional |
| HTTP Requests | Yes |

---

# 🚀 How It Works

## Step 1 — Fetch Homepage

The workflow starts by fetching the homepage HTML of the target website.

---

## Step 2 — Extract Internal URLs

A JavaScript extraction node parses the HTML and collects all internal links/subpages.

---

## Step 3 — Loop Through Pages

The workflow iterates through every discovered page URL automatically.

---

## Step 4 — Fetch Each Page

Each page is requested using HTTP Request nodes.

---

## Step 5 — Clean Extracted Data

The content is cleaned by:
- Removing HTML tags
- Removing scripts/styles
- Cleaning unnecessary whitespace
- Extracting readable text

---

## Step 6 — Aggregate Content

All cleaned content is merged into a single structured dataset.

---

## Step 7 — Export to Google Docs

The final cleaned output is automatically saved into Google Docs.

---

# 💡 Use Cases

## 🔹 AI & LLM Pipelines
Create datasets for:
- RAG systems
- AI chatbots
- Knowledge bases

---

## 🔹 SEO Research
Extract and analyze:
- Website structure
- Page content
- Metadata

---

## 🔹 Documentation Collection
Automatically scrape documentation websites and centralize data.

---

## 🔹 Competitor Analysis
Collect and analyze public website information.

---

# 📌 Example Output

```text
Page Title: About Us

Content:
We are an AI automation company focused on workflow development...
```

---

# 🔒 Security Notes

Before sharing/exporting workflow:

✅ Remove:
- API Keys
- OAuth Tokens
- Credentials
- Sensitive URLs

n8n usually excludes credentials automatically, but always verify manually.

---

# 📈 Future Improvements

Planned enhancements:

- PDF Export
- Database Storage
- Vector Database Integration
- Embeddings
- LangChain Integration
- Automatic Summarization
- Duplicate Detection
- Sitemap Parsing
- Multi-threaded Scraping

---

# 🤝 Contributions

Contributions are welcome.

Feel free to:
- Fork the repository
- Create pull requests
- Suggest improvements
- Report issues

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

Ali Zia

LinkedIn:
https://pk.linkedin.com/in/ali-zia-3500-ai

GitHub:
https://github.com/Ali-Zia3500

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🔁 Share it on LinkedIn  
🤝 Connect with me  

---
