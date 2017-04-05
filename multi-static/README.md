# multi-static

Docker image serving multiple static sites simultaneously.

# Usage

```
docker run -d -v /data/sites:/var/www/html -p 8080:80 rwade/multi-static
```

HTTP requests with hostname `www.example.com` will be served from `/data/sites/www.example.com` automatically, you can serve as many static sites as possible.
