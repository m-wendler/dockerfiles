# An image for wget.
#
# e.g.:  `docker run --rm mwendler/wget -V`

FROM        alpine

MAINTAINER  Mike


# install openssl and the complete wget
RUN            apk --update add openssl wget \
            \
            # clean up cached artefacts
            && rm -rf /var/cache/apk/*


# the application
ENTRYPOINT  ["wget"]
