# nginx_dynamic_port

Modified nginx container that changes the port before starting nginx. The default port is 80. In this case, just use the original nginx container. This is usuful mainly when the host network mode is used.
Run this container using the following command:

docker run -d -e PORT=9090 hmichopoulos/nginx
