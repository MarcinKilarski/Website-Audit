# Instructions for Search Engine Optimisation (SEO) Audit Report

## Table of Content

1. [Site-Level Factors](#1-site-level-factors)  
  1.1. [Manual Penalty](#11-manual-penalty)  
  1.2. [Algorithmic Demotion](#12-algorithmic-demotion)  
  1.3. [Domain Extension](#13-domain-extension)  
  1.4. [Subdomain](#14-subdomain)  
  1.5. [Internal Links](#15-internal-links)  
  1.6. [Keywords in Internal Links](#16-keywords-in-internal-links)  
  1.7. [Orphan pages](#17-orphan-pages)  
  1.8. [User Generated Content](#18-user-generated-content)  
  1.9. [Preferred Domain](#19-preferred-domain)  
  1.10. [Site Depth](#110-site-depth)  
  1.11. [Subdirectories](#111-subdirectories)  
  1.12. [Accessible Subdirectories](#112-accessible-subdirectories)  
  1.13. [Outbound Links](#113-outbound-links)  
  1.14. [Website Sitelinks](#114-website-sitelinks)  
  1.15. [Descriptive Media File Names](#115-descriptive-media-file-names)  
2. [Page-Level Factors](#2-page-level-factors)
  2.1. [Missing Title Tag](#21-missing-title-tag)
  2.2. [Keywords in Titles](#22-keywords-in-titles)
  2.3. [Duplicate Titles](#23-duplicate-titles)
  2.4. [Title Length](#24-title-length)
  2.5. [Headings](#25-headings)
  2.6. [Keywords in Headings](#26-keywords-in-headings)
  2.7. [Keywords in Main Content](#27-keywords-in-main-content)
  2.8. [Missing Meta Descriptions](#28-missing-meta-descriptions)
  2.9. [Keywords in Meta Descriptions](#29-keywords-in-meta-descriptions)
  2.10. [Meta Descriptions Length](#210-meta-descriptions-length)  
  2.11. [Duplicate Meta Descriptions](#211-duplicate-meta-descriptions)
  2.12. [Keywords in URLs](#212-keywords-in-urls)  
  2.13. [Separating Words in URLs](#213-separating-words-in-urls)  
  2.14. [Descriptive URLs](#214-descriptive-urls)  
  2.15. [URL Length](#215-url-length)  
  2.16. [Dates in URL](#216-dates-in-url)  
  2.17. [Unsafe Characters in URLs](#217-unsafe-characters-in-urls)  
  2.18. [Missing Alternative Text for Multimedia](#218-missing-alternative-text-for-multimedia)  
  2.19. [Keywords in Alternative Text](#219-keywords-in-alternative-text)  
  2.20. [Meta Keywords](#220-meta-keywords)  
  2.21. [Number of Links on a Page](#221-number-of-links-on-a-page)
  2.22. [Important Content in the Source Code](#222-important-content-in-the-source-code)
3. [Technical](#3-technical)  
  3.1. [Page Indexation](#31-page-indexation)  
  3.2. [4XX Client Error](#32-4xx-client-error)  
  3.3. [5XX Server Error](#33-5xx-server-error)  
  3.4. [Page Render](#34-page-render)  
  3.5. [Pages Restricted From Indexing](#35-pages-restricted-from-indexing)  
  3.6. [Canonicalisation](#36-canonicalisation)  
  3.7. [301 Redirects](#37-301-redirects)  
  3.8. [302 Redirects](#38-302-redirects)  
  3.9. [Redirect Chains](#39-redirect-chains)  
  3.10. [Meta Refresh](#310-meta-refresh)  
  3.11. [Sitemap for Robots](#311-sitemap-for-robots)  
  3.12. [Language Markup](#312-language-markup)  
  3.13. [Schema Markup](#313-schema-markup)  
  3.14. [Rich Cards](#314-rich-cards)  
  3.15. [Soft 404 Client Error](#315-soft-404-client-error)  
  3.16. [Frames](#316-frames)  
  3.17. [URL Parameters](#317-url-parameters)  
  3.18. [Redirects to Preferred Domain](#318-redirects-to-preferred-domain)  
  3.19. [Server Up-time](#319-server-up-time)  
  3.20. [Crawlable Resources](#320-crawlable-resources)  
  3.21. [Hypertext Transfer Protocol Secure (HTTPS)](#321-hypertext-transfer-protocol-secure-https)  
  3.22. [Google Publisher Markup](#322-google-publisher-markup)  
  3.23. [Preventing Directory Snippets](#323-preventing-directory-snippets)  
4. [User Experience](#4-user-experience)  
  4.1. [Mobile Friendly Test](#41-mobile-friendly-test)  
  4.2. [PageSpeed Insights](#42-pagespeed-insights)  
  4.3. [Accelerated Mobile Pages (AMP)](#43-accelerated-mobile-pages-amp)  
  4.4. [Response Time](#44-response-time)  
  4.5. [Pop-ups](#45-pop-ups)  
  4.6. [Hidden Content](#46-hidden-content)  
  4.7. [Text in Images](#47-text-in-images)  
  4.8. [Breadcrumb Navigation](#48-breadcrumb-navigation)  
  4.9. [Ads](#49-ads)  
  4.10. [Sliders](#410-sliders)  
  4.11. [Pagination](#411-pagination)  
  4.12. [Flash](#412-flash)  
  4.13. [Sitemap for Humans](#413-sitemap-for-humans)  
  4.14. [Image Pages](#414-image-pages)  
  4.15. [404 Page](#415-404-page)  
  4.16. [Search](#416-search)  
  4.17. [Code Validation](#415-code-validation)  
5. [Content](#5-content)  
  5.1. [Thin Content](#51-thin-content)  
  5.2. [Internal Duplicate Content](#52-internal-duplicate-content)  
  5.3. [External Duplicate Content](#53-external-duplicate-content)  
  5.4. [Keyword Cannibalization](#54-keyword-cannibalization)  
  5.5. [Related Keywords](#55-related-keywords)  
  5.6. [Hints & Tips or How-To Content](#56-hints--tips-or-how-to-content)  
  5.7. [Fresh Content](#57-fresh-content)  
  5.8. [Content Pruning](#58-content-pruning)  
  5.9. [Content Ideas](#59-content-ideas)  
  5.10. [Internal Search Queries](#510-internal-search-queries)  
  5.11. [Queries for Which Your Images Rank](#511-queries-for-which-your-images-rank)  
6. [Local](#6-local)  
  6.1. [Country Targeting](#61-country-targeting)  
  6.2. [Geo-Focused Keywords](#62-geo-focused-keywords)  
  6.3. [Business Name, Address, Phone (NAP)](#63-business-name-address-phone-nap)  
  6.4. [Google My Business](#64-google-my-business)  
  6.5. [Local Citations](#65-local-citations)  
  6.6. [Bing Places for Business](#66-bing-places-for-business)  
  6.7. [Apple Maps](#67-apple-maps)  
  6.8. [Reviews](#68-reviews)  
  6.9. [Responses to Reviews](#69-responses-to-reviews)  
  6.10. [Server Location](#610-server-location)  
  6.11. [Physical Web](#611-physical-web)  
7. [Off-Site](#7-off-site)  
  7.1. [Referring Domains](#71-referring-domains)  
  7.2. [Referring Pages (aka Backlinks)](#72-referring-pages-aka-backlinks)  
  7.3. [Link Targeting](#73-link-targeting)  
  7.4. [Broken Backlinks](#74-broken-backlinks)  
  7.5. [Anchor Texts](#75-anchor-texts)  
  7.6. [Online Mentions](#76-online-mentions)  
  7.7. [Disavow File](#77-disavow-file)  
  7.8. [Branded Search Query Results](#78-branded-search-query-results)  
  7.9. [Search Autocomplete](#79-search-autocomplete)  
  7.10. [Mostly Shared Pages](#710-mostly-shared-pages)  
  7.11. [Site Neighbourhood](#711-site-neighbourhood)  
8. [Competitor Analysis](#8-competitor-analysis)  
  8.1. [Search Visibility](#81-search-visibility)  
  8.2. [Referring Domains](#82-referring-domains)  
  8.3. [Referring Pages (aka Backlinks)](#83-referring-pages-aka-backlinks)  
  8.4. [Type of Content](#84-type-of-content)  
  8.5. [Keyword in Title](#85-keyword-in-title)  
  8.6. [Content Length](#86-content-length)  
  8.7. [Search Ads History](#87-search-ads-history)  
  8.8. [Search Ads Data](#88-search-ads-data)  
  8.9. [Engagement](#89-engagement)  

## 1. Site-Level Factors

### 1.1. Manual Penalty

#### Used Tools

1. Google Search Console
2. Bing Webmaster Tools

#### Instructions

#### Example of Recommendation

Great, there are no warnings from Google or Bing informing us that a manual penalty might be affecting your website's visibility in search.

### 1.2. Algorithmic Demotion

#### Used Tools

- https://fruition.net/sem/user/39619/dashboard
- or Panguin Tool
- or SEMrush > Domain Analytics > Overview
- https://moz.com/google-algorithm-change
- https://linchpinseo.com/list-of-google-algorithm-updates-seo/
- https://www.mariehaynes.com/algo-changes-and-more/
- https://barracuda.digital/panguin-google-algorithm-timeline/

#### Instructions

#### Example of Recommendation

After analysing your website traffic, Google algorithms and search changes in 2017 (Figure 1.2.1) and 2016 (Figure 1.2.2), we can’t see that your site was significantly affected by any of the algorithm updates.

Figure 1.2.1 – Your website traffic in 2017 and all known Google algorithm changes from that time.

Figure 1.2.2 – Your website traffic in 2016 and all known Google algorithm changes from that time.

Figure 1.2.3 – Your website traffic in 2015 and all known Google algorithm changes from that time.

### 1.3. Domain Extension

#### Used Tools

#### Instructions

#### Example of Recommendation

When choosing a domain extension, it is important to ask yourself: ‘How do I want my users to perceive my business?’ If your business needs to be seen as an international business, you should consider using Generic Top-Level Domains. If your business needs to be seen as a local business, then a Country-Code Top-Level Domain (ccTLD) would be a better fit. As a local business, an Irish domain with the .ie extension could increase the number of clicks your pages receive in the search results, helping you rank higher in local searches. However, this operation may lead to a short-term traffic drop.

I noticed that [ENTER DOMAIN X] is used to target users in Poland, [ENTER DOMAIN Y] targets users across all European countries. These two domain extensions are generic, which means that by default they don’t get a ranking boost in any specific country, making it more difficult to have a competitive advantage over country specific domains, like example.de or example.pl. This can be improved by selecting in Google Search Console and Bing Webmaster Tools which country each of these domains target, gaining more search visibility in these countries and attracting more potential customers. These tools are free for website owners to use.

However, in general, sites with generic domain extensions may attract less people when they appear in search results with other local domains. This happens as I customers consciously as well as unconsciously constantly make many assumptions based on information provided and our past experiences. 

When I are looking for a product locally and I see unknown website with .com, I make assumptions that:

- this business might be based abroad
- a delivery might take longer time
- it might be more expensive
- it might be more problematic and expensive to return the product
- calling the customer service might be expensive, as I might need to call an international number

When you see in search results domains like these below, you might first choose to check out those with your country domain extension and only afterward the other ones if you still have not found what you are looking for.

- example1.ie
- example2.com
- example3.ie
- example4.com
- example5.ie

Therefore, it might be better to host the Polish version of the site on domain like [ENTER DOMAIN X] and keep the [ENTER DOMAIN Y] for international expansion. 
Some companies decide to keep all language variations of their pages under one centralised domain, placing each language in one directory. They target other countries with each of these domains, using Google Search Console and Bing Webmaster Tools.

- example.com/BMW
- example.com/pl/BMW
- example.com/de/BMW

This approach partially solves the above-mentioned issue, as the country or language code in the URL provides hint to searchers that this is a version of this site designed for their country. 
In addition, ranking authority cumulated by the main domain benefits language variations of its pages, and accordingly, ranking authority acquired by pages in these languages benefit the main domain. It helps these pages faster climb rankings in search results. 
Moreover, a business only needs one main domain to virtually expand across all countries in the world. 

### 1.4. Subdomain

#### Used Tools

1. Screaming Frog > Configuration > select Crawl subdomains
    Sort crawled HTML files by domain and check if there are any other domains.
2. Check if there are any subdomains installed on the server.
3. ReverseInternet > Check ‘Subdomains’ tab
    Then, use Scrape Similar to gather the list of URLs, using the XPath query:
    //a[text()=’visit site’]/@href
    Export your results to a CSV, then load the CSV into Screaming Frog using ‘List’ mode. Once the spider has finished running, you’ll be able to see status codes, as well as any links on the subdomain homepages, anchor text and duplicate page titles among other things.
4. Ask the client about other subdomain, domain, printed resources, digital resources and internal materials that weren't published on the main domain.

#### Instructions

#### Example of Recommendation

Great, we haven't found any content that doesn't live on your main domain.

### 1.5. Internal Links

#### Used Tools

1. Check which internal links Google sees
    Google Search Console > Search Traffic > Internal Links
2. Calculate PR of internal pages
3. Consolidate HTTP and HTTPS links
4. Internal: follow
5. Internal: nofollow
6. Check orphaned pages

#### Instructions

#### Example of Recommendation

Your homepage receives the highest number of incoming internal links ([# of links]), increasing its chance to rank well in a search. However, [page X and page Y] pages, for which you would like to improve the ranking, receive only 26 incoming internal links each.

You should consider adding more links on your site that point to these pages. Creating more pages with helpful content related to [PAGE X and PAGE Y] could be a great way of doing this.

Figure 1.5 – A list of all your pages and the number of links on your site that point to them.

### 1.6. Keywords in Internal Links

#### Used Tools
Screaming Frog > Bulk Export > All Outlinks
Clean up data by filtering out any external sites

#### Instructions

#### Example of Recommendation

None of the internal links from pages on your site, pointing to your homepage, use your primary keyword ‘[KEYWORD X]’ (Figure 1.6.1). We recommend changing the alt text of your business logo image from ‘[X]’ to ‘[Y]’, as this will help increase the relevance of your page for the query ‘[KEYWORD Y]’.

Links to your [PAGE Y] and [PAGE Z] pages contain the primary keyword ‘[KEYWORD Y]’ or ‘[KEYWORD Z]’, but you also should consider linking from other places on your site with secondary keywords like ‘[KEYWORD YY]’ or ‘[KEYWORD ZZ]’ in the anchor text. This way you will increase their chances of ranking for these keywords in the search.
Figure 1.6.1 – A list of incoming internal links pointing to your homepage, and all anchor and alt texts used in them

| Source        | ALT Text           | Anchor Text  |
| ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder |

Figure 1.6.2 – A list of incoming internal links pointing to your [PAGE Y] page, and all anchor and alt texts used in them.

| Source        | ALT Text           | Anchor Text  |
| ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder |

Figure 1.6.3 – A list of incoming internal links pointing to your [PAGE Z] page, and all anchor and alt texts used in them.

| Source        | ALT Text           | Anchor Text  |
| ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder |

### 1.7. Orphan pages

#### Used Tools

- Screaming Frog
- Server logs - get list of visited pages and crawl it

#### Instructions

1. Crawl sitemap with Screaming Frog tool.
2. Check which what pages are visited in server log files.
3. Check pages which are indexed by Google and Bing.

#### Example of Recommendation

Great, we didn't detect any orphan pages on your site.

### 1.8. User Generated Content

#### Used Tools

Do links in comments are nofollow?
Are there any spammy comments?
Screaming Frog > ‘Configuration’ tab on the top bar > Custom > Extraction
Add comment, review, page, etc. with a link as a user, and check if the link was nofollowed

#### Instructions

#### Example of Recommendation

Great, we didn’t find any spam-like user-generated content your site.

### 1.9. Preferred Domain

#### Used Tools

Google Search Console > the gear icon in the upper right corner > Site Settings 

#### Instructions

#### Example of Recommendation

You haven’t specified in the Google Search Console what your preferred domain is. You also have not uploaded the sitemap to Bing Webmaster Tools. We recommend completing these two tasks.

### 1.10. Site Depth

#### Used Tools

Screaming Frog > Site Structure (in the sidebar)

#### Instructions

#### Example of Recommendation

Great, all of your pages are a maximum of two clicks away from your homepage.

Figure 1.10.1. A graph showing number of found pages and how many clicks they are away from the homepage.
![A graph showing around 30 pages one click away from homepage, and around 90 pages 2 clicks away from the homepage](https://github.com/MarcinKilarski/website-audit/blob/master/resources/images/site-structure.png)

### 1.11. Subdirectories

#### Used Tools

#### Instructions

#### Example of Recommendation

Good job, your pages do not have more than two directories.
Figure 1.11.1 – A list of pages on your site that have more than three directories.

| URLs        | Number of directories          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 1.11.2. A list of pages, which URL structure should be updates.

| Title        | Current URL Structure          | Recommended URL Structure          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 1.12. Accessible Subdirectories

#### Used Tools

#### Instructions

#### Example of Recommendation

All your directories are accessible, no action required.
Figure 1.12 – A list of all inaccessible directories on your website.

| URLs        |
| ------------- |
| placeholder     |

### 1.13. Outbound Links

#### Used Tools

1. Screaming Frog > External tab > Export all
2. Check are their follow or nofollow 
    Screaming Frog > Bulk Export top bar > All Outlinks
    In Excel: Remove duplicates and links to client’s site
    Excel > Data tab > Advanced > Unique records only 
3. Go to Moz Open Site Explorer
    Check for Domain Authority, Page Authority and Spam Score
4. Check in Excel if link to sites with low DA and high Spam Score are nofollow 
5. Host-machine-ratio > 5 = potential indication that your site is spammy

#### Instructions

#### Example of Recommendation

An authority of one of the domains, which your site associates itself with by linking to, is quite low ([DOMAIN X]). It is good practice to set up a ‘nofollow’ tag on that link and on any that may be untrustworthy (Figure 1.13).

In addition, your link to a website from all pages or a very large number of them. It’s recommended you have all of these ‘site-wide’ and tagged as ‘nofollow’ links ([DOMAIN Z]).

The table below shows websites to which you point to from your pages. Domain and Page Authority shows an estimate of how trusted and respected a website may be on the Internet. Spam Score shows the likelihood of a site being spam. The number of outbound links represents how many times that link was found on your site.
Figure 1.13 – A list of websites with the lowest ‘authority’ and the highest likelihood of being spam to which your site sends users.

| Link        | Domain Authority           | Page Authority  | Spam Score        | Number of Outbound links           | Dofollow / Nofollow  |
| ------------- | ------------- | ----- | ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder | placeholder     | placeholder | placeholder |

### 1.14. Website Sitelinks

#### Used Tools

#### Instructions
Perform a branded search on Google and Bing and check if any sitelinks are displayed.

#### Example of Recommendation

While sitelinks are not showing up under your homepage on Bing, Google shows six of them when a user searches for your brand name (Figure 1.13). They all look good.
Figure 1.14 – A screenshot of your website’s sitelinks in Google.

### 1.15. Descriptive Media File Names

#### Used Tools

#### Instructions

#### Example of Recommendation

All of your images have descriptive file names.

Figure 1.15 – A list of images which don’t use hyphen to separate words in the file names.

| URLs        |
| ------------- |
| placeholder     |

## 2. Page-Level Factors

### 2.1. Missing Title Tag

#### Used Tools

#### Instructions

#### Example of Recommendation

Great job, all of your pages have a title tag.

### 2.2. Keywords in Titles

#### Used Tools

#### Instructions

#### Example of Recommendation

We analysed keywords that you use in the titles of your [PAGE X] page, [PAGE Y] page and [PAGE Z] page. Here is what we found:

The three pages, which you want to rank for the specific query, contain your important keywords in their titles (Figure 2.2), but your [PAGE X] is missing the word ‘[KEYWORD X]’. Furthermore, all of them should be rewritten to sound more interesting, as this will help your business whether or not the searcher clicks through to your site.

Figure 2.2 – The title tags of pages that focus on your main keywords.  

| Keyword        | Title of the page ranking for the keyword          | URL   |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 2.3. Duplicate Titles

#### Used Tools

Screaming Frog
Search Console

#### Instructions

Check pages with Screaming Frog and in Search Console > Search Appearance > HTML Improvements

#### Example of Recommendation

### 2.4. Title Length

#### Used Tools

#### Instructions

#### Example of Recommendation

Some of your pages do not have optimised titles. It’s vital to spend some time crafting compelling titles to improve the ranking of your pages and to increase the number of searchers who may find them interesting enough to visit your site. [NUMBER] of your page titles are too short (Figure 2.4).
Figure 2.4 – A list of pages on your site with short titles.

| URL        | Title           | Number of characters  |
| ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder |

### 2.5. Headings

#### Used Tools

#### Instructions

1. Identify headings with Woorank (Chrome Extension) >
2. Check font size with CSSViewer (Chrome Extension)
3. Check does a heading contain an image or logo.

#### Example of Recommendation

Figure 2.5.1 – A number of headings by type, how many of them were detected on your [DELETE: PLACEHOLDER: PAGE X] page.

| H1        | H2        | H3        | H4        | H5        |
| ----- | ----- | ----- | ----- | ----- |
| placeholder     | placeholder | placeholder | placeholder     | placeholder |

Figure 2.5.2 – A list of headings on the page that ranks for keyword ‘[DELETE: KEYWORD X]’.

| Heading Text        | Heading Type           | Heading Size/Text Size  |
| ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder |

 Figure 2.5.3 – A number of headings by type, how many of them were detected on your [DELETE: PLACEHOLDER: PAGE Y] page.

| H1        | H2        | H3        | H4        | H5        |
| ----- | ----- | ----- | ----- | ----- |
| placeholder     | placeholder | placeholder | placeholder     | placeholder |

Figure 2.5.4 – A list of headings on the page that ranks for keyword ‘[DELETE: KEYWORD Y]’.

| Heading Text        | Heading Type           | Heading Size/Text Size  |
| ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder |

 Figure 2.5.5 – A number of headings by type, how many of them were detected on your [DELETE: PLACEHOLDER: PAGE Z] page.

| H1        | H2        | H3        | H4        | H5        |
| ----- | ----- | ----- | ----- | ----- |
| placeholder     | placeholder | placeholder | placeholder     | placeholder |

Figure 2.5.6 – A list of headings on the page that ranks for keyword ‘[DELETE: KEYWORD Z]’.

| Heading Text        | Heading Type           | Heading Size/Text Size  |
| ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder |

### 2.6. Keywords in Headings

#### Used Tools

#### Instructions

Woorank Chrome Extension >

#### Example of Recommendation

Your homepage main heading is optimised for keywords ‘[DELETE: PHRASE G]’instead of being optimised for ‘[DELETE: PHRASE A]’ (Figure 2.6.1). We recommend rewriting this to include the phrase ‘[DELETE: PHRASE F]’ or something similar. Other pages contain their primary keywords in the main heading, which is ideal.

Figure 2.6.1 – A list of headings on the page that ranks for keyword ‘[DELETE: KEYWORD X]’.

| Heading Type        | Text          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 2.6.2 – A list of headings on the page that ranks for keyword ‘[DELETE: KEYWORD Y]’.

| Heading Type        | Text          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 2.6.3 – A list of headings on the page that ranks for keyword ‘[DELETE: KEYWORD Z]’.

| Heading Type        | Text          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 2.7. Keywords in Main Content

#### Used Tools

http://www.seocentro.com/tools/search-engines/metatag-analyzer.html

#### Instructions

#### Example of Recommendation

We analysed the keywords you use in the main content of your homepage, [DELETE: PAGE A NAME] page and [DELETE: PAGE B NAME] page. Here is what we found:

On the homepage, the phrases used most often are ‘[DELETE: PHRASE A]’ and ‘[DELETE: PHRASE B]’ instead of your targeted keyword ‘[DELETE: PHRASE C]’ (Figure 2.7.3, Figure 2.7.4). The word ‘[DELETE: PHRASE D]’ occurs 6 times, while the word ‘[DELETE: PHRASE C]’ occurs only 4 times within the 397 words on the page (Figure 2.7.2). However, these words are not displayed on the page together or even close to each other (Figure 2.7.1). In addition to this, the word ‘[DELETE: WORD A]’ is rarely used in the main content. You should consider rewriting some parts of your page to include the keywords ‘[DELETE: PHRASE A]’ or ‘[DELETE: PHRASE B].

On your [DELETE: PAGE A] page, your main keyword is detected 9 times (Figure 2.7.6, Figure 2.7.7, Figure 2.7.8), while in the main copy it appears 6 times within the 309 words of text (Figure 2.7.5). This is a healthy ratio. We recommend using the word ‘[DELETE: WORD A]’ together with the word ‘[DELETE: WORD B]’ within the copy, e.g. ‘[DELETE: PHRASE A]’ to strengthen your local relevance.

On your [DELETE: PAGE A] page, we detected your main keyword 13 times (Figure 2.7.10, Figure 2.7.11, Figure 2.7.12), but only 7 times in the page’s visible copy (Figure 2.7.9). This is because in the page’s code, you have hidden duplicate mobile content, which should be fixed. In addition to this, you should rewrite the copy to include the phrase ‘[DELETE: PAGE A] in Dublin’, as this should also improve your page ranking for this query.

Figure 2.7.1 – The text content of your homepage with highlighted primary keywords (bolded text) and related (underlined text) keywords.

Figure 2.7.2 – A list of one-word keywords that occur most often on your homepage, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

Figure 2.7.3 – A list of two-word keywords that occur most often on your homepage, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

Figure 2.7.4 – A list of three-word keywords that occur most often on your homepage, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

Figure 2.7.5 – The text content of your [DELETE: PAGE B] page with highlighted primary (bolded text) and related (underlined text) keywords. 

Figure 2.7.6 – A list of one-word keywords that occur most often on your [DELETE: PAGE B] page, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

Figure 2.7.7 – A list of two-word keywords that occur most often on your [DELETE: PAGE B] page, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

Figure 2.7.8 – A list of three-word keywords that occur most often on your [DELETE: PAGE B] page, together with the number of times they were repeated (Freq), what percentage of the page’s content contains this word (density).

Figure 2.7.9 – The text content of your [DELETE: PAGE A] page with highlighted primary (bolded text) and related (underlined text) keywords.

Figure 2.7.10 – A list of one-word keywords that occur most often on your [DELETE: PAGE A] page, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

Figure 2.7.11 – A list of two-word keywords that occur most often on your [DELETE: PAGE A] page, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

Figure 2.7.12 – A list of three-word keywords that most often occur on your [DELETE: PAGE A] page, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

### 2.8. Missing Meta Descriptions

#### Used Tools

#### Instructions

#### Example of Recommendation

Good job, all of your pages have specified meta description tags.

Figure 2.8 – A list of pages that do not have a meta description tag.

| URLs        |
| ------------- |
| placeholder     |

### 2.9. Keywords in Meta Descriptions

#### Used Tools

#### Instructions

#### Example of Recommendation

We have analysed keywords used in the meta descriptions of your [PAGE X] page, [PAGE Y] page and [PAGE Z] page (Figure 2.12). Here is what we found:

Your meta descriptions contain important keywords, but your [PAGE X] is missing the word ‘[KEYOWRD X]’, which will be highlighted in bold font in the search results by Google and Bing. This could attract more searchers to your page.
Figure 2.12 – The meta descriptions of pages that focus on your main keywords.  

| Keyword        | Meta Description of the page ranking for keyword          | URL   |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 2.10. Meta Descriptions Length

#### Used Tools

#### Instructions

#### Example of Recommendation

Only one of your pages has a meta description that is too short. This requires your attention.

Figure 2.13.1 – A list of pages on your site with short meta descriptions.

| URL        | Meta Description          | Number of characters   |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 2.13.2 – A list of pages that have excessively long meta descriptions.

| URL        | Meta Description          | Number of characters   |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 2.11. Duplicate Meta Descriptions

#### Used Tools

1. Screaming Frog > Meta Description > Filter: Duplicate
2. Search Console > Search Appearance > HTML Improvements

#### Instructions

#### Example of Recommendation

A few of your pages have duplicate descriptions (Figure 2.14). These should be rewritten. 
Figure 2.14 – A list of pages with duplicated meta descriptions.

| URL        | Duplicate Meta Description          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 2.12. Keywords in URLs

#### Used Tools

#### Instructions

#### Example of Recommendation

We analysed the keywords you use in the URLs of your homepage, [PAGE Y] page and [PAGE Z] page. Here is what we found:

Your homepage ranks on both Google and Bing for ‘[KEYWORD X]’ and ‘[KEYWORD Y]’. For the keyword ‘[KEYWORD X]’ this is ideal. The URL also looks as it should (Figure 2.3). However, for the keyword ‘[KEYWORD Y]’ there is an issue, as the search engines think that the homepage is more relevant than your dedicated page for this keyword. We need to work on improving the quality (more valuable content), relevance (more content around this keyword on the page and internal links that mention ‘’) and authority (more backlinks from other websites) of this page. This should fix the issue of a wrong page ranking for your targeted keyword.

Figure 2.3 – The URLs of pages that focus on your main keywords.

| Keyword        | URL of a page ranking for keyword          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 2.13. Separating Words in URLs

#### Used Tools

Screaming Frog > URL tab > Filter: Underscores

#### Instructions

#### Example of Recommendation

All of your URLs use the right method of separating words.

### 2.14. Descriptive URLs

#### Used Tools

#### Instructions

#### Example of Recommendation

All of your URLs are easy to read and understand.

### 2.15. URL Length

#### Used Tools

#### Instructions

1. ‘Stop words’
2. Automatically generated numbers at the end of the URLs

#### Example of Recommendation

Great, none of your URLs are too long.
Figure 2.15.1 – A list of URLs longer than 80 characters.

| URL        | Number of characters          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 2.15.2 –  A list of pages on your site with auto-generated numbers.

| URL        |
| ------------- |
| placeholder     |

### 2.16. Dates in URL

#### Used Tools

#### Instructions

#### Example of Recommendation

Excellent, your URLs do not contain dates.

Figure 2.5 – A list of pages on your site with dates in the URLs.

| URL        |
| ------------- |
| placeholder     |

### 2.17. Unsafe Characters in URLs

#### Used Tools

#### Instructions

Screaming Frog > URL tab > Filter: Non ASCII characters/Uppercase/Dynamic

#### Example of Recommendation

Great, there are no unsafe characters or Non-ASCII characters in your URLs.

### 2.18. Missing Alternative Text for Multimedia

#### Used Tools

#### Instructions

alt for images, videos, <canvas>

1. Internal Note: Screaming Frog > Bulk Export > Images > Images Missing Alt Text
2. To find pages that contain embedded video or audio content, set a custom filter for a snippet of the embed code for YouTube, or any other media player that is used on the site.


#### Example of Recommendation

We notice that 68 images on your site (80%) lack the alternative text (Figure 2.19). A short image description that relates to the content on the page should be added to each of them.
Figure 2.19 – A list of pages that contain images without an alt tag.

| Page        | Image          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 2.19. Keywords in Alternative Text

#### Used Tools

#### Instructions

Screaming Frog > Bulk Export tab in the top bar > All Images

#### Example of Recommendation

We analysed keywords you use in the Alt tag of your images from your homepage, [PAGE B] page and [PAGE A] page. Here is what we found:

Your homepage uses the keyword ‘Dublin’ 7 times in the Alt tag and the keyword ‘[KEYWORD C]’ only once (Figure 2.20.1). You should rewrite 1-2 alternative texts to include the phrase ‘[PHRASE F] or ‘[PHRASE I]’. Both your [PAGE B] and [PAGE A] pages have two mentions of their targeted keyword in the Alt tags (Figure 2.20.2 and Figure 2.20.3). However, you should try rewriting them to include the phrases ‘[PHRASE A]’ and ‘[PAGE A] in Dublin’ instead of only the one-word keyword.
Figure 2.20.1 – A list of images on your homepage with their Alt text.

| URL        | ALT tag          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 2.20.2 – A list of images on your [PAGE B] page with their Alt text.

| URL        | ALT tag          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 2.20.3 – A list of images on your [PAGE A] page with their Alt text.

| URL        | ALT tag          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 2.20. Meta Keywords

#### Used Tools

#### Instructions

#### Example of Recommendation

Great, there are no meta keyword tags on your pages.

### 2.21. Number of Links on a Page

#### Used Tools

#### Instructions

#### Example of Recommendation

Great, none of your pages have over 200 links.

### 2.22. Important Content in the Source Code

#### Used Tools

https://www.diffchecker.com/

#### Instructions

1. Right-click on the page that you want to check and select "View source-code".
2. Copy source-code of a page that you are checking into the first field of the Diffchecker tool.
3. Right-click on the page and select "Inspect".
4. Right-click on the HTML tag and copy everything in the tag. Then enter it into the second field of the Diffchecker tool.
5. If you detect a difference in important content, copy the content that is different and past it in quotation marks into the Google search and Bing search. E.g. "This is the content that is different."
6. If you get a lot of results, search for a more substantial chunk of content in the search engine.
7. If you cannot find this content in the search engines, most likely, it was not seen by them on the page, which is an issue.

#### Example of Recommendation

Great, all importnat content is present on in the source code of your pages.

## 3. Technical

### 3.1. Page Indexation

#### Used Tools

#### Instructions

Check the number of pages:
- Google Search Console > Google Index > Index Status
- Go to Bing and search for site:domainname.ie
vs.
- static pages on the site discovered by Screaming Frog
- pages in sitemaps

#### Example of Recommendation

Google shows 48 pages from your site (Figure 3.1.1) in its search results, while Bing has 65 of your pages in its search (Figure 3.1.2). However, our crawl only found 29 static pages, which were reachable by a link-to-link crawl (Figure 3.1.3). 

After examining the results provided by the search engines, we notice your website’s ‘News’ and ‘Our Team Blog’ sections are listed in Google and Bing, but we did not find them on your site. If you don’t want users to access these sections, and the search engines to take them into account when scoring your site, you should remove them from the search engines.
Figure 3.1.1 – A screenshot showing how many of your pages Google has indexed in its search.

Figure 3.1.2 – A screenshot showing how many of your pages Bing has indexed in its search.

Figure 3.1.3 – A list of all pages found on your site via a link-to-link crawl.

| URL        |
| ------------- |
| placeholder     |

### 3.2. 4XX Client Error

#### Used Tools

#### Instructions

To find these errors cross-check data from a few of tools below:

1. Google Search Console > Crawl > Crawl Errors > check Desktop and Smartphone tab
2. Bing Webmaster Tools > Report & Data > Crawl Information
3. Google Analytics > Behaviour > Site Content > All Pages > Page Titles (tab) > then search for ‘404’ and ‘not found’. Click on the found result to see URLs which have triggered the error if the site setup 404 tag tracing. Otherwise check ‘Navigation Summary’ tab for information on which pages broken links were found. Make sure that you have selected to see more than 10 results (right-bottom corner).
4. Screaming Frog (after the crawl is completed, go to ‘Bulk Export’ in the navigation bar, then ‘All Outlinks.’ You can sort by URLs and see which pages are sending a 404 signal. Repeat the same step with ‘All Inlinks.’)
5. Integrity
6. DeepCrawl (If you’re using DeepCrawl, go to the ‘Unique Broken Links’ tab under the ‘Internal Links’ section.)

#### Example of Recommendation

Google has reported 14 errors in the Search Console that they detected while crawling your site (Figure 3.11.1). Your Google Analytics reported a person landing on ‘Page 404’ 108 times from November 11th to February 10th (Figure 3.11.2). 43% of the time, a user left your site after not seeing the requested page.

Our crawl of your site identified 28 URLs that currently trigger a ‘404 error’ (Figure 3.11.3). One relates to a broken main image on ‘Our Most Popular Bets’ page ([PAGE D URL]). Four links point to an external page, which no longer exists. The other 23 are the result of a broken link in the mobile version of your site’s footer.
Broken link: <a href=‘info@[WEBSITE ADDRESS]‘>
Correct link:  <a href=‘mailto:info@[WEBSITE ADDRESS]‘>
All of these errors should be fixed.

Figure 3.11.1 – ‘404 errors’ reported by Google in the Search Console.

| URL        | Platform           | Response Code  | Detected  |
| ------------- | ------------- | ----- | ----- |
| placeholder     | placeholder | placeholder | placeholder |

### 3.3. 5XX Server Error

#### Used Tools

#### Instructions

Cross-check to find these errors DeepCrawl, Screaming Frog, and Google and Bing webmaster tools

#### Example of Recommendation

Great, no ‘5XX errors’ were detected on your site during the site crawl and Google Search Console review.

### 3.4. Page Render

#### Used Tools

#### Instructions

Fetch and render in:

- Google Search Console > Crawl > Fetch as Google
- Bing Webmasters Tools > Diagnostics & Tools > Fetch as Bing

#### Example of Recommendation

Everything looks fine. We checked the homepage, one of your other pages, product pages and blog post. By checking each type of page on your site, this provides a good indication as to whether there are problems with how they render to search engines.

### 3.5. Pages Restricted From Indexing

#### Used Tools

#### Instructions

1. Screaming Frog > Response Codes > Filter: Blocked by Robots.txt
2. Screaming Frog > Directives > Filter: Noindex 
3. Google Search Console > Google Index > Remove URLs
4. https://www.google.com/webmasters/tools/removals?pli=1
5. https://technicalseo.com/seo-tools/robots-txt/

#### Example of Recommendation

Great, you don’t block any important pages from appearing in the search results. The only pages that you block are pages that should not be indexed:

- TERMS & CONDITIONS
- [PAGE C]
- Our Team Blog (this page appears in the search results with a URL which is not blocked) 

### 3.6. Canonicalisation

#### Used Tools

#### Instructions

Screaming Frog > Internal tab
Check if canonical URLs are not the same on other pages.
Check do individual pages use self-referring canonical.
Common errors with canonical tag 

- The canonical tag leads to a non-existing page.
- You use the same canonical tag with the same URL on all pages of your website.
- You put the canonical attribute in the body part of a web page instead of the head part.
- The canonical tag links to another website. This is correct when you syndicate your content on other websites. However, you should not use canonical tags with external links if you want to get high rankings for your own web pages.

#### Example of Recommendation

Excellent, all of your pages have specified rel=‘canonical’.

### 3.7. 301 Redirects

#### Used Tools

#### Instructions

Screaming Frog > Bulk Export > Response Codes > Redirects 3xx inlinks

#### Example of Recommendation

There are 72 internal redirects discovered on your site (Figure 3.6). Most of these are due to using the ‘non-www’ version of your site (e.g. [WEBSITE URL]) instead of the ‘www’ version (e.g. [WEBSITE URL]). This should be fixed to improve the time it takes to load your pages and improve your ranking.
Figure 3.6 – A list of pages (‘Page’ column) on which a URL (‘Link’ column) redirects users and the search engines to another URL (‘Final Destination’ column).

| Page        | Link          | Anchor Text   | Final Destination   |
| ------------- | ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder | placeholder |

### 3.8. 302 Redirects

#### Used Tools

#### Instructions

Remove any of these permanent redirects from the sitemap and any internal or external links

#### Example of Recommendation

Good, no ‘302 redirects’ were discovered on your website.

Figure 3.7 – A list of pages (‘Page’ column) on which a URL (‘Link’ column) redirects users and the search engines to another URL (‘Final Destination’ column).

| Page        | Link          | Anchor Text   | Final Destination   |
| ------------- | ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder | placeholder |

### 3.9. Redirect Chains

#### Used Tools

#### Instructions

Screaming Frog

1. Configuration > Spider > Advanced tab > select ‘Always Follow Redirects’
2. Crawl website
3. Reports (top bar) > Redirect Chains

#### Example of Recommendation

There are 87 URLs on your site, which trigger the redirect chain on your site (Figure 3.9). However, all of them are related to your business page on [THIRD-PARTY WEBSITE URL]. Replacing these with a direct link could improve the ranking of this page.

Figure 3.9 – A list of pages (‘Source’ column) with a URL (‘Destination’ column), which redirects users and the search engines more than once to another URL (‘Final Destination’ column).

| Source        | Destination          | Final Destination   | Number of Redirects   |
| ------------- | ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder | placeholder |

### 3.10. Meta Refresh

#### Used Tools

#### Instructions

Screaming Frog > Configuration > Custom > Search >

Contain 

<meta http-equiv=‘refresh’

#### Example of Recommendation

Great, your pages don’t use meta refresh.

### 3.11. Sitemap for Robots

#### Used Tools

#### Instructions

1. Check following locations of sitemaps
    a. example.com/sitemap.xml
    b. example.com/sitemap_index.xml
2. Google Search Console > Crawl > Sitemaps
3. Bing Webmaster Tools
4. Sitemap validation Tools
    a.  Code Beautify
    b. XML Validation
5. Screaming Frog > Mode > Lists
    Configuration > Spider > Advanced > select Always Follow Redirects (this way you will detect which pages do not exist)
    Upload > Download Sitemap then Download Sitemap Index (links found on in the sitemaps will have Level: 0) 

Look for pages with:
a. redirects
b. URLs parameters
c. any non-indexable pages
d. duplicate URLs
e. Is it up to date?

Look for pages with:
- redirects
- URLs parameters
- any non-indexable pages
- duplicate URLs
- Is it up to date?

#### Example of Recommendation

We notice an old sitemap and a set of the new sitemaps on your server. The old one may cause search engines to not discover these new sitemaps.
- The old sitemap
[WEBSITE URL]/sitemap.xml
- The set of new sitemaps
[WEBSITE URL]/sitemap_index.xml

Your website has an old sitemap, which contains 38 links to unsecured versions of your pages (Figure 3.15.1), and to two pages which no longer exist (Figure 3.15.2).
The set of new sitemaps has a separate list of:
- Pages
- Posts
- News
- Posts Categories

A set of your new sitemaps also includes links to unsecure versions of your 38 pages (Figure 3.15.3), and two pages that do not exist (Figure 3.15.4). Your posts, categories and news are not reachable from any page on your site. If you don’t want the search engines to show them to your users, these sitemaps should be removed.
A link to your set of sitemaps should be places in the robots.txt file on your server. We recommend removing the old sitemap and update the links to your pages in your set of new sitemaps. You should also create a sitemap for your images, to help the search engines quickly find and index them.

Figure 3.15.1 – A list of links to unsecured versions of your site in the old sitemap ([WEBSITE URL]/sitemap.xml).
URL

| URL        |
| ------------- |
| placeholder     |

Figure 3.15.2 – A list of links to pages that do not exist in the old sitemap ([WEBSITE URL]/sitemap.xml).
URL

| URL        |
| ------------- |
| placeholder     |

Figure 3.15.3 – A list of links to pages that do not exist in the old sitemap ([WEBSITE URL]/sitemap_index.xml).
URL

| URL        |
| ------------- |
| placeholder     |

Figure 3.15.4 – A list of links to pages that do not exist in the old sitemap ([WEBSITE URL]/sitemap_index.xml).
URL

| URL        |
| ------------- |
| placeholder     |

### 3.12. Language Markup

#### Used Tools

#### Instructions

Screaming Frog > Reports (top tab) > Hreflang

- Do language and country codes are correct (ISO codes)?
- Do pages link back to each other?
- Do they use absolute URLs?

#### Example of Recommendation

Your site contains content in English and Chinese, which it is not marked-up for the search engines with ‘hreflang’. This should be fixed to make it clear to Google and Bing what the primary language of your site is, and which other languages are available.

### 3.13. Schema Markup

#### Used Tools

#### Instructions

Tool to analysing the schema markup on the site: 
- http://t.dripemail2.com/c/eyJhY2NvdW50X2lkIjoiMzc3NjM2NCIsImRlbGl2ZXJ5X2lkIjoiMTI1NTI3MjE3MiIsInVybCI6Imh0dHBzOi8vYXBwLnNjaGVtYWFwcC5jb20vYW5hbHl6ZXI_X19zPW1xcW85bXpjdHRzOThyNXZocm96In0
- Website

  SearchAction

- Breadcrumbs
- LocalBusiness

  Opening hours
  Social media accounts
  Company description
  Logo
- Organisation
  Multiple departments
- Reviews
- Event (now also in Google Maps)
- Articles (Top Stories)
- Books
- Music
- Podcasts
- Recipes
- TV&Movies
- Video
- Products (now also in image search)
- Restaurant Listings (NEW)
- Online Courses (NEW)

Identify pages with schema markup
Screaming Frog > Configuration > Custom > Filter 1 ‘Contain’ ‘scheme.org/’ or ‘itemtype=http://schema.org’
To find a specific type of markup, you’ll have to be more specific. For example, using a custom filter for ‹span itemprop=‘ratingValue’› will get you all of the pages that contain Schema markup for ratings.
Validate schema markup used on the website.
https://search.google.com/structured-data/testing-tool

#### Example of Recommendation

We see WebSite and SearchAction schema markup on your homepage and Article schema markup on the news and blog section of your site, which is not currently linked to display on your site to users. Your Article markup misses some required information on who the author is and when the page was recently updated. These were highlighted by Google as errors in Google Search Console (Figure 3.19).
You should consider adding LocalBusiness, Breadcrumbs, Event, and Reviews markup to your pages to help the search engines better understand what information your content contains.
Figure 3.19 – A list of pages on your site with detected schema markup errors.

| URL        | Errors          | Last Detected   |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 3.14. Rich Cards

#### Used Tools

#### Instructions

#### Example of Recommendation

At the moment, no rich cards are shown for your pages. Consider adding a page on which customers can review your business. You will be able to use these to display a review rating under your site in the search results. In addition to this, you could markup your tournaments in schema, which could trigger an ‘event’ rich card in Google.

### 3.15. Soft 404 Client Error

#### Used Tools

#### Instructions

1. Google Search Console > Crawl > Crawl Errors > check Desktop and Smartphone tab
2. Bing Webmaster Tools

#### Example of Recommendation

Great, there are no soft ‘404 errors’ reported by Google.

### 3.16. Frames

#### Used Tools

#### Instructions

Screaming Frog > Configuration > Custom > Extraction
XPath
//iframe/@src
Extract HTML Element

#### Example of Recommendation

I notice there are two pages on your site with maps in frames (Figure 3.22), although neither of them has the alternative text. Additionally, the location of your business on these maps is very difficult to locate, as too many icons are displayed at once.  

Figures 3.22 – Pages with content in frames.

| URL        |
| ------------- |
| placeholder     |

### 3.17. URL Parameters

#### Used Tools

#### Instructions

if the URL has weird characters like ?, =, or + it’s a dynamic URL which can cause duplicate content if not fixed.
You can search for URL parameter in
1. Google by doing site:www.buyaunicorn.com/ inurl: ‘?’ or whatever you think the parameter may include.
2. Screaming Frog > URL > Filter: Parameters
3. Check and update a list of parameters in Google Search Console under ‘Crawl’ > ‘URL Parameters
4. Check and update a list of parameters in Bing Webmasters Tools > Configure My Site > Ignore URL Parameters
5. Check robots.txt if some URL parameters are already blocked
6. Make sure that the internal links do not have campaign parameters, as this may mislead your site’s attribution data.
Screaming Frog > Configuration (top bar) > Custom > Search
example.ie\(.*)utm_source=(.*)utm_medium=
or example.ie(.*)utm_source=(.*)utm_medium=
or example.ie/(.*)utm_source=(.*)utm_medium=
(check these)

#### Example of Recommendation

Users do not see any parameters in your URL. Good job.

Figure 3.3 – A list of your pages with URL parameters.

| URL        |
| ------------- |
| placeholder     |

### 3.18. Redirects to Preferred Domain

#### Used Tools

#### Instructions

#### Example of Recommendation

Great, your website redirects users from the wrong versions of your domain to the correct one. 

### 3.19. Server Up-time

#### Used Tools

#### Instructions

Setup website monitoring in Site24x7.com

#### Example of Recommendation

We have been monitoring your server up time every 10 minutes for the past 14 days and have not detected any down time (Figure 3.19).

Figure 3.19 – A diagram showing result of two weeks monitoring of your server’s up time.

### 3.20. Crawlable Resources

#### Used Tools

#### Instructions

Check whether any of these files’ types are blocked from being crawled in:
1. robots.txt file
2. Google Search Console > Google Index > Blocked Resources
3. Bing Webmaster Tools
4. Screaming Frog > Response Codes tab > Filter: Blocked Resource

#### Example of Recommendation

Good news, none of your resources are blocked.

### 3.21. Hypertext Transfer Protocol Secure (HTTPS)

#### Used Tools

#### Instructions

Screaming Frog > internal check URLs

#### Example of Recommendation

Great, your site uses HTTPS.

### 3.22. Google Publisher Markup

#### Used Tools

#### Instructions

Check for Rel=‘publisher’ on the site, and test it with http://www.google.com/webmasters/tools/richsnippets And check if a link back from business Google+/Google My Business account to site’s homepage is correct (www or non-www, http or https).
Screaming Frog > Configuration > Custom > Search
  Contains
rel=‘publisher’

#### Example of Recommendation

The Publisher’s markup wasn’t discovered on your website. You should add this to your business pages to improve your brand visibility in search results.

### 3.23. Preventing Directory Snippets

#### Used Tools

Screaming Frog > Internal HTML report > filter by pages which doesn’t contain ‘noodp’ and ‘noindex’

#### Instructions

#### Example of Recommendation

You are in control of almost all of your meta descriptions.

## 4. User Experience

### 4.1. Mobile Friendly Test

#### Used Tools

#### Instructions

1. Google
https://search.google.com/test/mobile-friendly
or
https://search.google.com/search-console/mobile-friendly
or Bulk test:
https://technicalseo.com/seo-tools/mobile-friendly/
2. Bing
https://www.bing.com/webmaster/tools/mobile-friendliness
3. Google Analytics > devices, browsers, screen sizes (look for high bounce rate and short time on page.)
4. Manual – Check how major pages’ render on iOS and an Android device.

#### Example of Recommendation

Good job, all pages that were found pass Google’s Mobile-Friendly test.

### 4.2. PageSpeed Insights

#### Used Tools

#### Instructions

Google PageSpeed Insights test
https://developers.google.com/speed/pagespeed/insights/ 

#### Example of Recommendation

The mobile version of your homepage scores 40 out of 100 points, while the desktop version scores 37 out of 100. Your Membership’s page score is 40 on mobile phones and 51 on desktop.
There are many parts of your site that should be optimised to improve your page load time and ranking. Here are the links to results of both tests, and suggestions on how to fix detected issues.
https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2F[WEBSITE ADDRESS]%2F 
https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2F[WEBSITE ADDRESS]%2Fmembership%2F&tab=mobile

### 4.3. Accelerated Mobile Pages (AMP)

#### Used Tools

#### Instructions

1. Screaming Frog > Configuration > Custom > Extraction
XPath
//head/link[@rel='amphtml']/@href
Extract HTML Element
2. Validate AMP Pages
- https://chrome.google.com/webstore/detail/amp-validator/nmoffdblmcmgeicmolmhobpoocbbmknc?hl=en
- https://validator.ampproject.org/
- Do a search in Google for “amp page test”
https://www.google.ie/search?q=amp+page+test&gws_rd=cr&dcr=0&ei=b2TCWYLDGIKWgAb9spu4Dg

#### Example of Recommendation

We didn’t detect any Accelerated Mobile Pages on your site. Consider creating AMP versions of your pages for additional visibility in search results and faster load times on mobile phones.

### 4.4. Response Time

#### Used Tools

#### Instructions

Screaming Frog > Response Time

#### Example of Recommendation

The response time of your pages during our site crawl varied between 0.7 second and 4.1 seconds (Figure 4.3). This is something that should be decreased as soon as possible.
Figure 4.3 – Response time of your pages.

| URL        | Response Time (seconds)           |
| ------------- | ------------- |
| placeholder     | placeholder |

### 4.5. Pop-ups

#### Used Tools

#### Instructions

#### Example of Recommendation

Great, we did not find any intrusive interstitials on your main pages, both on desktop and mobile. 

### 4.6. Hidden Content

#### Used Tools

#### Instructions

1. Check for unnatural word count on the page with Screaming frog
2. Check for usage of display: none on the pages

#### Example of Recommendation

Good job, you don’t hide any important content from searchers.

### 4.7. Text in Images

#### Used Tools

- Seeing images indexed by Google: https://www.google.ie/search?hl=en&biw=1920&bih=969&tbm=isch&sa=1&ei=805pXJH4BYLxxgO_-ZX4Cg&q=site%3Aexample.com&oq=site%3Aexample.com&gs_l=img.3...2371.3550..3763...0.0..0.36.149.5......0....1..gws-wiz-img.U-hBGZl7Mok
- Seeing images crawled by Screaming Frog: develop a tool

#### Instructions

find a tool that shows all images on one page for easy inspection.
In Google Image Search for site:sitename.com

#### Example of Recommendation

Great, there is no text embedded in your images.

### 4.8. Breadcrumb Navigation

#### Used Tools

#### Instructions

When you can see the breadcrumb navigation on the site, use Screaming Frog to identify all the pages on which it appears.
Screaming Frog > Configuration > Custom > Extraction

#### Example of Recommendation

We do not see the breadcrumb navigation on your site. We recommend adding it to your pages.

### 4.9. Ads

#### Used Tools

#### Instructions

#### Example of Recommendation

There are no excessive ads on your website.

### 4.10. Sliders

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.11. Pagination

#### Used Tools

#### Instructions

Scream Frog > Directives > Next/Prev
DeepCrawl > ‘First Page’ report
Review pages manually

#### Example of Recommendation

Great, you do not have a problem with pagination.

### 4.12. Flash

#### Used Tools

#### Instructions

Go to Screaming Frog

1. Head to the ‘Spider Configuration’ in the navigation.
2. Click ‘Check SWF.’
3. Filter the ‘Internal’ tab by ‘Flash’ after the crawl is done.

#### Example of Recommendation

Excellent, your website doesn’t use Flash.

### 4.13. Sitemap for Humans

#### Used Tools

#### Instructions

#### Example of Recommendation

Unfortunately, we haven’t found the sitemap for humans on your site. You should consider adding it to improve the user experience.

### 4.14. Image Pages

#### Used Tools

#### Instructions

Dedicate page for each image, full size image, title, description.

#### Example of Recommendation

Your images in searches take users to pages where those images were used instead of the dedicated pages. This often makes it difficult to find or use the image a person is searching for. You should consider setting up a dedicated page for each of your images to increase the number of people referring to your website

### 4.15. 404 Page

#### Used Tools

#### Instructions

It should have:

- Clear information that the page they were looking for couldn’t be found
- Your site’s main navigation
- A custom image
- Consistent design with the rest of your site
- Links to most popular pages
- A search functionality
- a way for users to report a broken link
- Return the 404 (Not found) or 410 (Gone) response code

#### Example of Recommendation

Currently, your Page 404 looks slightly broken on desktops (Figure 4.10). The look could also be improved by adding a custom image, links to most popular pages with page thumbnails, suggestion to check the URL looks correct, and a way to report a broken link.

Figure 4.10 – A screenshot of your current 404 page viewed on desktop.

### 4.16. Search

#### Used Tools

#### Instructions

Manual:

- On the site check is there a search box
- On the search results page check:
  Layout
  Thumbnail
  Title
  Description
  Link

#### Example of Recommendation

The search box is on your site, but the search results page could be improved (Figure 4.11.1). On desktops, when a user misspells a word, he or she lands on a page that looks broken.
When the word is entered correctly, the page looks better, but its layout could still be improved (Figure 4.11.2). Additionally, thumbnail images could be added to make the results more helpful, and a URL could also be included below the page description.

Figure 4.11.1 – A screenshot of your current search results page viewed on desktop, with no much for user’s query.

Figure 4.11.2 – A screenshot of your current search results page viewed on desktop, with pages matching for user’s query

### 4.17. Code Validation

#### Used Tools

#### Instructions

1. Unicorn - W3C's Unified Validator: https://validator.w3.org/unicorn/check
2. NU HTML validation: https://validator.w3.org/nu/
3. CSS validation: https://jigsaw.w3.org/css-validator/
4. JavaScript validation: Chrome > Developers Tools > Console (it checks syntax, it does not mean that the code is flawless)

#### Example of Recommendation

Figure 4.15.1 – URLs of full reports from HTML code validation.

| URL        | HTML Issues          | Test URL   |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 4.15.2 – URLs of full reports from CSS code validation.

| URL        | CSS Issues          | Test URL   |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

## 5. Content

### 5.1. Thin Content

#### Used Tools

1. Screaming Frog
2. Deduct words from header and footer from Screaming Frog word count

#### Instructions

Your pages contain an average of 417 words (Figure 5.1), but because a significant part of it consists of hidden duplicate content, the real figure is closer to half of this number. That means that many pages have only slightly more than 100 words.

We recommend adding more helpful content to these pages, and ensure they are at least 500 words in length. If your content is no better than pages that already rank for your targeted keywords, Google and Bing will unlikely show yours.

Figure 5.1 – A list of pages on your site and how many words were detected on each of them.

| URL        | Word Count (Total)          | Word Count (Main Content)   |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

#### Example of Recommendation

### 5.2. Internal Duplicate Content

#### Used Tools

- Siteliner > Duplicate Content
- Keep in mind that this tool isn't always accurate. For example, it may not know that you have ‘noindexed’ your category pages. So, it will likely classify those pages as duplicate content. Use your best judgement.

#### Instructions

We see a substantial amount of duplicate content on your pages, which means that the same content is repeated throughout a few pages on your site (Figure 5.2). It’s recommended to rewrite it and add more unique content to each page.

Figure 5.2 – A list of pages with duplicated content on your site and the percentage of text that is repeated on other pages of yours. 

| Hyperlink        | Match Words          | Match Percentage   |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

#### Example of Recommendation

### 5.3. External Duplicate Content

#### Used Tools

[Copyscape](http://www.copyscape.com/)
Or http://smallseotools.com/plagiarism-checker/
Or http://www.plagspotter.com/
Or http://www.copyscape.com/
All you need to do is file a DMCA report to Google and they will remove the content from the index.
Then you can check when that page was first archived on https://archive.org/
Do a search on Google for an exact match of the titles of the most popular pages on the site: intitle:”My page title”.

#### Instructions

We found a [PAGE B] page on [THIRD-PARTY WEBSITE URL]’S site where 20% of their words (110) match the content on your [PAGE B] page. This is not a big issue, as the portion of the content is not substantial and the [MAIN KEYWORD]is located in London. However, it would be good to rewrite this page to ensure your content is unique.

As a standard procedure we have highlighted the duplicated content in Figure 5.3.1 and Figure 5.3.2. In addition to this, we checked in the Internet Archive whether the content on this page appeared after the content on your page. The earliest presence of that content was documented on April 19, 2014 (Figure 5.3.3). Unfortunately, we were unable to determine when this content first appeared on your site.

We have not found sites that would use the content of your Home and [PAGE A] pages.

Figure 5.3.1 – A screenshot of the page whose content matches your page.
Figure 5.3.2 – A screenshot of your page that could potentially be used by other sites.
Figure 5.3.3 – A screenshot of the page that matches content on your page from April 19, 2014.

#### Example of Recommendation

### 5.4. Keyword Cannibalization

#### Used Tools

1. Screaming Frog > Page Titles tab > Enter one of your main keywords into the search bar. Look through your page titles and identify pages that may be competing for the same keywords.
2. Screaming Frog > H1 tab >
3. Google Search Console > One thing to look for in general is if more than one page is targeting or showing up in the search results for the same keyword (aka ‘keyword cannibalization’).

#### Instructions

#### Example of Recommendation

Great, we did not detect any major issues with keyword cannibalisation on your site.

### 5.5. Related Keywords

#### Used Tools

#### Instructions

#### Example of Recommendation

We analysed keywords that Google thinks are relevant to your brand (Figure 5.8). By looking at the ones for which your pages rank low, you can identify user queries for which you have a chance to improve ranking with a dedicated page or more optimised one.

Here are a few keywords you could consider including to optimise your content or create new pages with these keywords, to improve your ranking:
- Live [PAGE A] Dublin
- Live [MAIN KEYWORD] Dublin

Figure 5.8 – A list of queries your pages have ranked for during the past 90 days on Google.

| Queries        | Clicks          | Impressions   | CTR   | Position   |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder | placeholder | placeholder |

### 5.6. Hints & Tips or How-To Content

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.7. Fresh Content

#### Used Tools

#### Instructions

New content added regularly?
Existing content updated from time to time?
Does the site have a blog, and new content is added very regularly?

#### Example of Recommendation

Your site does not have enough helpful content for its users, except for sales-focused information about what services your business offers and where it is located. Consider running a survey among your customers to find out what other information they would like to see on your site.

### 5.8. Content Pruning

#### Used Tools

- Google Search Console > Search Traffic > Internal Links (Google traffic only)
- Bing Webmaster Tools

#### Instructions

#### Example of Recommendation

Because of the recent transition of your site to HTTPS and there not being enough data available on the HTTP version of your site, we will focus here on information regarding the HTTP version of your website.

Many of your pages shown in the search results did not receive a single click during the previous 90 days (Figure 5.11). You should consider de-indexing the pages that you are not interested in getting ranked and adding value to those in which you are.

Figure 5.11 – A list of pages on your site and the number of times a user clicked on it during the last 90 days.

| URL        | Clicks          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 5.9. Content Ideas

#### Used Tools

1. SEMrush > Keyword Analytics > Phrase Match
2. SEMrush > Keyword Analytics > Related Keywords

#### Instructions

#### Example of Recommendation

In Figure 5.7, we listed 170 types of queries around the keyword ‘[KEYWORD C]’ for which it may make sense for your business to focus on ranking higher. We then sorted these from the easiest to most difficult in terms of ranking well for each keyword. In addition, we included metrics like the number of monthly searches of these keywords (Search Volume), estimated cost per click of an ad shown for that query (CPC), popularity of the query among advertisers (Competition) and the number of results found for it.
Here are some related keywords that may be worth optimising on your site:
- Micro-gaming [MAIN KEYWORD]
- Best [MAIN KEYWORD] offers
- Sign up [MAIN KEYWORD] bonus
- [MAIN KEYWORD] no deposit

We notice that 140 people each month are searching for ‘[COMPETITOR BRAN NAME] [PHRASE A]’ and nobody is bidding with PPC ads for that keyword. These are people who most likely want to visit a local [MAIN KEYWORD]. If you don’t mind using more aggressive marketing tactics, you could test bidding on your competition branded keywords.  

Figure 5.7 – A list of popular queries around your primary keyword with information on how competitive they are.

| Keyword        | Search Volume          | Keyword Difficulty Index   | CPC   | Competition   | Number of Results   |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder | placeholder | placeholder | placeholder |

### 5.10. Internal Search Queries

#### Used Tools

Google Analytics > Behaviour > Site Content > All Pages

#### Instructions

#### Example of Recommendation

The below list outlines some of the searches users have performed on your site (Figure 5.10), with our recommendations alongside them:
- ‘[PAGE B]’, ‘[PAGE A]’, ‘[PAGE C]’ – you should consider placing links to these pages on your homepage.
- ‘Jobs’, ‘vacancies’, ‘carrier’ – consider creating a Carrier page, for those who would like to work in your business.
- ‘Address’ - your address should be added to your contact page.
- ‘Opening hours’, ‘Open hours 5 January’ – Opening hours are not prominent enough, you should add them to your Contact page and to the footer of each page.
- ‘Gift voucher’ – information on whether you allow customers to purchase Gift Vouchers should be added to your site. They could be a great way of bringing new customers to your business.
- ‘Menu’ – you should consider adding information on whether you serve food and if so, what food is available.
- ‘Bar’ – information on your bar should also be more prominent.

Including the above information on your website could attract more people to your casino.

Figure 5.10 – A list of what users have searched your site for during the past 90 days. 

| Page        | Page Views          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 5.11. Queries for Which Your Images Rank

#### Used Tools

Google Search Console >
Bing Webmaster Tools >

#### Instructions

#### Example of Recommendation

We notice that not all images on your site are optimised to rank well in an Image Search (Figure 5.11.1). We recommend using the prepared list of queries for which your images are already shown in search (Figure 5.11.2) by rewriting their file names, Alt text, title and description to help them rank higher.

Figure 5.11.1 – A list of the URLs of the images on your site, the pages where these images are shown and the Alt texts.

| Source        | Image URL          | Alt Text          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 5.11.2 – A list of queries where your images have ranked during the past 90 days on Google.

| Queries        | Clicks          | Impressions          | CTR          | Position          |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder | placeholder | placeholder |

## 6. Local

### 6.1. Country Targeting

#### Used Tools

1. Google > Search Traffic > International Targeting > Country

   https://www.google.com/webmasters/tools/i18n

2. Bing Webmaster Tools > International Targeting

#### Instructions

#### Example of Recommendation

You haven’t specified any country that is important to your business with Google’s International Targeting and Bing’s Geo-Targeting tools.

### 6.2. Geo-Focused Keywords

#### Used Tools

#### Instructions

#### Example of Recommendation

None of your pages contain your location in the title (Figure 6.2.1) or in the text of your internal links (aka anchor text) (Figure 6.2.2), and it is rarely repeated on your pages. 
Fixing this will send a clearer signal to searchers and Google that your pages are very relevant to people based in Dublin, improving your ranking in this area.

Figure 6.2.1 – A list of your pages and their titles.

| URL        | Title          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 6.2.2 – A list of internal links on your site with their anchor texts.

| Source        | Destination          | Anchor text          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 6.3. Business Name, Address, Phone (NAP)

#### Used Tools

#### Instructions

#### Example of Recommendation

You have your business contact information placed on all pages, but it could be improved in terms of consistency, formatting and with the addition of opening hours information, which we highlighted in Figure 6.3.

Furthermore, this information should be marked-up with Schema to make your company’s contact information crystal clear to the search engines.

Figure 6.3 – Recommended changes to the business name, address and phone number (NAP) section on your site, highlighted in red.

| Current NAP information        | Recommended NAP information          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 6.4. Google My Business

#### Used Tools

#### Instructions

1. https://synup.com/tools/google-checker/
2. Manually check
a. Is listing verified?
If the listing has an “own this business” or “claim this business” option, it is not currently verified.
b. Details
i. Address
ii. Phone number
iii. Opening hours
iv. Correct website address
v. Etc.
c. Photos
d. Picked categories. Could they be more specific?
e. Position on map
f. Attributes
g. Google My Business Posts usage

#### Example of Recommendation

Google Maps shows that your business is located within a different building to where you are actually based (Figure 6.4.1). This will confuse some searchers and may cost you business. You should correct this and monitor the details displayed on your profile once a month, as other users or the competition are able to submit incorrect information about your business to Google.
Furthermore, on your profile there is still a link to an old HTTP version of your site address (Figure 6.4.2), which will result in your site taking longer to load and may devalue some ranking signals. This should be fixed.
All other information is correct.

Feature 6..1 – Incorrect location of [BRAND NAME] displayed on Google Maps.

Feature 6.4.2 – Your ‘Google My Business’ points to an unsecure version of your site.

### 6.5. Local Citations

#### Used Tools

1. Current Citations
Check on each directory:

- Business name – is it exactly the same on each listing?
- Address – is it correct?
- Map – does it point to the entrance of the store?
- Website – check if the backlink points to the correct version of the site (HTTP, HTTPS, WWW, not-WWW)
- Review – is there a review?
- Photos – are presentable photos available?

2. Citations that should be created
3. Citations that competitors have, and you don’t

#### Instructions

#### Example of Recommendation

We notice many inconsistencies currently occur across your business listings on local citations (Figure 6.8), which may confuse users and the search engines.
It’s best to use the same company name everywhere on the Internet. We notice there are a few variations of your business name:
- [BRAND NAME 2]
- [BRAND NAME + MAIN KEYWORD]
- [BRAND NAME + LOCATION]
- [BRAND NAME] LIMITED
The address of your business is often incomplete.
Maps should be showing users the entrance to [BRAND NAME], as it will make it easier for them to find you. However, often the pin is located in either the middle of the building, a nearby building, the middle of the street, a nearby street or a different part of the neighbourhood. 
Additionally, some of your listings lack or have a low number of customer reviews. It’s always worth asking your users, via email or in person, to leave you a review. Positive reviews help your business to rank higher and encourage other searchers to visit your website. 

Figure 6.5 – A list of business directories on which your company is listed, and whether the information presented is consistent.

| Directory Site        | Business Name          | Address          | Phone          | Website          | Location on a Map          |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder | placeholder | placeholder | placeholder |
| [DIRECTORTY LISTING URL]     | [BRAND NAME] | ADDRESS] | [PHONE NUMBER] | [WEBSITE URL] | incorrect/correct |

### 6.6. Bing Places for Business

#### Used Tools

#### Instructions

Search for the business’ name on Bing

#### Example of Recommendation

Unfortunately, this tool is still not available for businesses in Ireland. We will let you know once it is.

### 6.7. Apple Maps

#### Used Tools

#### Instructions

#### Example of Recommendation

There is an incorrect version of your site’s address displayed on Apple Maps (Figure 6.7). It’s important that your domain is consistent on all third-party websites that link to you. This way, you can ensure the whole ranking value is carried over and does not confuse your users.

In addition to this, the image that is currently displayed should be updated, as many people will make a decision based on this, whether they want to visit your business or not.
We notice that the address listed as [ADDRESS], appears to be different than displayed on your website. The position of the pin on the map needs to be updated to reflect the location of the entrance to your building.

The above issues should be fixed to increase the number of customers who navigate to your website from Apple Maps.

Figure 6.7 – Information about your business in Apple Maps.

### 6.8. Reviews

#### Used Tools

#### Instructions

#### Example of Recommendation

Your customers have left your business 122 reviews across several sites (Figure 6.9). However, the majority of these reviews are on Facebook. You should try to ask your customers to share their experience at your [MAIN KEYWORD] on Google, TripAdvisor or Yelp. There are also a few sites on which you do not have any reviews, such as Euan’s Guide and [MAIN KEYWORD] Avenue. You should try to encourage customers to leave reviews on each of these sites, preferably asking them via email or in person.
Figure 6.9 – A list of local citations on which your customers have left or could leave you a review.

| URL        | Number of Reviews          | Average Rate          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 6.9. Responses to Reviews

#### Used Tools

#### Instructions

#### Example of Recommendation

You are responding to customer reviews, but you have not engaged with all of them. This is your opportunity to build stronger relationships with customers who are passionate enough about your business to leave you a review.

### 6.10. Server Location

#### Used Tools

https://www.site24x7.com/find-website-location.html

Google Analytics

#### Instructions

#### Example of Recommendation

Great, the server that you use is located in Dublin, Ireland where 65% of your users live (Figure 6.2).

Figure 6.2 – A list of countries with the number and percentage of people visiting your site from that geographic location.

| Country        | Number of Users          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 6.11. Physical Web

#### Used Tools

#### Instructions

#### Example of Recommendation

We notice your business is not taking advantage of what The Physical Web has to offer. Consider using it to give new visitors to your [MAIN KEYWORD] faster access to information on how to play specific games available or to inform them of your current deals.

## 7. Off-Site

### 7.1. Referring Domains

#### Used Tools

#### Instructions

Check backlinks to all the versions of the domain name (e.g. HTTP, HTTPS, WWW, non-WWW) and all previous domains used by the business.
1. Google Search Console > Search Traffic > Links to Your Site
2. Bing Webmaster Tools > 
3. SEMrush > Domain Analytics > Backlinks
4. Open Site Explorer
5. Majestic
6. Domains linking to your competitors but not you
7. Ahrefs
Evaluate backlinks 
https://ahrefs.com/batch-analysis
or URLProfiler
Crawl historical backlinks and search on those pages for your domain, as some of those pages may still be linking to you.
Characteristics of potentially spammy domains
- Are at least 45 characters’ long
- contain at least 6 dots
- contain at least 5 dashes
- contain at least 10 digits
Source: http://www.std.org/~msm/common/SpamDamnSpam.pdf

#### Example of Recommendation

We have identified 42,853 backlinks to your site, on 4,002 pages from 115 domains (Figure 7.1). We have calculated a Domain Authority of these websites and reviewed those with a score lower than 30, as this suggests that the site may not be very reliable. We notice that ‘nvgindex.com’ does not look entirely trustworthy, and you should consider disavowing it.
Figure 7.1 – A list of sites linking to you and their Domain Authority.

| Referring Domain        | Domain Authority          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 7.2. Referring Pages (aka Backlinks)

#### Used Tools

#### Instructions

1. Verify if backlinks are still on these pages
a. Screaming Frog > Mode > List > Upload your list of backlinks and run the spider in ‘List’ mode. Then, export the full list of outbound links by clicking on ‘All Out Links’ in the ‘Advanced Export Menu’. This will provide you with the URLs and anchor text/alt text for all links on those pages. You can then use a filter on the ‘Destination’ column of the CSV to determine if your site is linked and what anchor text/alt text is included.
b. Check do destination links point to clients site
2. Check does the backlink point to the right version of the site (HTTP, HTTPS, WWW, not-WWW)
3. Number of backlinks from each page
Excel > Insert > Pivot table > Row (source) and Value (destination)
4. Number of backlinks from a domain
In Excel 
a. =LEFT(B4,FIND(‘/’,B4,9))
b. then replace with nothing
i. www
ii. http://
iii. https://
5. Link Detox (DTOX) – it automatically reviews and categorises backlinks

#### Example of Recommendation

We reviewed domains from which your site receives most links from (Figure 7.2.1), and pages that are most often linked to you (Figure 7.2.2). We notice that ‘[THIRD-PARTY SITE]’ links to your site 41,349 times, which may suggest search engines that your site uses spam-like practices in order to manipulate your ranking. 
To comply with Google’s regulations, you should: 
1. Add a nofollow attribute to links in ads on the following domains
a. ‘[THIRD-PARTY SITE]’
b. ‘[THIRD-PARTY SITE]’
2. Disavow domains with many low-quality links to
a. ‘[THIRD-PARTY SITE]’
Figure 7.2.1 – A list of domains, and the number of times they link to your site.

| Domains        | Number of backlinks          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 7.2.2 – The 4,002 pages linking to you, and the number of backlinks you received from each of these pages. Due to the high number of links, we have included them in a Google Sheets file.
[LINK TO DATA BASE]

### 7.3. Link Targeting

#### Used Tools

#### Instructions

#### Example of Recommendation

When you look at the pages your backlinks point to (Figure 7.3.2), it appears as though your site has a well-distributed number of links across all of your important pages, such as Home, [KEYWORD D], [PAGE B] and [PAGE A]. However, when we exclude links from the [THIRD-PARTY SITE] domain, we see that nobody links to your key pages, except from your homepage and a few links going to your [KEYWORD D] page (Figure 7.3.3).
You should focus on ways to earn backlinks to your [KEYWORD D], [PAGE B] and [PAGE A] pages to help them rank higher in search results.
Figure 7.3.1 – The 42,853 backlinks to your site, and pages to which they link to. Due to the high number of links, we have included them in a Google Sheets file.
[LINK TO DATA BASE]

Figure 7.3.2 – A list of the most frequently linked pages on your site with the number of times they are pointed to. 

| Most Linked Page        | Number of Occurrences          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 7.3.3 – A list of the most frequently linked pages on your site, and the number of times they are pointed to. We excluded links from the ‘[THIRD-PARTY SITE]’ domain.

| Row Labels        | Count of Links          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 7.4. Broken Backlinks

#### Used Tools

#### Instructions

Two types of tools are great for finding broken backlinks — Google Search Console, and a backlink checker such as Moz, Majestic, or Ahrefs.
Also look for broken links because the linking site typed in your URL wrong or messed up the link code on their end, this is another rich source of link opportunity

#### Example of Recommendation

Some sites link to your old pages and domains that are no longer used by you (Figure 7.4). This causes you to lose some of the ranking signals, which could otherwise have improved the position of your site in search results.
Here is a list of your pages and domains to which other sites still link to:
- http://[WEBSITE ADDRESS]/home/registration-form.104.html
- http://[WEBSITE ADDRESS]/contactus.aspx
You should consider redirecting them to the new versions of these pages or pages that are more relevant (except for http://www.[OLD WEBSITE ADDRESS]/). We are able to identify 150 pages that link to this domain, but the majority of them do not look trustworthy. Before redirecting this domain to the new one, taking a closer look at old backlinks is required, including a clean-up of them. 
Figure 7.4 – A list of backlinks to your old domain.

| Source        | Destination          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 7.5. Anchor Texts

#### Used Tools

#### Instructions

1. Screaming Frog > Mode > List
2. Categorise Anchor texts into:
- Branded (around 65%) – any anchor text with your company name
- Naked links (around 20%) – those with a raw URL, e.g. example.ie, https//www.example.ie
- Generic (around 5%) – Usually with call to action, e.g. click here, go here, website etc.
- No anchor – usually in images
- Image anchor – if your image is a link, alt text becomes an anchor text
- Brand + keyword anchor (around 2%) – combined a brand name and a target keyword
- LSI (Latent Semantic Indexing) (around 2%) – these are variations and synonymous of your main. To identify them you can use Search Autosuggestions or ‘Searches related to ___’ at the bottom of the search results.
- Partial-Match Anchors (around 1%) –
- Long Anchors (around 2%) – 6+ words in the anchor text with your important keyword
- Exact Match Anchors (around 1%) – exact much of your main keyword
Usually, the more divers you anchor text profile the better.

#### Example of Recommendation

We reviewed what other sites say about your pages when linking to them (Figure 7.5.1 and Figure 7.5.2). 74 times out of 100, the backlinks contained your important keywords. While only 2 out 100 used your company’s name when linking to you. This is a very dangerous situation to be in, as this does not look natural, and when discovered by Google or Bing, may reduce your ranking position if it has not done so already.

However, when we excluded links from ‘[THIRD-PARTY SITE]’ (Figure 7.5.3 and Figure 7.5.4), everything changed. Now, only 1% of anchor and alt texts contain your keyword, 56 times out of 100 a site use your business name in the backlink. Which is a much safer ratio. We advise you add more links with exact-match anchors to help you rank higher.

We recommend you disavow links on ‘[THIRD-PARTY SITE]’, which will tell the search engines that you do not want those backlinks to be associated with your site.

Figure 7.5.1 – A list of anchor texts with the number of times they were used in the links. We also included translations for the anchor texts that are in a different language than English.

| Category        | Alt & Anchor texts          | Number occurrences          | Translation          |
| ------------- | ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder | placeholder |

Figure 7.5.2 – Anchor and alt text categories, together with the number of their occurrences.

| Categories        | Number of occurrences          | Percentage          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 7.6. Online Mentions

#### Used Tools

#### Instructions

1. Ahrefs
2. SEMrush
3. MOZ > Open Site Explorer > Link Opportunities (left sidebar) > Unlinked Mentions (tab)
4. Mentions of your competitors but not you
5. Google
“founder name” OR “company name” OR “companyname” OR “branded product/service name” –site:domainname
Check company’s name, alternative names, branded products and services and website address which is a plan text.
Here are some specific search queries you can try using:
- [My Name] – to track the mentions of your name.
- [My Company Name] – to monitor the company name mentions (reviews, forum posts, etc)
- [mycompanyname.com] – to monitor the domain name mentions; some of the backlinks can also be discovered that way…
Google Alerts is just one (admittedly best-known) tool to monitor your brand online. There are more, better tools:
- [Brand Mentions](https://brandmentions.com/) is a newer tool sending you daily email digests with your brand mentions
- https://mention.com
- [Buzzsumo](http://buzzsumo.com/) is a great tool allowing you to set up multiple alerts to monitor your online mentions
- [Hooks](https://play.google.com/store/apps/details?id=com.hooks.android&hl=en) is a mobile app allowing you to set up alerts to monitor your brand mentions on the go.
- [BestAndroidApps](http://bestandroidapps.com/) [offers a good tutorial](http://bestandroidapps.com/how-to-set-up-alerts-for-almost-everything-with-the-hooks-app/) on how to set up mobile alerts using the app.

#### Example of Recommendation

We notice 92 pages that mention your business name but do not link to your website. 20 of these pages would be worth contacting to request a backlink added (Figure 7.6). You should try contacting these sites to check if there is a possibility to add a backlink that points to your website on those pages. 
Figure 7.6 – A list of pages that mention your brand name, which may be worth adding a backlink.
URL Domain Authority

| URL        | Domain Authority          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 7.7. Disavow File

#### Used Tools

#### Instructions

Google: https://www.google.com/webmasters/tools/disavow-links-main
Bing: ?
Check formatting of the disavow file

#### Example of Recommendation

We have not found any issues with your disavow files.

### 7.8. Branded Search Query Results

#### Used Tools

#### Instructions

1. Search for company’s name, branded products and services
2. Check whether they control all pages on page one of search results, and if these pages leave readers with a positive view of the company.

#### Example of Recommendation

Google shows [BRAND NAME] Online in position 5 for your brand name (Figure 7.8.1), which is an online ski shop. While Bing displays the Vision-net page for your brand in position 6 (Figure 7.8.3 and Figure 7.8.4), which you do not have control over.

You should consider boosting the ranking positions of your social media accounts and business listings to push these pages below the first page of the search results.

Figure 7.8.1 – A screenshot of the Google search results for the query ‘[BRAND NAME]’.

Figure 7.8.2 – A screenshot of the Google search results for the query ‘[BRAND NAME 2]’

Figure 7.8.3 – A screenshot of the Bing search results for the query ‘[BRAND NAME]’.

Figure 7.8.4 – A screenshot of the Bing search results for the query ‘[BRAND NAME 2]’.

### 7.9. Search Autocomplete

#### Used Tools

#### Instructions

Bulk Search Autosuggest Tool - http://tools.seochat.com/tools/suggest-tool/
Label interesting keywords that require an action:
- Create new content to target this keyword
- Create a new section on the site targeting this keyword or the group of keywords
- Make a section of your site or a web page more visible (Something that would help users to easier find it)
- Launch a new feature / product / service that would cover a need your competitor isn’t covering
- Look for phrases containing the following and similar words:
  - Security
  - Scam
  - Spam
  - Returns
  - Alternatives
  - Refund
- Moreover, the following words can suggest frequent tech problems, which may prevent your customers from using your site:
- Down
- Slow
- Malware
- Downtime (You may want to keep an eye on this page to avoid seeing people complain about your site performance)
- Report offensive autocompletes https://support.google.com/websearch/answer/106230?hl=en

#### Example of Recommendation

There are no negative search autocomplete suggestions for your brand name (Figure 7.9.1 and Figure 7.9.2). We notice questions about ‘dress code’ and ‘jobs’ being searched by users on Google. You should consider creating pages on these topics to make it easier for searchers to find what they are looking for.

Figure 7.9.1 – A list of Search Suggestions from Google that are shown for your brand name.

| Search Suggestion        | Note          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 7.9.2 – A list of Search Suggestions from Bing that are shown for your brand name.

| Search Suggestion        | Note          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 7.9.3 – A list of Search Suggestions from YouTube that are shown for your brand name.

| Search Suggestion        | Note          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 7.9.4 – A list of Search Suggestions from Amazon that are shown for your brand name.

| Search Suggestion        | Note          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 7.10. Mostly Shared Pages

#### Used Tools

URLProfiler > Social Shares

#### Instructions

#### Example of Recommendation

We notice that your pages are rarely shared on social media (Figure 7.8). You should promote them regularly to increase brand awareness and recall among your target audience.
Figure 7.8 – A list of pages on your site and the number of times links to them appear on social media.

| URL        | Facebook          | LinkedIn          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 7.11. Site Neighbourhood

#### Used Tools

1. Do revers lookup with http://viewdns.info/reverseip/
2. Check DA and PA of domains hosted on the same server with http://www.seoweather.com/bulk-metrics-checker/ 

   Double check sites with score 0. NEEDED A BETTER TOOL!

#### Instructions

#### Example of Recommendation

We found only one different domain ([THIRD-PARTY WEBSITE]) associated with your server (Figure 7.11). However, it redirects to your main website, and we did not detect any problematic backlinks which could lead to your site through this domain. Everything looks fine.

Figure 7.11 – List of domains hosted on the same server as yours.

| Domain        | Domain Authority          | Page Authority          | Spam Score          |
| ------------- | ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder | placeholder |

## 8. Competitor Analysis

### 8.1. Search Visibility

#### Used Tools

SEMrush > Project > Position Tracing

#### Instructions

#### Example of Recommendation

We have collected a list of top 100 keywords from your industry (Figure 8.1.1) to identify which are the best performing websites for these keywords (Figure 8.1.2).
If you were to rank in first place for all 100 keywords, then the maximum monthly traffic from them would equal 1,220,592 clicks and new visitors to your site.
We notice that the most prominent domain currently ranking the highest for these keywords is ‘[COMPETITOR WEBSITE]’, with an estimated visibility of around 63% (Figure 8.6). Your domain has the second highest search visibility among 12 identified local [MAIN KEYWORD] with a score of around 16%. 
It would be wise to conduct a separate audit of [COMPETITOR BRAND NAME] site, as they have established what the search engines require for their users. This may help you better understand the key differences between your sites.

Figure 8.1.1 – A list of top 100 keywords for your industry.

| Keywords        |
| ------------- |
| placeholder     |

Figure 8.1.2 – A diagram with the most visible competitor’s websites for your most important keywords.

Figure 8.1.3 – A list of the most visible competitor’s websites for your most important keywords.

### 8.2. Referring Domains

#### Used Tools

#### Instructions

#### Example of Recommendation

For the query ‘[PHRASE A], [COMPETITOR BRAND NAME] has 161 referring domains to their homepage, which is twice as many as you have (Figure 8.2.1). The average number is 41. You need to work on earning backlinks from more domains.

For the query ‘[WORD B]’ and ‘[PAGE A]’, the average number of linking domains to pages for positions 2-9 is 43 and 25 respectively (Figure 8.2.2 and Figure 8.2.3). [COMPETITOR BRAND NAME] page that ranks for ‘[WORD B]’ has only 1 referring domain that we know of, and it may be relatively easy for you to steal this position from them, if you are able to build more backlinks from various authoritative domains.

Figure 8.2.1 – A list of pages that rank for the query ‘[PHRASE A], and the number of domains linking to them.

| Position        | URL          | Domains          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.2.2 – A list of pages that rank for the query ‘[WORD B]’, and the number of domains linking to them.

| Position        | URL          | Domains          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.2.3 – A list of pages that rank for the query ‘[PAGE A]’, and the number of domains linking to them.

| Position        | URL          | Domains          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 8.3. Referring Pages (aka Backlinks)

#### Used Tools

#### Instructions

#### Example of Recommendation

For the query ‘[PHRASE A], your website has around 40% more pages linking to you than to the page ranking 1st ([COMPETITOR BRAND NAME]) (Figure 8.3.1). However, as we explained in section 7.2 of the report, most of your backlinks come from one site, which may be damaging your ranking.

For the query ‘[WORD B]’, pages with position 2-9 have an average of 259 backlinks, while position 1 has 13,623 backlinks (Figure 8.3.2). However, a [COMPETITOR BRAND NAME] page on this topic list at position 4, has only 1 backlink. This creates an opportunity for you to take this spot from them if you improve your page quality, as well as cleaning the low quality and spammy backlinks we talked about in section 7.2 of this report.

For the query ‘[WORD B]’, pages with position 2-9 have an average of 53 backlinks, while position 1 (a page from Wikipedia) has 7,762 backlinks (Figure 8.3.3). The other two informative pages have an average of 103 links pointing to them. To rank for this keyword, you will need to improve the quality of your ‘[WORD B]’ page and earn more genuine backlinks than your competition. 

Figure 8.3.1 – A list of pages that rank for the query ‘[PHRASE A], and the number of pages linking to them.

| Position        | URL          | Total Backlinks          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.3.2 – A list of pages that rank for the query ‘[WORD B]’, and the number of pages linking to them.

| Position        | URL          | Total Backlinks          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.3.3 – A list of pages that rank for the query ‘[PAGE A]’, and the number of pages linking to them.

| Position        | URL          | Total Backlinks          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 8.4. Type of Content

#### Used Tools

1. In Incognito Window search for client keywords
2. Check websites’ categorisation - https://www.similarweb.com/

#### Instructions

#### Example of Recommendation

For the keyword ‘[PHRASE A], the search results page features 7 local business (two of these sites belong to [COMPETITOR BRAND NAME]) and 3 directories with local businesses (two industry-specific directories) (Figure 8.4.1). In addition to this, we notice that the location of your business on ‘[COMPETITOR WEBSITE]’ is not accurate. We recommend correcting this.

For the keyword ‘[WORD B]’, the search results page features 6 pages with online or mobile [PAGE B] games and 3 pages with information on how to play [PAGE B] (Figure 8.4.2). You can increase your chances of ranking for this keyword by ensuring your page is more detailed and helpful for people who would like to learn how to play this game.

For the keyword ‘[PAGE A]’, the search results page features 6 pages with online [PAGE A] games and 3 pages with information on how to play [PAGE A] (Figure 8.4.2). As with [PAGE B], you should improve the quality of your [PAGE A] page by adding more helpful information on how to play this game.

Figure 8.4.1 – A list of pages that rank for the query ‘[PHRASE A], and what type of pages they are.

| Position        | URL          | Type of Page          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.4.2 – A list of pages that rank for the query ‘[WORD B]’, and what type of pages they are.

| Position        | URL          | Type of Page          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.4.3 – A list of pages that rank for the query ‘[PAGE A]’, and what type of pages they are.

| Position        | URL          | Type of Page          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 8.5. Keyword in Title

#### Used Tools

#### Instructions

#### Example of Recommendation

For the query ‘[PHRASE A], 4 out of the 5 top pages have both the words ‘[KEYWORD C]’ and ‘Dublin’ in their title (Figure 8.5.1). Your page is the only one from those five that didn’t contain these two words within the title. You should fix this.

For the queries ‘[WORD B]’ and ‘[PAGE A]’, all pages contain the targeted keyword in the title except for one (Figure 8.5.2 and Figure 8.5.3), and only a few of them contain just one or two words, like your pages. You should change your titles to more descriptive ones.

Figure 8.5.1 – A list of pages that rank for the query ‘[PHRASE A], and the titles they use.

| Position        | URL          | Title          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.5.2 – A list of pages that rank for the query ‘[WORD B]’, and the titles they use.

| Position        | URL          | Title          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.5.3 – A list of pages that rank for the query ‘[PAGE A]’, and the titles they use.

| Position        | URL          | Title          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 8.6. Content Length

#### Used Tools

#### Instructions

#### Example of Recommendation

For the query ‘[PHRASE A], the average length of the content on ranked pages is 777 words (Figure 8.6.2). Your page contains only 379 words. Therefore, you should expand your content by adding more helpful information on your [MAIN KEYWORD] and what you can do inside.

For the query ‘[WORD B]’, the average length of content on ranked pages is 2,649 words, with the Wikipedia page ranking 1st with an 8,321-word page (Figure 8.6.2). Your [PAGE B] page contains 549 words. You should expand on the information that you currently have there.

For the query ‘[PAGE A], the average length of content on ranked pages is 1,785 words, with the Wikipedia page again ranking 1st with a 9,847-word page (Figure 8.6.3). Your [PAGE A] page contains 649 words. Again, you should add more quality content to this page in order to rank for this query.

Figure 8.6.1 – A list of pages that rank for the query ‘[PHRASE A], and the number of words detected on these pages.

| Position        | URL          | Word count          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.6.2 – A list of pages that rank for the query ‘[WORD B]’, and the number of words detected on these pages.

| Position        | URL          | Word count          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.6.3 – A list of pages that rank for the query ‘[PAGE A]’, and the number of words detected on these pages.

| Position        | URL          | Word count          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 8.7. Search Ads History

#### Used Tools

SEMrush > Keyword Analytics > Ads History

#### Instructions

#### Example of Recommendation

While many sites compete for an opportunity to show ads for keywords like ‘[KEYWORD C]’ (Figure 8.7.1), ‘[WORD B]’ (Figure 8.7.3) and ‘[PAGE A]’ (Figure 8.7.4), not many of them show ads for location-specific queries like ‘[PHRASE A] (Figure 8.7.2). We also did not find any data on advertisers bidding for ‘[PAGE B] Dublin’ or ‘[PAGE A] Dublin’. 
Your business could use this opportunity to show ads in searches above your competition for a relatively low cost-per-click, as there are not many, if any, advertisers competing for this space. You could start by showing ads inviting searchers, who are near to the locations of you or your competitors, to visit your business.

Figure 8.7.1 – A list of advertisers that have been displaying ads on Google during the past 12 months for the keyword ‘[KEYWORD C]’, and the number of ads run by them.

Figure 8.7.2 – A list of advertisers that have been displaying ads on Google during the past 12 months for the keyword ‘[PHRASE A], and the number of ads run by them.
 
Figure 8.7.3 – A list of advertisers that have been displaying ads on Google during the past 12 months for the keyword ‘[WORD B]’, and the number of ads run by them.

Figure 8.7.4 – A list of advertisers that have been displaying ads on Google during the past 12 months for the keyword ‘[PAGE A]’, and the number of ads run by them.

### 8.8. Search Ads Data

#### Used Tools

SEMrush > Keyword Analytics > Ads History > Export

#### Instructions

#### Example of Recommendation

Use below examples of ads for keyword ‘[KEYWORD C]’ (Figure 8.8.1), ‘[PHRASE A] (Figure 8.8.2), ‘[WORD B]’ (Figure 8.8.3) and ‘[PAGE A]’ (Figure 8.8.4) to further optimise titles and descriptions of your key pages. This especially goes for your [PAGE B] and [PAGE A] pages, which currently have only one word. Furthermore, consider creating similar ads for your business.

Figure 8.8.1 – A list of ads that were displayed on Google during the past 12 months for the keyword ‘[KEYWORD C]’.

| Position        | URL          | Description          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.8.2 – A list of ads that were displayed on Google during the past 12 months for the keyword ‘[PHRASE A].

| Position        | URL          | Description          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.8.3 – A list of ads that were displayed on Google during the past 12 months for the keyword ‘[WORD B]’.

| Position        | URL          | Description          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

Figure 8.8.4 – A list of ads that were displayed on Google during the past 12 months for the keyword ‘[PAGE A]’.

| Position        | URL          | Description          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 8.9. Engagement

#### Used Tools

#### Instructions

Average sites metrics from:
- http://www.alexa.com/siteinfo
- https://www.similarweb.com/

#### Example of Recommendation

A list of competitors with their site’s engagement metrics compared to yours.

| Domain        | Bounce Rate          | Daily Page views per Visitor          | Daily Time on Site per Visitor         |
| ------------- | ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder | placeholder |
