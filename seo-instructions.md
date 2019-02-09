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

None of the internal links from pages on your site, pointing to your home page, use your primary keyword ‘[KEYWORD X]’ (Figure 1.6.1). We recommend changing the alt text of your business logo image from ‘[X]’ to ‘[Y]’, as this will help increase the relevance of your page for the query ‘[KEYWORD Y]’.

Links to your [PAGE Y] and [PAGE Z] pages contain the primary keyword ‘[KEYWORD Y]’ or ‘[KEYWORD Z]’, but you also should consider linking from other places on your site with secondary keywords like ‘[KEYWORD YY]’ or ‘[KEYWORD ZZ]’ in the anchor text. This way you will increase their chances of ranking for these keywords in the search.
Figure 1.6.1 – A list of incoming internal links pointing to your home page, and all anchor and alt texts used in them

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

- Screaming Frog - crawl sitemap
- Server logs - get list of visited pages and crawl it

#### Instructions

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

Great, all of your pages are a maximum of two clicks away from your home page.

### 1.11. Subdirectories

#### Used Tools

#### Instructions

#### Example of Recommendation

Good job, your pages do not have more than two directories.
Figure 1.11 – A list of pages on your site that have more than three directories.

| URLs        | Number of directories          |
| ------------- | ------------- |
| placeholder     | placeholder |

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

1.	Screaming Frog > External tab > Export all
2.	Check are their follow or nofollow 
    Screaming Frog > Bulk Export top bar > All Outlinks
    In Excel: Remove duplicates and links to client’s site
    Excel > Data tab > Advanced > Unique records only 
3.	Go to Moz Open Site Explorer
    Check for Domain Authority, Page Authority and Spam Score
4.	Check in Excel if link to sites with low DA and high Spam Score are nofollow 
5.	Host-machine-ratio > 5 = potential indication that your site is spammy

#### Instructions

#### Example of Recommendation

An authority of one of the domains, which your site associates itself with by linking to, is quite low ([DOMAIN X]). It is good practice to set up a ‘nofollow’ tag on that link and on any that may be untrustworthy (Figure 1.13).

In addition, your link to a website from all pages or a very large number of them. It’s recommended you have all of these ‘site-wide’ and tagged as ‘nofollow’ links ([DOMAIN Z]).

The table below shows websites to which you point to from your pages. Domain and Page Authority shows an estimate of how trusted and respected a website may be on the Internet. Spam Score shows the likelihood of a site being spam. The number of outbound links represents how many times that link was found on your site.
Figure 1.13 – A list of websites with the lowest ‘authority’ and the highest likelihood of being spam to which your site sends users.

| Link        | Domain Authority           | Page Authority  | Spam Score        | Number of Outbound links           | Dofollow/ Nofollow  |
| ------------- | ------------- | ----- | ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder | placeholder     | placeholder | placeholder |

### 1.14. Website Sitelinks

#### Used Tools

#### Instructions
Perform a branded search on Google and Bing and check if any sitelinks are displayed.

#### Example of Recommendation

While sitelinks are not showing up under your home page on Bing, Google shows six of them when a user searches for your brand name (Figure 1.13). They all look good.
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

1.	Identify headings with Woorank (Chrome Extension) >
2.	Check font size with CSSViewer (Chrome Extension)
3.	Check does a heading contain an image or logo.

#### Example of Recommendation

Figure 2.5.1 – A number of headings by type, how many of them were detected on your [DELETE: PLACEHOLDER: PAGE X] page.

| <H1>        | <H2>        | <H3>        | <H4>        | <H5>        |
| ----- | ----- | ----- | ----- | ----- |
| placeholder     | placeholder | placeholder | placeholder     | placeholder |

Figure 2.5.2 – A list of headings on the page that ranks for keyword ‘[DELETE: KEYWORD X]’.

| Heading Text        | Heading Type           | Heading Size/Text Size  |
| ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder |

 Figure 2.5.3 – A number of headings by type, how many of them were detected on your [DELETE: PLACEHOLDER: PAGE Y] page.

| <H1>        | <H2>        | <H3>        | <H4>        | <H5>        |
| ----- | ----- | ----- | ----- | ----- |
| placeholder     | placeholder | placeholder | placeholder     | placeholder |

Figure 2.5.4 – A list of headings on the page that ranks for keyword ‘[DELETE: KEYWORD Y]’.

| Heading Text        | Heading Type           | Heading Size/Text Size  |
| ------------- | ------------- | ----- |
| placeholder     | placeholder | placeholder |

 Figure 2.5.5 – A number of headings by type, how many of them were detected on your [DELETE: PLACEHOLDER: PAGE Z] page.

| <H1>        | <H2>        | <H3>        | <H4>        | <H5>        |
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

Your Home page main heading is optimised for keywords ‘[DELETE: PHRASE G]’instead of being optimised for ‘[DELETE: PHRASE A]’ (Figure 2.6.1). We recommend rewriting this to include the phrase ‘[DELETE: PHRASE F]’ or something similar. Other pages contain their primary keywords in the main heading, which is ideal.

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

We analysed the keywords you use in the main content of your Home page, [DELETE: PAGE A NAME] page and [DELETE: PAGE B NAME] page. Here is what we found:

On the Home page, the phrases used most often are ‘[DELETE: PHRASE A]’ and ‘[DELETE: PHRASE B]’ instead of your targeted keyword ‘[DELETE: PHRASE C]’ (Figure 2.7.3, Figure 2.7.4). The word ‘[DELETE: PHRASE D]’ occurs 6 times, while the word ‘[DELETE: PHRASE C]’ occurs only 4 times within the 397 words on the page (Figure 2.7.2). However, these words are not displayed on the page together or even close to each other (Figure 2.7.1). In addition to this, the word ‘[DELETE: WORD A]’ is rarely used in the main content. You should consider rewriting some parts of your page to include the keywords ‘[DELETE: PHRASE A]’ or ‘[DELETE: PHRASE B].

On your [DELETE: PAGE A] page, your main keyword is detected 9 times (Figure 2.7.6, Figure 2.7.7, Figure 2.7.8), while in the main copy it appears 6 times within the 309 words of text (Figure 2.7.5). This is a healthy ratio. We recommend using the word ‘[DELETE: WORD A]’ together with the word ‘[DELETE: WORD B]’ within the copy, e.g. ‘[DELETE: PHRASE A]’ to strengthen your local relevance.

On your [DELETE: PAGE A] page, we detected your main keyword 13 times (Figure 2.7.10, Figure 2.7.11, Figure 2.7.12), but only 7 times in the page’s visible copy (Figure 2.7.9). This is because in the page’s code, you have hidden duplicate mobile content, which should be fixed. In addition to this, you should rewrite the copy to include the phrase ‘[DELETE: PAGE A] in Dublin’, as this should also improve your page ranking for this query.

Figure 2.7.1 – The text content of your Home page with highlighted primary keywords (bolded text) and related (underlined text) keywords.

Figure 2.7.2 – A list of one-word keywords that occur most often on your Home page, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

Figure 2.7.3 – A list of two-word keywords that occur most often on your Home page, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

Figure 2.7.4 – A list of three-word keywords that occur most often on your Home page, together with the number of times they are repeated (Freq), what percentage of the page’s content contains this word (density).

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

1.	Screaming Frog > Meta Description > Filter: Duplicate
2.	Search Console > Search Appearance > HTML Improvements

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

We analysed the keywords you use in the URLs of your Home page, [PAGE Y] page and [PAGE Z] page. Here is what we found:

Your Home page ranks on both Google and Bing for ‘[KEYWORD X]’ and ‘[KEYWORD Y]’. For the keyword ‘[KEYWORD X]’ this is ideal. The URL also looks as it should (Figure 2.3). However, for the keyword ‘[KEYWORD Y]’ there is an issue, as the search engines think that the Home page is more relevant than your dedicated page for this keyword. We need to work on improving the quality (more valuable content), relevance (more content around this keyword on the page and internal links that mention ‘’) and authority (more backlinks from other websites) of this page. This should fix the issue of a wrong page ranking for your targeted keyword.

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

#### Example of Recommendation

### 2.16. Dates in URL

#### Used Tools

#### Instructions

#### Example of Recommendation

### 2.17. Unsafe Characters in URLs

#### Used Tools

#### Instructions

#### Example of Recommendation

### 2.18. Missing Alternative Text for Multimedia

#### Used Tools

#### Instructions

#### Example of Recommendation

### 2.19. Keywords in Alternative Text

#### Used Tools

#### Instructions

#### Example of Recommendation

### 2.20. Meta Keywords

#### Used Tools

#### Instructions

#### Example of Recommendation

### 2.21. Number of Links on a Page

#### Used Tools

#### Instructions

#### Example of Recommendation

## 3. Technical

### 3.1. Page Indexation

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.2. 4XX Client Error

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.3. 5XX Server Error

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.4. Page Render

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.5. Pages Restricted From Indexing

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.6. Canonicalisation

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.7. 301 Redirects

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.8. 302 Redirects

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.9. Redirect Chains

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.10. Meta Refresh

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.11. Sitemap for Robots

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.12. Language Markup

#### Used Tools

#### Instructions

#### Example of Recommendation

### 3.13. Schema Markup

#### Used Tools

#### Instructions

#### Example of Recommendation

## 4. User Experience

### 4.1. Mobile Friendly Test

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.2. PageSpeed Insights

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.3. Accelerated Mobile Pages (AMP)

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.4. Response Time

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.5. Pop-ups

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.6. Hidden Content

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.7. Text in Images

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.8. Breadcrumb Navigation

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.9. Ads

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.10. Sliders

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.11. Pagination

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.12. Flash

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.13. Sitemap for Humans

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.14. Image Pages

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.13. 404 Page

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.14. Search

#### Used Tools

#### Instructions

#### Example of Recommendation

### 4.15. Code Validation

#### Used Tools

#### Instructions

#### Example of Recommendation

## 5. Content

### 5.1. Thin Content

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.2. Internal Duplicate Content

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.3. External Duplicate Content

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.4. Keyword Cannibalization

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.5. Related Keywords

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.6. Hints & Tips or How-To Content

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.7. Fresh Content

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.8. Content Pruning

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.9. Content Ideas

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.10. Internal Search Queries

#### Used Tools

#### Instructions

#### Example of Recommendation

### 5.11. Queries for Which Your Images Rank

#### Used Tools

#### Instructions

#### Example of Recommendation

## 6. Local

### 6.1. Country Targeting

#### Used Tools

#### Instructions

#### Example of Recommendation

### 6.2. Geo-Focused Keywords

#### Used Tools

#### Instructions

#### Example of Recommendation

### 6.3. Business Name, Address, Phone (NAP)

#### Used Tools

#### Instructions

#### Example of Recommendation

### 6.4. Google My Business

#### Used Tools

#### Instructions

#### Example of Recommendation

### 6.5. Local Citations

#### Used Tools

#### Instructions

#### Example of Recommendation

### 6.6. Bing Places for Business

#### Used Tools

#### Instructions

#### Example of Recommendation

### 6.7. Apple Maps

#### Used Tools

#### Instructions

#### Example of Recommendation

### 6.8. Reviews

#### Used Tools

#### Instructions

#### Example of Recommendation

### 6.9. Responses to Reviews

#### Used Tools

#### Instructions

#### Example of Recommendation

### 6.10. Server Location

#### Used Tools

#### Instructions

#### Example of Recommendation

### 6.11. Physical Web

#### Used Tools

#### Instructions

#### Example of Recommendation

## 7. Off-Site

### 7.1. Referring Domains

#### Used Tools

#### Instructions

#### Example of Recommendation

### 7.2. Referring Pages (aka Backlinks)

#### Used Tools

#### Instructions

#### Example of Recommendation

### 7.3. Link Targeting

#### Used Tools

#### Instructions

#### Example of Recommendation

### 7.4. Broken Backlinks

#### Used Tools

#### Instructions

#### Example of Recommendation

### 7.5. Anchor Texts

#### Used Tools

#### Instructions

#### Example of Recommendation

### 7.6. Online Mentions

#### Used Tools

#### Instructions

#### Example of Recommendation

### 7.7. Disavow File

#### Used Tools

#### Instructions

#### Example of Recommendation

### 7.8. Branded Search Query Results

#### Used Tools

#### Instructions

#### Example of Recommendation

### 7.9. Search Autocomplete

#### Used Tools

#### Instructions

#### Example of Recommendation

### 7.10. Mostly Shared Pages

#### Used Tools

#### Instructions

#### Example of Recommendation

### 7.11. Site Neighbourhood

#### Used Tools

#### Instructions

#### Example of Recommendation

## 8. Competitor Analysis

### 8.1. Search Visibility

#### Used Tools

#### Instructions

#### Example of Recommendation

### 8.2. Referring Domains

#### Used Tools

#### Instructions

#### Example of Recommendation

### 8.3. Referring Pages (aka Backlinks)

#### Used Tools

#### Instructions

#### Example of Recommendation

### 8.4. Type of Content

#### Used Tools

#### Instructions

#### Example of Recommendation

### 8.5. Keyword in Title

#### Used Tools

#### Instructions

#### Example of Recommendation

### 8.6. Content Length

#### Used Tools

#### Instructions

#### Example of Recommendation

### 8.7. Search Ads History

#### Used Tools

#### Instructions

#### Example of Recommendation

### 8.8. Search Ads Data

#### Used Tools

#### Instructions

#### Example of Recommendation

### 8.9. Engagement

#### Used Tools

#### Instructions

#### Example of Recommendation
