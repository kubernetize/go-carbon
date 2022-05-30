FROM scratch

LABEL org.opencontainers.image.authors "Richard Kojedzinszky <richard@kojedz.in>"
LABEL org.opencontainers.image.source https://github.com/kubernetize/go-carbon

COPY go-carbon /

COPY assets/ /

USER 17230

CMD ["/go-carbon", "-config", "/etc/go-carbon/go-carbon.conf"]
