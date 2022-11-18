The idea of the program is to keep a running set of every url that has been visited, as well as a set of every URL seen but not yet visited.

Notes on HTTP for self:\
HTTP used to transmit resources - uRl
use http parser
Must use CRLF in string literals, CR - \r, LF - 
Can just use Path, HTTP proxies would use whole URL

Allowed: urllib.parse, html, html.parser, xml

Initial request line: GET /path/to/file/index.html HTTP/1.0
HTTP1.1 needs the host header - e.g. Host: www.host1.com:80

https://piazza.com/class/l7kwgqgh3pd6vc/post/616

General Format:

    an initial line,
    zero or more header lines,
    a blank line (i.e. a CRLF by itself), and
    an optional message body (e.g. a file, or query data, or query output). 
Initial lines and headers should end in CRLF

gzip decoder needs entire data chunk to decode properly 
