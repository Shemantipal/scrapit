 # **LinkedIn Jobs Scraper**

LinkedIn Jobs Scraper running in Node.js that uses Puppeteer and RxJS to scrape job offers from LinkedIn.

- Parses LinkedIn job offers and returns the data in JSON format  
- Loops through all the pages for a specified search parameters  
- Loops through as many search parameters as needed  
- Uses RxJS Observables instead of Promises  
- Handles 429 status code error  
- Handles LinkedIn Authwall  
- Saves the scraped data as JSON in an auto-generated /data folder  
- It is written entirely in TypeScript  
