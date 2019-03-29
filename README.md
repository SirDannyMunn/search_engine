# search_engine
An implementation of the search engine created in the Udacity Intro to Computer Science course.

# Algorithm details
Crawl the web starting from a seed page.

Ensure the crawler doesn't crawl the same page twice.

Index every page by splitting the words within the page and then checking the index if the entry already exists for each word. If it doesn't add it along with the url if it does, just add the url.

Lookup functionality works as follows: Search the index using a keyword parameter as the point of search  and return any urls which match.
