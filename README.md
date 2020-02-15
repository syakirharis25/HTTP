# HTTP
My works related to Hypertext Transfer Protocol (HTTP).

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [HTTP status codes.](#statuscodes)
4. [GitHub notes.](#github)

<a name="introduction"></a>
## 1. Introduction.
<img src="http.png" height="100"> 
The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources that the user can easily access, for example by a mouse click or by tapping the screen in a web browser.<br /><br />

Development of HTTP was initiated by Tim Berners-Lee at CERN in 1989. Development of early HTTP Requests for Comments (RFCs) was a coordinated effort by the Internet Engineering Task Force (IETF) and the World Wide Web Consortium (W3C), with work later moving to the IETF. HTTP is stateless, every request is completely independent, similar to transactions. Programming, local storage, cookies, sessions are used to create enhanced user experiences.

HTTP/1.1 was first documented in RFC 2068 in 1997. That specification was obsoleted by RFC 2616 in 1999, which was likewise replaced by the RFC 7230 family of RFCs in 2014.

HTTP/2 is a more efficient expression of HTTP's semantics "on the wire", and was published in 2015; it is now supported by major web servers and browsers over Transport Layer Security (TLS) using an Application-Layer Protocol Negotiation (ALPN) extension where TLS 1.2 or newer is required.

HTTP/3 is the proposed successor to HTTP/2, which is already in use on the web, using UDP instead of TCP for the underlying transport protocol. Like HTTP/2, it does not obsolete previous major versions of the protocol. Support for HTTP/3 was added to Cloudflare and Google Chrome (Canary build) in September 2019, and can be enabled in the stable versions of Chrome and Firefox (since version 72, January 2020).

<a name="references"></a>
## 2. Official references websites. <br />
The European Organization for Nuclear Research (French: Organisation européenne pour la recherche nucléaire), known as CERN official website : https://home.cern <br />
World Wide Web Consortium (W3C) official website : https://www.w3.org <br />
Internet Engineering Task Force (IETF) official website : https://ietf.org <br />

**_HTTP related tools_** <br />
Security Headers : https://securityheaders.com <br />

**_HTTP school resources_** <br />
Øredev : https://oredev.org <br />
Mozilla MDN Web Docs : https://developer.mozilla.org <br />

**_HTTP question and answer website_** <br />
Stack Overflow question and answer website : https://stackoverflow.com <br />

**_HTTP documentation by Mozilla_** <br />
X-Frame-Options by Mozilla : https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options <br />
CSP: frame-ancestors by Mozilla : https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/frame-ancestors <br />
User-Agent by Mozilla : https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/User-Agent <br />

**_HTTP documentation by W3C_**
Preload by W3C : https://w3c.github.io/preload/ <br />
Content Security Policy Level 3 by W3C : https://w3c.github.io/webappsec-csp/ <br />
Server Timing by W3C : https://www.w3.org/TR/server-timing/ <br />
Feature Policy by W3C : https://w3c.github.io/webappsec-feature-policy/ <br />
Origin Policy by W3C : https://wicg.github.io/origin-policy/ <br />

**_HTTP related articles_** <br />
How to enable the Telnet Client in Windows 10 by RootUsers : https://www.rootusers.com/how-to-enable-the-telnet-client-in-windows-10/ <br />
How to Install and Use TELNET in Ubuntu : https://quehow.com/how-to-install-and-use-telnet-in-ubuntu/3629.html <br />
X-Cache Header Explanation by Stack Overflow : https://stackoverflow.com/questions/3027492/x-cache-header-explanation/29772017 <br />
Hypertext Transfer Protocol (HTTP/1.1): Message Syntax and Routing : https://httpwg.org/specs/rfc7230.html <br />
HTTP Strict Transport Security (HSTS) : https://tools.ietf.org/html/rfc6797 <br />
Fetch : https://fetch.spec.whatwg.org <br />
HTTP Client Hints : https://httpwg.org/http-extensions/client-hints.html <br />
What is Transport Layer Security (TLS)? by Zeus Kerravala : https://www.networkworld.com/article/2303073/lan-wan-what-is-transport-layer-security-protocol.html <br />
An HTTP Status Code for Indicating Hints : https://tools.ietf.org/html/draft-ietf-httpbis-early-hints-05 <br />
The headers we don't want by Andrew Betts : https://www.fastly.com/blog/headers-we-dont-want <br />
What is an SSL Certificate? by Network Solutions : http://www.networksolutions.com/education/what-is-an-ssl-certificate/ <br />
HTTP Headers for Dummies by Envato Tut+ : https://code.tutsplus.com/tutorials/http-headers-for-dummies--net-8039 <br />

**_HTTP developers_** <br />
Andrew Betts : https://github.com/triblondon <br />
Steve Souders : http://stevesouders.com, https://github.com/stevesouders <br />

<a name="statuscodes"></a>
## 3. HTTP status codes.
**_1×× Informational_** <br />
100 Continue <br />
101 Switching Protocols <br />
102 Processing <br />
2×× Success <br />
200 OK <br />
201 Created <br />
202 Accepted <br />
203 Non-authoritative Information <br />
204 No Content <br />
205 Reset Content <br />
206 Partial Content <br />
207 Multi-Status <br />
208 Already Reported <br />
226 IM Used <br />

**_3×× Redirection_** <br />
300 Multiple Choices <br />
301 Moved Permanently <br />
302 Found <br />
303 See Other <br />
304 Not Modified <br />
305 Use Proxy <br />
307 Temporary Redirect <br />
308 Permanent Redirect <br />

**_4×× Client Error_** <br />
400 Bad Request <br />
401 Unauthorized <br />
402 Payment Required <br />
403 Forbidden <br />
404 Not Found <br />
405 Method Not Allowed <br />
406 Not Acceptable <br />
407 Proxy Authentication Required <br />
408 Request Timeout <br />
409 Conflict <br />
410 Gone <br />
411 Length Required <br />
412 Precondition Failed <br />
413 Payload Too Large <br />
414 Request-URI Too Long <br />
415 Unsupported Media Type <br />
416 Requested Range Not Satisfiable <br />
417 Expectation Failed <br />
418 I'm a teapot <br />
421 Misdirected Request <br />
422 Unprocessable Entity <br />
423 Locked <br />
424 Failed Dependency <br />
426 Upgrade Required <br />
428 Precondition Required <br />
429 Too Many Requests <br />
431 Request Header Fields Too Large <br />
444 Connection Closed Without Response <br />
451 Unavailable For Legal Reasons <br />
499 Client Closed Request <br />

**_5×× Server Error_** <br />
500 Internal Server Error <br />
501 Not Implemented <br />
502 Bad Gateway <br />
503 Service Unavailable <br />
504 Gateway Timeout <br />
505 HTTP Version Not Supported <br />
506 Variant Also Negotiates <br />
507 Insufficient Storage <br />
508 Loop Detected <br />
510 Not Extended <br />
511 Network Authentication Required <br />
599 Network Connect Timeout Error <br />

<a name="github"></a>
## 3. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/HTTP.git
$ cd HTTP/
$ git remote -v
$ git status
