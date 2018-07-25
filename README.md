# dirty-docker-hack

(Yes there's missing code in this repo)

This is meant to replicate a load balancing application running on three virtual machines, it is a nonsensical dirty hack to benchmark Docker and compare it to data we already have.

You can build the image with:

    docker build -t http-cimsi httpd

And run it with:

    docker run -d http-cimsi      
