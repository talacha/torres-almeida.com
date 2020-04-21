# Use a stock Docksal image as the base
FROM docksal/cli:2.1-php7.3

# Install hugo 0.69
RUN wget -q https://github.com/gohugoio/hugo/releases/download/v0.69.0/hugo_0.69.0_Linux-64bit.deb -O /tmp/hugo.deb \
    && dpkg -i /tmp/hugo.deb