# minimal jq
#

FROM       alpine
MAINTAINER Mike

ENV        VERSION 1.5

RUN           apk add --update curl \
           && curl -o /usr/local/bin/jq -L https://github.com/stedolan/jq/releases/download/jq-$VERSION/jq-linux64 \
           && chmod +x /usr/local/bin/jq  \
           #
           # clean up cached artefacts
           && rm -rf /var/cache/apk/* 

ENTRYPOINT ["/usr/local/bin/jq"]
CMD        ["--help"]
