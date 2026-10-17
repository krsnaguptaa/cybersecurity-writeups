# HTTP
HTTP = protocol for accessing websites
HTTPS = encrypted version

URL: scheme://host:port/path?querystring

METHODS:
GET = retrieve | POST = create
PUT = update | DELETE = remove

STATUS CODES:
100-199 = informational
200-299 = success
300-399 = redirects
400-499 = client errors (401=unauth, 403=forbidden, 404=notfound)
500-599 = server errors

REQUEST HEADERS:
Host, User-Agent, Content-Length,
Accept-Encoding, Cookie

RESPONSE HEADERS:
Set-Cookie, Cache-Control,
Content-Type, Content-Encoding

COOKIES:
HTTP is stateless = server forgets you
Cookies fix this = store session data
Security risk = cookie theft = attacker logs in as you
