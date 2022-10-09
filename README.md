# How-the-Web-Works-Exercise

1. HTTP stands for Hypertext Transfer Protocol (standard web) (How browsers and servers communicate)

2. URL stands for Uniform Resource Locator. It's an address for some internet resource

3. DNs stands for Domain Name Service which is a system that takes human-readable URLs and converts them into IP addresses

4. The query string allows one to pass key-value pairs into the URL, in the format ?key1=value1&key2=value2...

5. GET and POST are two HTTP verbs. GET gets some data from the server (most pages, search forms). POST sends some data to the server (pages that change data on the server)

6. An HTTP request is a request from a client to a server which follows the HTTP protocol (eg a request for HTML from news.google.com)

7. An HTTP response is a response from a server to a client which follows the HTTP protocol (eg sending back HTML/CSS/JS/etc)

8. HTTP headers provide additional information about the request or the response

  - Request Headers Examples: Host, User-Agent, Accept, Cookie, Cache-Control
  - Response Headers Exaples: Content-Type, Last-Modified, Set-Cookie, Cache-Control
  
9. The following happens when one types a URL in a browser:

   - The browser "resolves" the name into an IP address using DNS
   - The browser makes a request to that IP address, including headers (info about browser, any previous cookies, and other things)
   - The server sends a response (typically, HTML, with a status code (200 if it was successful))
   - The browser makes a DOM from that HTML, and finds any other resources needed (images, CSS, Javascript, etc)
   - The browser makes separate HTTP requests for those resources and receives response from the server for each 
