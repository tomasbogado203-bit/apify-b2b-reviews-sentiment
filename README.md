# G2, Trustpilot & Capterra B2B Software Reviews & Sentiment Scraper

Extract customer reviews, user complaints, pros, cons, star ratings, and competitor sentiment across **G2**, **Trustpilot**, and **Capterra** for SaaS products, AI tools, and enterprise software.

## 🚀 Features

- **Multi-Platform Scraping:** G2, Trustpilot, Capterra in one unified workflow.
- **Sentiment Classification:** Automatic tagging of Positive, Neutral, and Negative customer sentiment.
- **Competitor Intelligence:** Uncover what users hate or love about competitor tools.
- **Export Options:** Download results in **Excel (XLSX)**, **CSV**, and **JSON**.

## 📥 Input Example

```json
{
  "softwareList": [
    "Notion",
    "HubSpot CRM",
    "Shopify",
    "Zapier"
  ],
  "maxReviewsPerSoftware": 50
}
```

## 📤 Output Format

Each record in the dataset includes:
- `softwareName`: Software product name
- `reviewTitle`: Review headline
- `rating`: Star rating (e.g. 4.5 / 5.0)
- `sentiment`: Positive / Neutral / Negative tag
- `sourcePlatform`: G2, Trustpilot, or Capterra
- `reviewerRole`: Verified business user
- `reviewText`: Full review summary, pros, and cons
- `reviewUrl`: Direct link to verified review
