# Robots Analysis for the Daily Pennsylvanian

The Daily Pennsylvanian's `robots.txt` file is available at
[https://www.thedp.com/robots.txt](https://www.thedp.com/robots.txt).

## Contents of the `robots.txt` file on March 22, 2025

```
User-agent: *
Crawl-delay: 10
Allow: /

User-agent: SemrushBot
Disallow: /
```

## Explanation

Allow: / – Explicitly allows crawling of the entire site. No sections are disallowed for these crawlers, meaning every URL on the domain is permitted
User-agent: SemrushBot + Disallow: – This section targets SemrushBot (a specific SEO crawler) and gives it an empty Disallow rule, meaning the site isn’t blocking any pages for SemrushBot. This SemrushBot section omits any Crawl-delay, which means the general 10-second delay in the * section doesn’t apply to SemrushBot
