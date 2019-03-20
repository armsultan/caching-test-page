# Website to test HTTP/HTTPS Caching

A static website that include several HTML files through iFrames to demonstrate various cache / no cache methods

The website will need to be hosted on webserver capable of setting response headers - see [Nginx configurations](cache_test_pages.conf)

This is a suitable website for testing browser and proxy caches

This test page is an adaptation of [HTTPS Caching Test Page](https://demo.securityevaluators.com/) by Jacob Thompson


## Testing and troubleshooting

You will need to inspect HTML and HTTP headers to confirm cache control directives are set. You can use various web developtment / network tools to inspect these details:

### Client Side Tools

 - [Chrome Developer Tools](https://developer.chrome.com/devtools)
 - [Firebug](http://getfirebug.com/)
 - [Fiddler](http://getfirebug.com/)

#### A great list of online Tools:**
 - [16 Website Speed Test Tools for Analyzing Web Performance](https://www.keycdn.com/blog/website-speed-test-tools/)

**Credit and resources:**
 - This test page is an adaptation of [HTTPS Caching Test Page](https://demo.securityevaluators.com/) by Jacob Thompson