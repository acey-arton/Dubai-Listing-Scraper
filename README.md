# Dubai Listing Scraper
>The Dubai Listing Scraper extracts detailed property listings from Bayut.com, the UAE's largest real estate platform. Perfect for real estate professionals, market researchers, and investors, this tool gathers data like property prices, specifications, agent contacts, and more—ideal for market analysis, lead generation, or competitive research.

<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Dubai Listing Scraper</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The Dubai Listing Scraper helps you collect comprehensive property details from Bayut.com, including prices, descriptions, agent information, and location data. Whether you're analyzing the real estate market in the UAE, generating leads, or studying property trends, this tool delivers all the information you need in a structured format for easy analysis.

### What It Helps You Do
- Gather real estate data including property pricing, agent contacts, and specifications.
- Track market trends across different locations in the UAE.
- Generate leads by collecting agent contact details.
- Conduct competitive research on available properties.

---
## Features
| Feature | Description |
|---------|-------------|
| **Complete Property Details** | Extracts property titles, descriptions, pricing, specifications, and more. |
| **Agent & Agency Data** | Collects agent names, profile links, contact info, and agency details. |
| **Advanced Filters** | Filters by property purpose (Buy/Rent), type, price range, and location. |
| **Image & Virtual Tour Links** | Retrieves images and virtual tour links to enhance property listings. |
| **High-Performance Extraction** | Smart pagination and error handling for large-scale data scraping. |
| **Location & Pricing Data** | Provides location-based property searches and currency-formatted pricing. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| title | Property title or name. |
| description | Full description of the property. |
| price | Property price in AED (formatted currency). |
| rooms | Number of rooms in the property. |
| baths | Number of bathrooms in the property. |
| area | Property area in square meters. |
| address | Complete property address and location details. |
| images | URLs of property images. |
| virtualTour | Link to virtual tour of the property, if available. |
| agentName | Name of the property agent. |
| agentProfileLink | Link to the agent’s profile page. |
| agencyName | Name of the agency listing the property. |
| agencyContact | Agency contact information, including phone and WhatsApp. |
| professionalLicense | License number or certification of the agent/agency. |

---
## Example Output
    
    [
      {
        "title": "3-Bedroom Apartment in Downtown Dubai",
        "description": "This beautiful 3-bedroom apartment offers stunning views of the Burj Khalifa. With spacious rooms and modern amenities, it's ideal for families.",
        "price": 1500000,
        "rooms": 3,
        "baths": 2,
        "area": 120,
        "address": "Downtown Dubai, Dubai, UAE",
        "images": [
          "https://www.bayut.com/images/3bed-apartment.jpg"
        ],
        "virtualTour": "https://www.bayut.com/virtual-tour/3bed-apartment",
        "agentName": "John Doe",
        "agentProfileLink": "https://www.bayut.com/agents/john-doe",
        "agencyName": "ABC Real Estate",
        "agencyContact": "+971 50 123 4567, +971 4 789 0123",
        "professionalLicense": "XYZ123456"
      }
    ]

---
## Directory Structure Tree
    
    Dubai Listing Scraper/
    ├── src/
    │   ├── main.js
    │   ├── scraper/
    │   │   ├── property_scraper.js
    │   │   ├── agent_data_extractor.js
    │   │   └── pagination_handler.js
    │   ├── utils/
    │   │   ├── image_downloader.js
    │   │   └── data_formatter.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── sample_input.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **Real Estate Agents** use it to track property listings, manage contacts, and monitor market prices.  
- **Market Researchers** analyze property trends, neighborhood comparisons, and price fluctuations.  
- **Investors** gather detailed property data to make informed investment decisions.  
- **Lead Generation Teams** collect agent details and property info for outbound marketing.  
- **Real Estate Platforms** integrate this tool for automatic listing imports and updates.  

---
## FAQs

**How do I filter properties?**  
The scraper allows you to filter properties by purpose (buy/rent), type, location, price, and other attributes.

**Can I get agent contact details?**  
Yes, the scraper extracts agent names, contact info, and profile links.

**Is the data available in structured format?**  
Yes, the scraper outputs data in clean, structured formats like JSON, CSV, or Excel.

**How do I handle pagination?**  
The scraper automatically handles pagination, ensuring you get the full set of property listings.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Processes hundreds of listings per minute depending on network speed and page structure.

**Reliability Metric:**  
Maintains a success rate above 98%, even with complex listings and agent details.

**Efficiency Metric:**  
Optimized for large-scale scraping, the tool handles thousands of listings without performance degradation.

**Quality Metric:**  
Delivers highly accurate and complete property data, including images, descriptions, and metadata.


---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>
