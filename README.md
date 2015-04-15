Yakuza Example: Reddit
======================

This repository shows how to scrape sub-reddits with the [Yakuza](https://github.com/Narzerus/yakuza) framework

Run with:
`node test.js`

You can change which sub-reddits are scraped by changing the following line:

```javascript
  job = Yakuza.job('Articles', 'Reddit', {subreddits: ['WatchPeopleCode']});

  // To whatever you want to scrape, it supports multiple subreddits and will return one big response.
```