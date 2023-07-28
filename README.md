# web-server-simulator
Simple Python 3 web server that responds to any web request with a random HTTP status code.


Usage(server)
```
python3 ./www-server-simulator.py
```

Usage(client)
```
# Looping example
while :; do curl -v http://127.0.0.1:8080/; sleep 1; done
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 410   Gone 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 401   Unauthorized 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 401   Unauthorized 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 407   Proxy Authentication Required 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 413   Content Too Large 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 424   Failed Dependency 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 226   IM Used 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 200   OK 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 409   Conflict 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 307   Temporary Redirect 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 302   Found 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
< HTTP/1.1 422   Unprocessable Content 
* Connection #0 to host 127.0.0.1 left intact
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to 127.0.0.1 (127.0.0.1) port 8080 (#0)
> GET / HTTP/1.1
> Host: 127.0.0.1:8080
> User-Agent: curl/7
> Accept: */*
> 
```
