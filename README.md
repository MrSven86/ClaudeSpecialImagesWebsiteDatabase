# Velocity Client Database

Client collateral, scraped data and assets organized by industry.

## Structure
```
clients/
  hair-salons/
    [client-name]/
      brief.json
      captions.txt
      research.txt
      photos/
      site-url.txt
  nail-salons/
  barbers/
  painters/
  restaurants/
  _template/
```

## Adding a new client
1. Run Velocity Scraper (Scrape All)
2. Download full brief JSON
3. Create folder: clients/[industry]/[business-name]-[city]
4. Upload brief.json, captions.txt, research.txt
5. Add photos to photos/ folder
6. After build, add site-url.txt with the Vercel URL
