# A very tiny curl setup

based on alpine. The complete image is just over 8 MB big ...

Run a container from this image like:

    docker run --rm mwendler/curl

which should display the installed curl version:

    curl 7.42.1 (x86_64-alpine-linux-musl) libcurl/7.42.1 OpenSSL/1.0.2d zlib/1.2.8 libssh2/1.5.0
    Protocols: dict file ftp ftps gopher http https imap imaps pop3 pop3s rtsp scp sftp smb smbs smtp smtps telnet tftp
    Features: IPv6 Largefile NTLM NTLM_WB SSL libz TLS-SRP UnixSockets


Have fun!
