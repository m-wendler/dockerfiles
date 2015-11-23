# a minimal ruby setup based on alpine
#
# For your specific ruby applications create another image based on
# this one and set volumes, install gems, etc there ...

FROM        alpine

MAINTAINER  Mike 


# install ruby, ruby-io-console and bundler
RUN            apk update \
            && apk upgrade \
            && apk add ruby ruby-io-console \
               # (if you don't need bundler than leave it out and save 1 MB)
               ruby-bundler \
            \
               # clean up after use ...
            && rm /var/cache/apk/*

CMD         ["ruby", "--version"]
