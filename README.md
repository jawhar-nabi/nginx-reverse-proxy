# nginx-reverse-proxy

This a configuration for reverse proxy.
This configuration will redirect all requests like website.com/something to a port that is not accessible from outside our virtual machine.

this example redirect all /back to :8000 port

It also redirect all http to https and contains ssl configuration with certbot