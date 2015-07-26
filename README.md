# HttpServers
Python3 HTTPS Web Server Class

Based on Python3 standard http.server lib.

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

## License
*HttpServers* is distributed under the MIT license.
