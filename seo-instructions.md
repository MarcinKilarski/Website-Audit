# Instructions for Search Engine Optimisation (SEO) Audit Report

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
    Export your results to a CSV, then load the CSV into Screaming Frog using ‘List’ mode. Once the spider has finished running, you’ll be able to see status codes, as well as any links on the subdomain home pages, anchor text and duplicate page titles among other things.
4. Ask the client about other subdomain, domain, printed resources, digital resources and internal materials that weren't published on the main domain.

#### Instructions

#### Example of Recommendation

Great, we haven't found any content that doesn't live on your main domain.

### 1.5. Internal Links

#### Used Tools

1.	Check which internal links Google sees
Google Search Console > Search Traffic > Internal Links
2.	Calculate PR of internal pages
3.	Consolidate HTTP and HTTPS links
4.	Internal: follow
5.	Internal: nofollow
6.	Check orphaned pages

#### Instructions

#### Example of Recommendation

Your home page receives the highest number of incoming internal links ([# of links]), increasing its chance to rank well in a search. However, [page X and page Y] pages, for which you would like to improve the ranking, receive only 26 incoming internal links each. 

You should consider adding more links on your site that point to these pages. Creating more pages with helpful content related to [PAGE X and PAGE Y] could be a great way of doing this.

Figure 1.5 – A list of all your pages and the number of links on your site that point to them.

### 1.6. Keywords in Internal Links

#### Used Tools
Screaming Frog > Bulk Export > All Outlinks
Clean up data by filtering out any external sites

#### Instructions

#### Example of Recommendation

None of the internal links from pages on your site, pointing to your home page, use your primary keyword ‘[KEYWORD X]’ (Figure 1.9.1). We recommend changing the alt text of your business logo image from ‘[X]’ to ‘[Y]’, as this will help increase the relevance of your page for the query ‘[KEYWORD Y]’.

Links to your [PAGE Y] and [PAGE Z] pages contain the primary keyword ‘[KEYWORD Y]’ or ‘[KEYWORD Z]’, but you also should consider linking from other places on your site with secondary keywords like ‘[KEYWORD YY]’ or ‘[KEYWORD ZZ]’ in the anchor text. This way you will increase their chances of ranking for these keywords in the search.
Figure 1.10.1 – A list of incoming internal links pointing to your home page, and all anchor and alt texts used in them.
| Source | ALT text | Anchor text|
| --- | --- | --- |
| | | |

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Figure 1.10.2 – A list of incoming internal links pointing to your [PAGE Y] page, and all anchor and alt texts used in them.
| Source | ALT text | Anchor text|
| | | |

Figure 1.10.3 – A list of incoming internal links pointing to your [PAGE Z] page, and all anchor and alt texts used in them.
| Source | ALT text | Anchor text|
| | | |

### 1.7. Orphan pages

#### Used Tools

#### Instructions

#### Example of Recommendation

### 1.8. User Generated Content

#### Used Tools

#### Instructions

#### Example of Recommendation

### 1.9. Preferred Domain

#### Used Tools

#### Instructions

#### Example of Recommendation

### 1.10. Site Depth

#### Used Tools

#### Instructions

#### Example of Recommendation

### 1.11. Subdirectories

#### Used Tools

#### Instructions

#### Example of Recommendation

### 1.12. Accessible Subdirectories

#### Used Tools

#### Instructions

#### Example of Recommendation

### 1.13. Outbound Links

#### Used Tools

#### Instructions

#### Example of Recommendation

### 1.14. Website Sitelinks

#### Used Tools

#### Instructions

#### Example of Recommendation

### 1.15. Descriptive Media File Names

#### Used Tools

#### Instructions

#### Example of Recommendation

## 2. Page-Level Factors

### 2.1. Missing Title Tag

### 2.2. Keywords in Titles

### 2.3. Duplicate Titles

### 2.4. Title Length

### 2.5. Headings

### 2.6. Keywords in Headings

### 2.7. Keywords in Main Content

### 2.8. Missing Meta Descriptions

### 2.9. Keywords in Meta Descriptions

### 2.10. Meta Descriptions Length

### 2.11. Duplicate Meta Descriptions

### 2.12. Descriptive URLs

### 2.13. Separating Words in URLs

### 2.14. Keywords in URLs

### 2.15. URL Length

### 2.16. Dates in URL

### 2.17. Unsafe Characters in URLs

### 2.18. Missing Alternative Text for Multimedia

### 2.19. Keywords in Alternative Text

### 2.20. Meta Keywords

### 2.21. Number of Links on a Page

## 3. Technical

### 3.1. Page Indexation

### 3.2. 4XX Client Error

### 3.3. 5XX Server Error

### 3.4. Page Render

### 3.5. Pages Restricted From Indexing

### 3.6. Canonicalisation

### 3.7. 301 Redirects

### 3.8. 302 Redirects

### 3.9. Redirect Chains

### 3.10. Meta Refresh

### 3.11. Sitemap for Robots

### 3.12. Language Markup

### 3.13. Schema Markup

## 4. User Experience

### 4.1. Mobile Friendly Test

### 4.2. PageSpeed Insights

### 4.3. Accelerated Mobile Pages (AMP)

### 4.4. Response Time

### 4.5. Pop-ups

### 4.6. Hidden Content

### 4.7. Text in Images

### 4.8. Breadcrumb Navigation

### 4.9. Ads

### 4.10. Sliders

### 4.11. Pagination

### 4.12. Flash

### 4.13. Sitemap for Humans

### 4.14. Image Pages

### 4.13. 404 Page

### 4.14. Search

### 4.15. Code Validation

## 5. Content

### 5.1. Thin Content

### 5.2. Internal Duplicate Content

### 5.3. External Duplicate Content

### 5.4. Keyword Cannibalization

### 5.5. Related Keywords

### 5.6. Hints & Tips or How-To Content

### 5.7. Fresh Content

### 5.8. Content Pruning

### 5.9. Content Ideas

### 5.10. Internal Search Queries

### 5.11. Queries for Which Your Images Rank

## 6. Local

### 6.1. Country Targeting

### 6.2. Geo-Focused Keywords

### 6.3. Business Name, Address, Phone (NAP)

### 6.4. Google My Business

### 6.5. Local Citations

### 6.6. Bing Places for Business

### 6.7. Apple Maps

### 6.8. Reviews

### 6.9. Responses to Reviews

### 6.10. Server Location

### 6.11. Physical Web

## 7. Off-Site

### 7.1. Referring Domains

### 7.2. Referring Pages (aka Backlinks)

### 7.3. Link Targeting

### 7.4. Broken Backlinks

### 7.5. Anchor Texts

### 7.6. Online Mentions

### 7.7. Disavow File

### 7.8. Branded Search Query Results

### 7.9. Search Autocomplete

### 7.10. Mostly Shared Pages

### 7.11. Site Neighbourhood

## 8. Competitor Analysis

### 8.1. Search Visibility

### 8.2. Referring Domains

### 8.3. Referring Pages (aka Backlinks)

### 8.4. Type of Content

### 8.5. Keyword in Title

### 8.6. Content Length

### 8.7. Search Ads History

### 8.8. Search Ads Data

### 8.9. Engagement
