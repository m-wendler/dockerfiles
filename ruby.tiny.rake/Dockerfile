# a minimal ruby with rake setup based on alpine
#
# For your specific ruby applications create another image based on
# this one and set volumes, install gems, etc there ...

FROM        mwendler/ruby.tiny

MAINTAINER  Mike


# install rake
RUN            apk update \
            && apk upgrade \
            && gem install rake --no-document \
            \
               # clean up after use ...
            && rm /var/cache/apk/*


# default command
CMD         ["rake", "--version"]
