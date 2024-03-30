# syntax=docker/dockerfile:1
FROM varnish:7.4

LABEL maintainer="Pedro Godoi <collective@plone.org>" \
      org.label-schema.name="plone-conference-website-2070-varnish" \
      org.label-schema.description="Plone Conference Website 2070 Varnish image." \
      org.label-schema.vendor="Pedro Godoi"

COPY etc/varnish.vcl /etc/varnish/default.vcl
