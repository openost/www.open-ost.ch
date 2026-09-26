FROM lipanski/docker-static-website:latest

COPY web .
CMD ["/busybox-httpd", "-f", "-v", "-p", "3000"]
