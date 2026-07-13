## 🤖 [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

Simple web scraper for extracting exhibitor data from a specific type of trade show exhibitor lists provided by **Xporience**. Easily scrape company profiles including **company details, websites, social media links, product sectors**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. Supports multiple **Xporience** exhibition websites with a consistent HTML structure.

> [Apify](https://apify.com/) is a cloud platform and marketplace for web scraping and automation tools.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Website Structure](#supported-website-structure)

- [Supported Xporience Events (Exhibitor Lists)](#supported-xporience-events-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Xporience event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (country, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter, YouTube)

- Two output formats (Single-Row & Multi-Row)

- Multi-Row format for Excel-friendly product sector filtering

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Website Structure

- This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported Xporience exhibitor lists below.

- Take a look at some of the event websites from the below list. Your event website URL might be in that list.

- If you are not sure about if this actor is capable of scraping your event URL, test it with [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor.

---

## Supported Xporience Events (Exhibitor Lists)

> The following partial list includes Xporience exhibitor directory URLs that have been tested so far. Other Xporience events or different events with the same website structure may also be supported.

> Some event URLs may have been updated or canceled entirely; please check them before using.

- [AI Everything GLOBAL 2026 Exhibitor List – exhibitors.gitex.com/ai-everything-global-2026](https://exhibitors.gitex.com/ai-everything-global-2026/Exhibitor)

- [Dubai International Boat Show 2026 Exhibitor List – exhibitors.gitex.com/dibs-2026](https://exhibitors.gitex.com/dibs-2026/Exhibitor/)

- [GISEC Global 2026 Exhibitor List – exhibitors.gisec.ae/gisec-global-2026](https://exhibitors.gisec.ae/gisec-global-2026/Exhibitor)

- [GITEX EUROPE 2026 Exhibitor List – exhibitors.gitex.com/gitex-europe-2026](https://exhibitors.gitex.com/gitex-europe-2026/Exhibitor)

- [Gitex Africa 2026 Exhibitor List – exhibitors.gitexafrica.com/gitex-africa-2026](https://exhibitors.gitexafrica.com/gitex-africa-2026/Exhibitor)

- [GITEX GLOBAL DWTC 2025 Exhibitor List – exhibitors.gitex.com/gitex-global-2025](https://exhibitors.gitex.com/gitex-global-2025/Exhibitor)

- [Dubai International Boat Show 2025 Exhibitor List – exhibitors.gitex.com/dibs-2025](https://exhibitors.gitex.com/dibs-2025/Exhibitor/)

- [Fintech Surge 2025 Exhibitor List – exhibitors.gitex.com/fintech-surge-2025](https://exhibitors.gitex.com/fintech-surge-2025/Exhibitor)

- [Future Blockchain Summit 2025 Exhibitor List – exhibitors.gitex.com/future-blockchain-summit-2025](https://exhibitors.gitex.com/future-blockchain-summit-2025/Exhibitor)

- [GITEX EUROPE 2025 Exhibitor List – exhibitors.gitex.com/gitex-europe-2025](https://exhibitors.gitex.com/gitex-europe-2025/Exhibitor)

- [Expand North Star 2025 Exhibitor List – exhibitors.expandnorthstar.com/expand-north-star-2025](https://exhibitors.expandnorthstar.com/expand-north-star-2025/Exhibitor)

- [AI Everything GLOBAL 2025 Exhibitor List – exhibitors.gitex.com/ai-everything-global-2025](https://exhibitors.gitex.com/ai-everything-global-2025/Exhibitor)

- [Gitex Africa 2025 Exhibitor List – exhibitors.gitexafrica.com/gitex-africa-2025](https://exhibitors.gitexafrica.com/gitex-africa-2025/Exhibitor)

- [Indo Pacific 2025 Exhibitor List – exhibitors.indopacificexpo.com.au/indo-pacific-2025](https://exhibitors.indopacificexpo.com.au/indo-pacific-2025/Exhibitor)

- [Gulfood Manufacturing 2025 Exhibitor List – exhibitors.indopacificexpo.com.au/indo-pacific-2025](https://exhibitors.gulfoodmanufacturing.com/gulfood-manufacturing-2025/Exhibitor)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Sectors</td>
        </tr>
        <tr>
            <td>Country</td>
            <td>Instagram</td>
            <td>Brands</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>YouTube</td>
            <td></td>
        </tr>
    </tbody>
</table>

<br>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://exhibitors.gulfood.com/gulfood-2026/Exhibitor/ExbDetails/11er-nahrungsmittel-gmbh",
  "__company_name": "11er Nahrungsmittel GmbH",
  "_company_country": "Austria",
  "_company_website": "https://www.11er.at",
  "_hall_stands": "Stand No- 5-111, South Hall 1",
  "_social_url_linkedin": "https://at.linkedin.com/company/11er-nahrungsmittel",
  "_social_url_facebook": "https://www.facebook.com/11erkartoffelspezialitaeten/",
  "_social_url_instagram": "https://www.instagram.com/11ergenusswelt/",
  "_social_url_youtube": "https://www.youtube.com/user/elferaustria",
  "product_sectors": ["Specialty Food", "Snacks", "Private Label", "Halal and Kosher Food", "Frozen Food", "Value-Added Food", "Gourmet & Fine Food", "Finger Food", "Frozen Ready Meals", "Frozen Baked Goods"]
}
```

<br>

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)