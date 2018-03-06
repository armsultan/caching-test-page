**Website to test HTTPS Cache**
-----
A Static Website to test the download times of large images and hundreds of HTTP requests over HTTP1 and HTTP2

Hope to add more tests later...

Web performance tools
-----

First, it's beneficial to test with Latency, either with a Wan Emulator tools or accessing the web content over the internet, over real network latency

To confirm HTTP/2 is faster you can use various web performance measurement tools:

**Client Side Tools:**

 - [Chrome Developer Tools](https://developer.chrome.com/devtools)
 - [Firebug](http://getfirebug.com/)
 - [Fiddler](http://getfirebug.com/)

**A great list of online Tools:**
 - [16 Website Speed Test Tools for Analyzing Web Performance](https://www.keycdn.com/blog/website-speed-test-tools/)


HTTP2 Cheat Sheet
-----
To confirm HTTP/2 is working you can use various tools:

**Chrome Developer Tools** 
Chrome Developer Tools (View -> Developer -> Developer Tools) and reload the page (View -> Reload This Page). Then navigate to the Network tab, click on table header row that starts with Name, right-click on it, and select the Protocol option.

Now you should see h2 (which stands for HTTP/2) in a new column for your website serving HTTP/2 content.

**Firefox Firebug:** 
Open Firebug and navigate to the Net (Network) tab, on the sub menu select 'All' to see all HTTP requests. Also click on table header row that starts with Name, right-click on it, and select the Protocol option. Then reload the page to see Firebug populate a waterfall. 

Now you should see h2 (which stands for HTTP/2) in a new column for your website serving HTTP/2 content.

When inspecting a request's HTTP headers, you will also see the header value X-Firefox-Spdy: h2 

**Image Credit:**
 - Surfer: https://unsplash.com/@seefromthesky
 - Rooster:https://unsplash.com/@heytowner
 - Flowers:https://unsplash.com/@charlieharutaka
