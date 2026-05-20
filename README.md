[500 Global Scraper](https://apify.com/michael.g/500-global-scraper?fpr=data)

## What does 500 Global Scraper do?

500 Global Scraper allows you to extract data about companies from the [500 Global (formerly 500 Startups)](https://500.co/portfolio): company name, description, stage, country, region, website, LinkedIn, and more.

## About 500 Global

500 Global is a venture capital firm that invests across sectors, geographies and markets where capital and their unique global networks and resources may unlock the potential of entrepreneurs to drive uncommon outcomes. They have invested in companies across various stages from Pre-Seed to Growth.

## Company data fields

| Field Name | Type | Description |
| --- | --- | --- |
| Company Image | String (URL) | Company image URL |
| Company Name | String | Company name |
| Description | String | Company description |
| Stage | String | Investment stage (Pre-Seed, Seed, Series A, etc.) |
| Country | String | Company country |
| Business Model | String | Business model (B2B, B2C, etc.) |
| Website | String (URL) | Company website |
| Company LinkedIn | String (URL) | Company LinkedIn profile URL |

## Why scrape 500 Global?

- **Lead generation:** identifying startups for potential collaboration or investment.
- **Market research:** analyzing trends and popular niches in the startup ecosystem.
- **Studying the startup landscape:** understanding successful approaches and business models.
- **Finding inspiration:** exploring ideas and innovations that could influence your own project.

## Example Input

Portfolio URL: [https://500.co/portfolio?page=1&industry=AI/Machine%20Learning&region=all&stage=all&country=all&bModel=all&batch=all&sort=alphabetically#companies-table](https://500.co/portfolio?page=1&industry=AI/Machine%20Learning&region=all&stage=all&country=all&bModel=all&batch=all&sort=alphabetically#companies-table)

![Input Example](https://images.apifyusercontent.com/m-l3SMF50I4RDd4jyYU02WGFYhg-g40DZhrQDvEQfo0/w:1800/cb:1/aHR0cHM6Ly9pLmltZ2hpcHBvLmNvbS9maWxlcy9zWXk1NjQyalEucG5n.webp)

And here's the same, just in JSON.

```
{
  "url": "https://500.co/portfolio?page=1&industry=AI/Machine%20Learning&region=all&stage=all&country=all&bModel=all&batch=all&sort=alphabetically#companies-table",
  "scrape_all_companies": false
}
```

## Output sample

The results will be wrapped into a dataset which you can find in the Storage tab. Note that the output is organized in a table for viewing convenience. Here's an example of some of the output from the previous companies search URL:

![Output Sample](https://images.apifyusercontent.com/TNdDXB7ba761bdMLt2JT_9HmC8EMfA3a5wUGNzBxjcw/w:1800/cb:1/aHR0cHM6Ly9pLmltZ2hpcHBvLmNvbS9maWxlcy9jeG5yNzc5N1JwUS5wbmc.webp)

By clicking on the green Export button, you can download the dataset in XML, CSV, Excel, HTML, or JSON. See an example of a JSON file:

```
{
    "company_image": "https://500.co/_next/image?url=https%3A%2F%2Ffounder-hub-public.s3.amazonaws.com%2Fdf27f718-40b9-40ed-b77b-9219544de495.png&w=128&q=75",
    "company_name": "Talkdesk",
    "description": "Developer of cloud-based call center software designed to help growing businesses improve customer satisfaction while reducing costs. The company's platform uses IVR, ACD, and skills-based routing technology that seamlessly integrates ITSM and CSM service desks, enabling businesses to communicate with their customers and manage the entire call center operations using the web.",
    "stage": "Series D & Beyond",
    "country": "United States",
    "business_model": "B2B",
    "website": "http://www.talkdesk.com",
    "company_linkedin": "https://www.linkedin.com/company/talkdesk"
}
```

## How do I use 500 Global Scraper?

500 Global Scraper is designed to help you easily extract company data from the portfolio page. Follow these steps:

1. **Run the Scraper:** Click "Start" and wait for the data extraction to complete.
2. **Export your data:** Download in Excel, CSV, JSON, HTML, or via API.

## How much does 500 Global Scraper cost?

This scraper uses the Pay-per-result pricing model, so your costs can be easily calculated: it will cost you **$10 to scrape 1,000 companies**, which is $0.010 per item. Apify provides you with $5 in free usage credits every month on the [Apify Free plan](https://apify.com/pricing?fpr=home), allowing you to **scrape over 50 companies** from the 500 Global portfolio for free using those credits.

For regular data extraction, consider upgrading to the [$29/month Starter plan](https://apify.com/pricing?fpr=home), which can **get you over 2,900 companies every month.**

## Integrations and 500 Global Scraper

500 Global Scraper can be connected with almost any cloud service or web app thanks to integrations on the Apify platform. You can integrate with Make, n8n, Zapier, Apollo, Clay, Slack, Airbyte, GitHub, Google Sheets, Google Drive, and [more](https://docs.apify.com/platform/integrations).

## Your feedback

We're always working on improving the performance of our Actors. If you've got any technical feedback for 500 Global Scraper or simply found a bug, please create an issue on the actor's [Issues tab](https://console.apify.com/actors/dt6pOPzVU16Rv4pom/issues) in Apify Console.