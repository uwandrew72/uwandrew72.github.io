---
title:  "Rapid Response Search Engine"
categories:
  - Projects
permalink: /search-engine
---

* modules that can efficiently crawl static file folders' sub-tree, generate inverted indices, and store indices along with error checking metadata in cross-platform POSIX format
* a query processor that can handle user queries by searching through multiple indices, and serve a ranked list of results based on their correlation with the query words within 1 second
* a multi-threaded web server with a thread pool to handle concurrent client connections, and enhanced robustness by escaping cross-site scripting flaw and directory traversal attack