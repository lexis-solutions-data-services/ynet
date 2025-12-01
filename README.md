# Ynet Scraper

![banner](https://lexis-solutions-apify.fra1.cdn.digitaloceanspaces.com/banners/ynet-co-il.png)

## 🔎 What is the Ynet Scraper?

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.18` |
| **Last Update** | Dec 1, 2025 |

---



## 💻 Integration Examples

This repository includes example code showing how to integrate the `ynet` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---



The Ynet Scraper is a web scraping tool that allows you to extract news articles from Ynet.co.il, one of Israel's leading news websites. This actor crawls the website to fetch the latest news articles and extracts specific fields of interest from various sections of the site.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-x8sMdZ9I3sVM4BsVQ-kYiAhXnTWa-ynet-co-il.png" alt="Ynet.co.il Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/ynet" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


## 🧾 What data can the Ynet Scraper extract?

The Ynet Scraper can extract the following data from Ynet.co.il:

- URL
- Headline
- Subtitle
- Author Name
- Image URL
- Timestamp

## 💼 What use cases does the Ynet Scraper have?

The Ynet Scraper is a web scraping tool used for collecting news data from Ynet.co.il, Israel's popular news portal. It allows users to extract comprehensive news data for various purposes.

Use Cases:

- **Media Monitoring**: Track news coverage on specific topics or events across Israeli media.
- **Content Aggregation**: Aggregate news content for news apps, digests, or newsletters.
- **Market Intelligence**: Monitor news for market-moving events, company mentions, or industry developments.
- **Sentiment Analysis**: Analyze news sentiment around specific companies, individuals, or topics.
- **Research and Analysis**: Collect data for academic or journalistic research on media coverage.
- **SEO and Content Marketing**: Identify trending topics and keywords for content creation.
- **Competitive Intelligence**: Monitor industry news and competitor mentions.
- **Event Detection**: Identify breaking news or emerging trends in real-time.

## 📖 How to use the Ynet Scraper?

1. Create a free Apify account
2. Open Ynet Scraper
3. Configure proxy settings if needed
4. Click Start and wait for the results
5. Download the results in JSON, XML, or CSV format or connect the actor to your backend via API

## 📥 Input

The actor doesn't require any specific input parameters to run, but you can configure:

- **Proxy configuration** - choose between default proxy settings, Apify's RESIDENTIAL proxy, or a custom proxy URL

## 📤 Output

The results are stored in the default dataset associated with the actor. Each item is a news article, having the following format:

```json
{
  "url": "https://www.ynet.co.il/news/article/example-article",
  "headLine": "Example headline of a news article",
  "subTitle": "This is a subtitle that provides additional context about the article",
  "authorName": "John Doe",
  "imageUrl": "https://ynet.co.il/images/example-image.jpg",
  "timeStamp": 1684667520000
}
```

## How many results can I scrape?

The Ynet Scraper extracts all articles present on the homepage of Ynet.co.il, including the top stories, various section articles, opinions, and more. This typically includes several dozen news articles from a single crawl of the homepage.

## Why use the Ynet Scraper?

- ⚡️ **Fast** - The scraper is fast and efficient, allowing you to extract news articles in a programmatic way.

- 🤙 **Easy to use** - The scraper is easy to use and requires no coding knowledge. Just run the actor and get structured data.

- ☑️ **Well-Maintained** - The scraper is maintained by the Lexis Solutions team, ensuring that it is always up-to-date and working properly.

## FAQ

- **Is Scraping Ynet Legal?**

  The current scraper only scrapes public data from Ynet.co.il. This means that the data is publicly available and can be accessed by anyone. However, we recommend that you check Ynet's Terms of Service before using the scraper.

- **How much does it cost?**

  The cost for using the Ynet Scraper is shown on the top of this page. You can also check the Apify Store page for more information.

---

## Need to scrape other news or content websites?

- Social Media 📱

  - [Instagram Scraper](https://apify.com/lexis-solutions/instagram-scraper)
  - [Twitter Scraper](https://apify.com/lexis-solutions/twitter-scraper)
  - [Meta Threads Scraper](https://apify.com/lexis-solutions/meta-threads-scraper)
  - [TikTok Trending Videos Scraper](https://apify.com/lexis-solutions/tiktok-trending-videos-scraper)

- News & Content 📰
  - [Reddit Links Scraper](https://apify.com/lexis-solutions/reddit-links-scraper)

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!
