# syntax=docker/dockerfile:1
FROM varnish:7.4

LABEL maintainer="kinsley <kinsley.davis@gmail.com>" \
      org.label-schema.name="trece-varnish" \
      org.label-schema.description="Treinamento TRE-CE Varnish image." \
      org.label-schema.vendor="kinsley"

COPY etc/varnish.vcl /etc/varnish/default.vcl
