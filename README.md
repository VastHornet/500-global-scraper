[500 Global Scraper](https://apify.com/fatihtahta/500-global-scraper?fpr=data)

# 500 Global Scraper | Fast & Reliable | $5 / 1k

**Slug:** `fatihtahta/500-global-scraper`

**Price:** **$5.00 per 1,000 saved companies**

Pull structured company intelligence straight from the 500 Global portfolio. Point this actor at any portfolio view on [500.co](https://500.co/portfolio), set your preferred limits, and receive ready-to-use records that include founder details, investment history, hiring signals, and optional professional emails.

📩 This actor is built upon the [ValidatedMails.com](https://validatedmails.com) architecture for email enrichment workflows.

---

## 🚀 What You Get

- **Filter-aware portfolio coverage** — Scrape companies by tenant, region, industry, stage, or any combination of filters you configure on 500.co.
- **Complete company snapshots** — Company names, descriptions, locations, batch participation, investment counts, and hiring indicators all included.
- **Founder context & contactability** — Each record includes the founders tracked by 500 Global; toggle email enrichment when available.
- **Dataset-ready deduped output** — Export JSON, CSV, Excel, or HTML from Apify without any manual cleanup.
- **Scalable & dependable** — Designed for large pulls across the global portfolio while staying responsive for small, targeted jobs.

---

## 🧠 Ideal Use Cases

- **Deal sourcing** – Build shortlists of startups that match your thesis, region, or batch interest.
- **Competitive scouting** – Compare industries, stages, and hiring signals across cohorts.
- **Founder outreach** – Enrich and prioritise with contact-ready founder details.
- **Market mapping** – Analyse the breadth of 500 Global investments for research and reporting.

---

## 📥 Input Configuration

Open the **Input** tab and provide the settings that fit your search. Key fields include:

- `startUrls` *(string | array)* — One or more 500 Global portfolio URLs with your desired filters applied.
- `maxCompanies` *(number, default `5000`)* — Upper limit for saved companies.
- `enrichWithEmail` *(boolean, default `true`)* — Toggle founder email discovery.
- `includeRiskyEmails` *(boolean, default `false`)* — Include limitly verified results when email enrichment is enabled.
- `proxyConfiguration` *(object)* — Leave the Apify defaults or customise to match your proxy setup.
- 

---

## 🧪 Example Input

```
{
  "startUrls": [
    "https://500.co/portfolio?tenant=global&industry=artificial-intelligence"
  ],
  "maxCompanies": 750,
  "enrichWithEmail": true,
  "includeRiskyEmails": false,
  "proxyConfiguration": {
    "useApifyProxy": true,
    "groups": ["RESIDENTIAL"]
  }
}
```

---

## 📦 Output Fields

Each saved item represents a single portfolio company and typically contains:

- `source` — Original URL and scrape timestamp.
- `identifiers` — 500 Global company IDs.
- `names` — Display, legal, brand, and alternative names.
- `descriptions` — Short and extended company blurbs (when available).
- `media` — Logo or featured image URLs.
- `web` — Website, social profiles, and domain.
- `operations` — Country, regional grouping, and tenant tags.
- `business` — Stage, fundraising status, industries, and business model insights.
- `program` — Batch or accelerator program participation.
- `hiring` — Hiring flag and number of open roles.
- `investments` — Count of known investment events and their dates.
- `founders` — Founder roster with profile links and optional email + status fields.
- `stats` / `legacy` — Aggregated counters and compatibility fields for older workflows.

Export results directly from the **Dataset** tab in your preferred format.

---

## 🛠️ How to Use

1. **Open** the actor: **500 Global Scraper | Fast & Reliable | $4 / 1k**.
2. **Configure** your filters on 500.co and copy the resulting portfolio URL(s) into `startUrls`.
3. **Adjust** the optional limits, concurrency, and email settings as needed.
4. **Run** the actor and monitor progress in real time.
5. **Download** or integrate your dataset once the run completes.

---

## 💰 Pricing

**$4.00 per 1,000 saved companies.**

You are billed only for successfully stored items.

---

## ⚖️ Responsible Use

The dataset surfaces publicly available company and founder information. Depending on your jurisdiction, this may include personal data. Ensure your use complies with applicable privacy laws (e.g., GDPR, CCPA), respect opt-outs, and follow the relevant platform terms when contacting founders.

---

## ❓ Support

Need help, feature tweaks, or a custom dataset? Open an issue on the **Issues** tab of the actor page and it will be resolved around the clock.

Happy Scraping!

— Fatih