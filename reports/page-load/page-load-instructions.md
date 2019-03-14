# Instructions for Page Load Optimisation Audit Report

## Table of Content

1. [Response Time](#1-response-time)  
  1.1. [Server-Side Caching](#11-server-side-caching)  
  1.2. [Server Location](#12-server-location)  
  1.3. [Accelerated Mobile Pages (AMP)](#13-accelerated-mobile-pages-amp)  
  1.4. [HTTP Strict Transport Security (HSTS)](#14-http-strict-transport-security-hsts)  
  1.5. [Content Delivery Network (CDN)](#15-content-delivery-network-cdn)  
  1.6. [Prefetching](#16-prefetching)  
2. [Time to First Paint](#2-time-to-first-paint)  
  2.1. [Size of HTML Pages](#21-size-of-html-pages)  
  2.2. [Server Push](#22-server-push)  
  2.3. [Unused Code](#23-unused-styles)  
  2.4. [Non-Essential Styles](#24-non-essential-styles)  
  2.5. [Code Minification](#25-code-minification)  
  2.6. [Server-Side Compression](#26-server-side-compression)  
  2.7. [Async Loading of Code](#27-async-loading-of-code)  
  2.8. [Number of Requested Files](#28-number-of-requested-files)  
  2.9. [HTTP/2](#29-http2)  
  2.10. [DNS Prefetching](#210-dns-prefetching)  
  2.11. [Code Validation](#211-code-validation)  
3. [Time to Interaction](#3-time-to-interaction)
4. [Page Load Time](#4-page-load-time)  
  4.1. [Total Page Size](#41-total-page-size)  
  4.2. [Image Format](#42-image-format)  
  4.3. [Image Dimension](#43-image-dimension)  
  4.4. [Image Compression](#44-image-compression)  
  4.5. [Deferred Image Load](#45-deferred-image-load)  
  4.6. [Client-Side Caching](#46-client-side-caching)  
  4.7. [Query Strings](#47-query-strings)  

## 1. Response Time

### 1.1. Server-Side Caching

#### Used Tools

#### Instructions

#### Example of Recommendation

### 1.2. Server Location

#### Used Tools

#### Instructions

WebPageTest.org > Details tab > time needed to receive HTML page over 1 second

#### Example of Recommendation

Your website does not use server caching. It is recommended to set it up on your server as soon as possible, as it can significantly increase your website’s speed.

### 1.3. Accelerated Mobile Pages (AMP)

#### Used Tools

#### Instructions

Screaming Frog > Configuration > Custom > Extraction
XPath
//head/link[@rel='amphtml']/@href
Extract HTML Element

#### Example of Recommendation

Your site does not have AMP versions of your pages. Consider implementing them for improved load time on mobile phones.

### 1.4. HTTP Strict Transport Security (HSTS)

#### Used Tools

#### Instructions

Use this page to test does a site uses HSTS: https://hstspreload.org/

#### Example of Recommendation

Very good, your site uses HSTS.

### 1.5. Content Delivery Network (CDN)

#### Used Tools

#### Instructions

#### Example of Recommendation

We did not detect that your site is using Content Delivery Networks. It is worth setting this up, even if the majority of your visitors live a small distance from your server.

#### Solutions

You could use a CDN like Cloudflare, which provides you with a free basic CDN functionality.
[Using Cloudflare with WordPress](https://support.cloudflare.com/hc/en-us/articles/227634427-Using-Cloudflare-with-WordPress)
[How can I tell if Cloudflare is caching my site or a specific file?](https://support.cloudflare.com/hc/en-us/articles/200169556-How-can-I-tell-if-CloudFlare-is-caching-my-site-or-a-specific-file-)
[What do the various Cloudflare cache responses (HIT, Expired, etc.) mean?](https://support.cloudflare.com/hc/en-us/articles/200168266-What-do-the-various-CloudFlare-cache-responses-HIT-Expired-etc-mean-)

### 1.6. Prefetching

#### Used Tools

1.	Manual > check the source code on the homepage for prefetch directive
2.	Google Analytics > Audience > User Flow

#### Instructions

#### Example of Recommendation

We have already set up prefetching directive from your memberships pages to your Thank You page, as hopefully most of the visitors to this page will fill out the registration form and end up on the Thank you page.

However, we have not detected a prefetching directive on any other pages on your site. We checked your user flow after they arrived on your homepage. As you can observe on Figure 9.1.2, they follow a clear path from the homepage, to [KEYWORD D], and then to the [KEYWORD D] page, before finally ending up at the [PAGE T] page.

Each of the pages in this path should prefetch the next one in order to help the user get to the final destination in the shortest amount of time. This should decrease the percentage of users dropping on each page.

Moreover, you should consider prefetching a few ‘critical resources’ on all pages, which are used across the whole site.

Figure 9.1.2 – User flow after arriving on the homepage.

## 2. Time to First Paint

### 2.1. Size of HTML Pages

#### Used Tools

According to HTML5 spec, self-closing syntax (/>) can't be used on a non-void HTML element.

#### Instructions

#### Example of Recommendation

Your homepage is 37.7 KB in size and your [PAGE X] page is 55.8 KB. However, all pages on your site are above 30 KB (Figure 2.1.1). After reviewing the HTML code of your pages, we notice some of them have the main content and the footer in a few places on the same page. These are labelled as ‘desktop’, ‘large-desktop’, ‘small-desktop’ and ‘mobile’ (Figure 2.1.2), with only one copy visible at a time. This significantly increases the size of your HTML pages, by deleting the duplicated content you will make your pages lighter and faster.

Figure 2.1.1 – A list of all pages found on your site with their HTML sizes.

| URL        | Size          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 2.1.2 – A snippet of code from your [PAGE A] page with two copies of the main content. One for desktop (green colour) and another for mobile (blue colour). These could be reduced to one copy with the use of CSS styles.

### 2.2. Critical CSS

#### Used Tools

https://developers.google.com/web/tools/chrome-devtools/css/reference#coverage

https://developers.google.com/web/tools/lighthouse/audits/unused-css#inlining

#### Instructions

### 2.3. Server Push

#### Used Tools

#### Instructions

#### Example of Recommendation

#### Solutions

If you use Cloudflare as your CDN, you will need to do (https://support.cloudflare.com/hc/en-us/articles/115002816808-How-do-I-enable-HTTP-2-Server-Push-in-WordPress)

### 2.4. Unused Styles

#### Used Tools

- Google Chrome DevTools: Coverage tool

Google Chrome > DevTools (OPTION + COMMAND + I on Mac or CONTROL + SHIFT + I on Windows) > open the Command Menu (SHIFT + COMMAND + P on Mac or CONTROL + SHIFT + P on Windows) > Show Coverage

- Google Chrome DevTools: Request Blocking tool

Google Chrome > DevTools (OPTION + COMMAND + I on Mac or CONTROL + SHIFT + I on Windows) > open the Command Menu (SHIFT + COMMAND + P on Mac or CONTROL + SHIFT + P on Windows) > Request Blocking tool

#### Instructions

1. Go to Show Coverage tool and refresh the page.
2. Identify, which files are not used or used minimally on the site.
3. Check if you can safely remove them by temporarily blocking them in your browser. To do this, open Request Blocking tool and add URLs of files that you would like to block, then reload the page.
4. If removing blocking/removing files brake the design or functionality on the page on desktop or mobile device, you should be able to move important code other files, then remove the old files.

Video: https://youtu.be/5fLW5Q5ODiE?t=416

#### Example of Recommendation

Your site uses Bootstrap framework, which is 135 KB in size and adds a significant amount of unnecessary code to your site.

### 2.5. Non-Essential Styles

#### Used Tools

#### Instructions

Check page’s source code for print and width specific styles. Search for ‘media=‘

#### Example of Recommendation

Each device type downloads all styles at the same time. You should consider removing print and media query styles from the main style-sheet.

### 2.6. Code Minification

#### Used Tools

https://gtmetrix.com/

#### Instructions

#### Example of Recommendation

The size of the HTML code of your homepage can be minified by an average 32%, CSS by 13% and JavaScript by 3% (Figure 9.2.6.1).

On the [PAGE Z] page, the HTML can be made an average of 17% smaller through Minification while CSS by 13% and JavaScript by 5% (Figure 9.2.6.2).
This will make these files load in a shorter amount of time.

Figure 9.2.6.1 – List files with code on your homepage and potential reduction gains from minifying them.

| Files        | Potential Gain          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 2.7. Server-Side Compression

#### Used Tools

https://gtmetrix.com/
or
http://www.gidnetwork.com/tools/gzip-test.php
or
Chrome DevTools > Network > Use small request rows > Size column
https://youtu.be/5fLW5Q5ODiE?t=252

#### Instructions

#### Example of Recommendation

23 of the files on your homepage (Figure 9.2.7.1), and 26 files on the [PAGE Z] page (Figure 9.2.7.2) are not compressed. Activating Gzip compression on your server could reduce the size of them by an average of 74%.

This will improve the load time on desktop and mobile phones of these two pages, as well as other pages on your site.

Figure 9.2.7.1 – A list of files with code on your homepage and potential reduction gains from compressing them.

| Files        | Potential Gain          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 2.8. Async Loading of Code

#### Used Tools

#### Instructions

#### Example of Recommendation

### 2.9. Number of Requested Files

#### Used Tools

Webpagetest.org > Content Breakdown tab

#### Instructions

#### Example of Recommendation

Your homepage requests the browser to download 56 files, while your [PAGE Z] page requests 70 files. All files should be reviewed and any that are not used by specific pages should not be downloaded. 
Figure 9.2.1 – Number of files requested by homepage and their types.

| File Type        | Number of Files          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 9.2.2 – All requested files by the homepage and their types.

| Number        | URL          | File Type          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |

### 2.10. HTTP/2

#### Used Tools

Check site on:

- https://tools.keycdn.com/http2-test
- https://http2.pro/
- [Tools for debugging, testing and using HTTP/2](https://blog.cloudflare.com/tools-for-debugging-testing-and-using-http-2/?utm_referrer=https://www.google.com/)

#### Instructions

#### Example of Recommendation

Your website does not use HTTP/2. You should ask your hosting provider to enable it for your site.

### 2.11. DNS Prefetching

#### Used Tools

#### Instructions

1. Manual > check the page source code for DNS-prefetch
2. WebPageTest.org > Details tab

#### Example of Recommendation

Your website uses DNS prefetching for your own domain and WordPress domain. There are still 3 more domains from which your page requests files. I recommend adding them too, as some of them slow down your page by up to half a second (Figure 9.3.8).
Figure 9.3.8 – A list of domains and the time it took to perform the DNS lookup for each of them.

| URL        | Lookup Time          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 2.12. Code Validation

#### Used Tools

#### Instructions

HTML validation: https://validator.w3.org/
CSS validation: https://jigsaw.w3.org/css-validator/
JavaScript validation: Chrome > Developers Tools > Console (it checks syntax; it does not mean that the code is flawless)

#### Example of Recommendation

The HTML code of your homepage has 20 minor errors and 2 warnings, while CSS code has 58 minor errors and 250 warnings. The [PAGE Z] page has 10 minor errors and no warnings, but the same number of CSS errors and warnings (Figure 9.12).
Fixing the majority of code errors on your site would improve the quality of used code and decrease the number of issues that browsers need to deal with to display your pages.  
Figure 9.2.8 – URLs of full reports from HTML and CSS code validation.

| URL        | Type          | Test URL          |
| ------------- | ------------- | ------------- |
| placeholder     | placeholder | placeholder |
| placeholder     | HTML | placeholder |
| placeholder     | CSS | placeholder |
| placeholder     | JavaScript | placeholder |

#### Example of Recommendation

## 3. Time to Interaction

## 4. Page Load Time

### 4.1. Total Page Size

#### Used Tools

webpagetest.org > Details

#### Instructions

#### Example of Recommendation

Your homepage is 1,974 KB, while your [PAGE Z] page is 5,246 KB in size. These sizes should be significantly reduced.

### 4.2. Image Format

#### Used Tools

#### Instructions

#### Example of Recommendation

Your website does not take advantage of WebP image format which could decrease the size of your images by 25-35%. Moreover, the animations on your pages are in GIF format, which from our tests on desktop take around 8 seconds to load. By converting those files to MP4, you could reduce their size and loading time by around 60%. If you replaced them with a static image, that time could be decreased by approximately 95%.

Figure 9.3.2.1 – List of images in saved in wrong format.
Images

| Images        |
| ------------- |
| placeholder     |

### 4.3. Image Dimension

#### Used Tools

#### Instructions

#### Example of Recommendation

Your site has mobile and tablet specific image dimensions. However, there is still room for further improvement. For example, the three images in the middle of the homepage have dimensions more than two times bigger than the space dedicated for them on the page. This adds unnecessary kilobits to the size of your page, ultimately slowing it down.

### 4.4. Image Compression

#### Used Tools

https://webspeedtest.cloudinary.com/
GTmetrix.com > PageSpeed > Optimize images

#### Instructions

#### Example of Recommendation

16 images on your homepage can be compressed on average by a further 12% with Lossless compression (Figure 4.4.1), without losing their quality. 12 images on the [PAGE Z] page could be 24% smaller (Figure 4.4.2). By using Lossy compression their size could be reduced even further.

Compressing images will reduce the time it takes to download them and display on your page.

Figure 4.4.1 – List of images on the homepage and how much smaller they could be by applying Lossless compression.

| Files        | Potential Gain          |
| ------------- | ------------- |
| placeholder     | placeholder |

Figure 4.4.2 – List of images on the [PAGE Z] page and how much smaller they could be by applying Lossless compression.

| Files        | Potential Gain          |
| ------------- | ------------- |
| placeholder     | placeholder |

### 4.5. Deferred Image Load

#### Used Tools

#### Instructions

#### Example of Recommendation

We have not detected the differed image load on your site. You should consider setting it up to make your pages load faster.

### 4.6. Client-Side Caching

#### Used Tools

WebPageTest.org > Details

#### Instructions

#### Example of Recommendation

Your website does not use browser caching, which should be fixed.

#### Solutions

### 4.7. Query Strings

#### Used Tools

WebPageTest.org > Details

#### Instructions

#### Example of Recommendation

22 files on your homepage and [PAGE Z] page contain query string (Figure 4.7), which prevents browsers from saving them for future usage.

Figure 4.7 – A list of files requested by your homepage and [PAGE Z] page that contain a query string.

| File        |
| ------------- |
| placeholder     |