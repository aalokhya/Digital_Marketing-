Date : 15-09-2026

H1 tag : H1 is the main heading of a webpage.
H1 → Main topic
H2 → Main sections
H3 → Subsections inside an H2
SEO Title appears mainly in search results/browser context.
H1 appears on the webpage as the main heading.
Content Optimization : 
 

Keyword density is the percentage of times a target keyword appears in a webpage's content compared with the total number of words.
Keyword Density (%) = (Number of times keyword appears ÷ Total number of words) × 100
Ex :  wrds in webpage = 1000 , keyword (electrical shop in hnk ) = 10 then , 
                        %  =  ( 10 / 1000 ) * 100   ----- > 1 % 


Lesson 5 — Duplicate Content, Internal & External Links
Duplicate content means the same or very similar content appears on more than one URL/page.
•	when multiple URLs have substantially similar content, search engines may have difficulty deciding which version should be shown/indexed and some times can lead to Google penalty also 
•	we can prevent the duplicate content by writing the unique content , don’t create pages just for keywords , use canonical tags 

•	(Canonical tag tells search engines which URL is the preferred/main version when multiple URLs have the same or very similar content.)
•	Ex : /electrical-products and /electrical-products? sort=price 
•	It's mainly useful when multiple URLs exist for legitimate/technical reasons, and you need to tell search engines which URL is the preferred one.
Example of duplicate content :   example.com/electrical-products   ,   example.com/electrical-materials
Google penalty is when Google takes action against a website because it violates Google's spam policies. This can cause some pages to rank much lower, or in serious cases, pages/site to be removed from Google's search results.
Example of google penalty: Copying competitor content , Suppose someone tries to manipulate rankings by:
•	Buying large numbers of spammy backlinks 
•	Creating pages purely to manipulate search rankings 
•	Keyword stuffing 
•	Hiding keywords from users 
•	Using deceptive techniques.  These can violate Google's spam policies.
Duplicate Content Checker
A duplicate content checker is a tool that compares your content with other content and identifies text that is identical or very similar.
It can help you find:
•	Content copied from another website 
•	Content that is too similar to another page 
•	Duplicate sections within your own website
Tools  : Copyscape  , Grammarly plagiarism checker , Quetext , Siteliner
internal link is a link from one page of your website to another page on the same website. (  <a href="/electrical-products">Electrical Products</a> )
	Why use internal links?
•	Help visitors navigate your website. 
•	Help search engines discover other pages. 
•	Connect related pages. 
•	Help establish the structure/hierarchy of your website.
 external link is a link from your website to a different website/domain. External links can be useful when you're referring users to a trustworthy, relevant source.
Type	Goes to
Internal link	Your website → Your website
External link	Your website → Another website
Backlink	Another website → Your website
	
Anchor text is the clickable text of a link. descriptive anchor text helps the user understand where the link goes and gives search engines useful context about the linked page.
•	Don’t use words like click here , read etc use exact name or page of what that link leads to that is electrical products , services etc 
	

Lesson 6 - Canonical Tag, Image ALT Tag & Breadcrumbs
A canonical tag tells search engines which URL is the preferred/main version when multiple URLs have the same or very similar content.
ALT text is a description added to an image in HTML that helps search engines and screen readers understand what the image shows.
Uses: 
Helps accessibility for users who can't see the image. 
Helps search engines understand the image. 
Can help images appear in relevant image searches.


Breadcrumbs are a navigation path that shows the user's location within a website, such as Home → Electrical Products → Switches.

Uses :  helps in navigation for users and for search engines it helps to understand the structure of website 

Lesson 7 - Schema.org , 404 / 302 / 301 Errors
Schema.org  provides structured-data vocabulary that helps search engines understand the meaning and details of webpage content.
•	We write Schema as structured data in JSON-LD format. 
•	website can still work and can still be indexed and ranked without Schema.
•	Schema is additional structured information that helps search engines understand the page/entity.
Ex : 
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "name": "ABC Electricals",
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Hanamkonda"
  }
}
</script>
Tools : 
technicalseo.com ( we can create the schema code of  organization , local business , breadcrumbs , faqs all these here )

404 error :  The requested webpage cannot be found. 
If you delete or rename that page without handling the old URL, someone visiting the old URL may see 404 Not Found.
301 redirect = Permanently sends users and search engines from an old URL to a new URL.
302 redirect = Temporarily sends users from one URL to another.
Problem	What you do
404 because page was accidentally deleted	Restore/create the page
404 because page permanently moved	301 → new page
Wrong 301 destination	Correct the redirect
Permanent move using 302	Change 302 → 301
Temporary move using 301	Usually change 301 → 302
	

Lesson 8 — Sitemap & Robots.txt
A sitemap is a file that tells search engines about the important pages on your website.
Ex : https://yourwebsite.com/sitemap.xml
It helps search engines discover and understand the URLs on your site, especially when a website has many pages.
Ex : 
 

image sitemap is a file that helps search engines discover the images on your website.
When some one searches Google can potentially understand and show those images in image search.
Sitemap → tells Google about your web pages          
Image sitemap → helps Google discover your images

robots.txt is a set of crawling instruction  (or) robots.txt is a file that gives instructions to search-engine crawlers about which parts of a website they may or may not crawl.
Crawling is necessary for search engines to discover/read webpages.
No robots.txt → your website can still be crawled.
Ex : User-agent: *  (applies to all agents )
Disallow: /admin/  (don’t check admin area)
Sitemap: https://yourwebsite.com/sitemap.xml

Geo tags are location information added to a webpage or content to indicate where a business or place is located.
Ex : <meta name="geo.region" content="IN-TS">   
<meta name="geo.placename" content="Hanamkonda">
<meta name="geo.position" content="17.9784;79.5941">

OG tags ( open graph ) : HTML tags that control how your webpage appears when someone shares your website link on social media or messaging platforms.
 
Tools :  https://freecodetools.org/ogp/

SEO → Get found in search engines
AEO → Provide content that can be used as a direct answer
GEO → Make content understandable/useful for generative AI answer

Lesson 9 : Google Search Console & Google Analytics

Google Search Console (GSC) is a free Google tool that helps you understand how your website performs in Google Search and whether Google can properly discover/index your pages.  What happens in Google Search before someone reaches your website?
Ex :  Google Search - > Impression - > Click - > Your website
4 major terms :
Impressions - How many times your website's search result was shown in Google Search.
Clicks - How many times someone clicked your search result.
CTR - Click-Through Rate = percentage of impressions that resulted in clicks.
For example: 500 impressions + 25 clicks = 5% CTR.
Average Position - The average position of your website in Google's search results for the queries being reported.
It can tell you things like:
•	What people searched for 
•	How many times your website appeared in Google 
•	How many people clicked your result 
•	Your average position 
•	Which pages Google has indexed 
•	Which pages have indexing problems 
•	Whether your sitemap was submitted successfully
Google Analytics  :  What happens after someone reaches your website?
Your website - > Visitor views pages -> Clicks WhatsApp - > Clicks phone number - > Engages with website

Search Console → Google Search performance
Analytics → Website visitor behavior







