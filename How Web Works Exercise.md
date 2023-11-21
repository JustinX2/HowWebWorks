Part One: Solidify Terminology
In your own terms, define the following terms:

What is HTTP?
Hypertext Transfer Protocol that is a protocol used to transfer data over the web
What is a URL?
Uniform Resource Locator is a unique address for identifying a resource on the Internet. It includes protocol, domain name, path, and query string
What is DNS?
Domain Name System translates domain names into IP addresses (numbers) that computers and servers can identify each other
What is a query string?
Query string is a part of a URL that comes after the question mark (?). For example, search terms after the question mark
What are two HTTP verbs and how are they different?
GET request: Requests data from a specified resource. It retrives information without affecting the data on the server.
POST request: Sends data to a server to create/update a resource. It often changes the state of the data on the server.
What is an HTTP request?
HTTP request is a message sent from a client to a server to request a specific resource
What is an HTTP response?
HTTP response is a message sent from a server to a client in response to a request. It includes a status code, headers, and an optional response body.
What is an HTTP header? Give a couple examples of request and response headers you have seen.
HTTP header is a line of information that provides additional details about an HTTP request or response. HTTP header includes Content-Type, Content-Length, and Cache-Control.
What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
1. Browser reads the URL and extracts the domain name.
2. DNS changes the human readable domain name into a number IP address.
3. Browser establishes a connection to the server using the number IP address and sends an HTTP request.
4. Server processes the request, generates an HTTP response, and sends the response back to the browser.
5. Browser receives the response, interprets the HTML response, and loads this response into the web page.

Part Two: Practice Tools

GET request using curl:I was unable to install Curl on windows. 
I don't have Linux but here is the code to get IP using dig on Linux: dig icanhazdadjoke.com
server using python: python3 -m http.server

Part Three: Explore Dev Tools

Create an HTML form with GET method:
I was able to preview the form using Rested chrome extension on "icanhazdadjoke.com". 
