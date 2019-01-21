FROM abiosoft/caddy
EXPOSE 80 443 2015
# COPY builder.sh /usr/bin/builder.sh

# CMD ["/bin/sh", "/usr/bin/builder.sh"]

ENTRYPOINT ["/usr/bin/caddy"]
COPY Caddyfile /etc/Caddyfile
CMD ["--conf", "/etc/Caddyfile", "--log", "stdout"]