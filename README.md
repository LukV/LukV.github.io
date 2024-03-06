# Luk Verhelst's Profile Page

## Overview

This profile page at https://lukv.github.io/#me is a straightforward, client-side HTML document. It leverages RDFa for semantic annotation of HTML content and includes additional profile information in Turtle format. The profile page is hosted on GitHub pages, from https://github.com/LukV/lukv.github.io.

## HTTP Headers Insights

Sending an HTTP request with curl reveals below response headers.

```bash
curl -IL  http://lukv.github.io/#me
```

* HTTP/2 200 
* server: GitHub.com
* content-type: text/html; charset=utf-8
* last-modified: Wed, 06 Mar 2024 07:44:42 GMT
* access-control-allow-origin: *
* etag: "65e81eea-a3c"
* expires: Wed, 06 Mar 2024 07:56:15 GMT
* cache-control: max-age=600
* x-proxy-cache: MISS
* x-github-request-id: AB62:131A35:896E6A:8C6E8F:65E81F46
* accept-ranges: bytes
* date: Wed, 06 Mar 2024 07:46:15 GMT
* via: 1.1 varnish
* age: 0
* x-served-by: cache-bru1480041-BRU
* x-cache: MISS
* x-cache-hits: 0
* x-timer: S1709711175.952056,VS0,VE118
* vary: Accept-Encoding
* x-fastly-request-id: 11d1571f856b25616ceb89a830b2e3fc1a201e3d
* content-length: 2620

Caching strategies for the page:
* etag: The presence of an ETag offers a unique version identifier to reuse cached versions when the page is unchanged.
* Utilizing `cache-control` ensures that browsers or other clients can reuse cached content for a maximum period, in theis case `max-age=600` for 10 minutes (600 seconds).
* `via: 1.1 varnish` indicates that a Varnish cache was involved.
* `vary: Accept-Encoding` informs a cache that the content is based on the encoding accepted by the client

Access strategy:
* `Access-Control-Allow-Origin *`: Any domain can request the page, facilitating broader data sharing.

