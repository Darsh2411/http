 ## what are domain names?
 ## so, do i have to choose one or the other for my web site?
 ## techniques for canonical URLs
 ### using http 301 redirects
 Example:
 - A server receives a request for http://www.example.org/whaddup (when the canonical domain is example.org)
 - The server answers with a code 301 with the header Location: http://example.org/whaddup.
 - The client issues a request to the canonical domain: http://example.org/whatddup

 ### using &lt;link rel="cannoical"&gt;
This has no impact on the human reader of the page, but tells search engine crawlers where the page actually lives. This way, search engines don't index the same page several times, potentially leading to it being considered as duplicate content or spam, and even removing or lowering your page from the search engine result pages.<

Unlike the previous case, browser history will consider non-www and www URLs as independent entries.

## mark your page work for both
## deciding the case
## see also