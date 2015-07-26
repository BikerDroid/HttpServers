# HttpServers (Python3)

HTTPS/HTTP Web Server Class using Python3 standard libs.

An offspring from a project using CGI for a WebGUI interface.

## Usage

**HTTP Web Server (ip='localhost', port=8000):**

`HttpServers().start()`

**HTTP Web Server with CGI (ip='localhost', port=8000):**

`HttpServers(use_cgi=True).start()`

**HTTPS Web Server (ip='localhost', port=1443):**

`HttpServers(use_ssl=True).start()`

**HTTPS Web Server with CGI (ip='localhost', port=1443):**

`HttpServers(use_ssl=True, use_cgi=True).start()`

**Shut Down Server**

```
http://localhost:8000/shutdown/
https://localhost:1443/shutdown/
```

**Open WebBrowser at Server Start:**

```
HttpServers(start_browser=True).start()
HttpServers(use_cgi=True, start_browser=True).start()
HttpServers(use_ssl=True, start_browser=True).start()
HttpServers(use_ssl=True, use_cgi=True, start_browser=True).start()
```

## Self-Signed SSL Certificate

If you want to generate your own Self-Signed SSL Certificate in PEM format, visit [cert-depot.com](http://www.cert-depot.com/).

The code has a very generic PEM Certificate and Key included for demo (TLS 1.2, RSA).

## License
*HttpServers* is distributed under the MIT license.
