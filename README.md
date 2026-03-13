# PhillDocs (docs.phillips-network.work)

Public documentation portal (BookStack) with installation guides, troubleshooting and how-tos.

Live site: https://docs.phillips-network.work/

---

## Quick Links

- Home: https://docs.phillips-network.work/
- Books: https://docs.phillips-network.work/books
- Example guide (Windows 11):  
  https://docs.phillips-network.work/books/windows/page/windows-11-installation-mit-microsoft-account

---

## SEO / Google Indexing

This site is intended to be discoverable via Google. Use the links below to verify crawlability and indexing signals.

### Crawling & Sitemaps

- `robots.txt`: https://docs.phillips-network.work/robots.txt
- Sitemap index (submit this in Google Search Console):  
  https://docs.phillips-network.work/sitemap-index.xml
- Sitemap (referenced by the index):  
  https://docs.phillips-network.work/sitemap.xml

### Google Search Console Checklist

1. **Sitemaps**
   - Submit: `https://docs.phillips-network.work/sitemap-index.xml`
   - If an old `sitemap.xml` entry shows errors (historical 404), remove it and keep only the index.

2. **URL Inspection**
   - Run “Live Test”
   - Request indexing for:
     - Home page
     - `/books`
     - Top 5–20 most important guides

3. **Verification**
   - Search: `site:docs.phillips-network.work`
   - Note: it can take time until results appear, even if crawling works.

---

## Server-side Verification (copy/paste)

### 1) Sitemaps must return `200` and `application/xml`
```bash
curl -I https://docs.phillips-network.work/sitemap-index.xml | egrep -i 'HTTP/|Content-Type|Content-Length'
curl -I https://docs.phillips-network.work/sitemap.xml       | egrep -i 'HTTP/|Content-Type|Content-Length'
```

Wenn du mir noch sagst, ob du ein **Open-Source Repo** (Code/Configs) oder nur eine **Doku-Repo-Seite** meinst, kann ich das README im Ton und in den Sections (Install/Deployment, Docker, Apache vhost, Cron für Sitemap, etc.) passend zuschneiden. 
::contentReference[oaicite:0]{index=0}

