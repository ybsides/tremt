# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Yuri Barros <yuribarros@tre-mt.jus.br>" \
      org.label-schema.name="tremt-varnish" \
      org.label-schema.description="Treinamento TRE-MT Varnish image." \
      org.label-schema.vendor="Yuri Barros"

COPY etc/varnish.vcl /etc/varnish/default.vcl
