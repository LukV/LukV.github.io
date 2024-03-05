# Luk Verhelst's Profile Page

## Overview

This profile page at https://lukv.github.io/#me is a straightforward, client-side HTML document. It leverages RDFa for semantic annotation of HTML content and includes additional profile information in Turtle format. The profile page is hosted on GitHub pages, from https://github.com/LukV/lukv.github.io.

## HTTP Headers Insights

Sending an HTTP request with curl:

```bash
curl -IL  http://lukv.github.io/#me
```

reveales these access and caching strategies for the page:
* `Access-Control-Allow-Origin *`: Any domain can request the page, facilitating broader data sharing.
* ETag: The presence of an ETag offers a unique version identifier to reuse cached versions when the page is unchanged.
* Utilizing `Cache-Control` ensures that browsers or other clients can reuse cached content for a maximum period, in theis case `max-age=600` for 10 minutes (600 seconds).
* `Via: 1.1 varnish` indicates that a Varnish cache was involved.