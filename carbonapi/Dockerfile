FROM scratch

LABEL org.opencontainers.image.authors "Richard Kojedzinszky <richard@kojedz.in>"
LABEL org.opencontainers.image.source https://github.com/kubernetize/go-carbon

COPY carbonapi /

COPY assets/ /

USER 17231

CMD ["/carbonapi", "-config", "/etc/go-carbon/carbonapi.conf"]
