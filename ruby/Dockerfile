FROM rwade/alpine:3.5

RUN apk add ca-certificates ruby ruby-bigdecimal ruby-io-console ruby-irb ruby-json ruby-libs ruby-rake ruby-bundler ruby-dev build-base

RUN gem sources --add https://gems.ruby-china.org/ --remove https://rubygems.org/

RUN echo "gem: --no-rdoc --no-ri" > ~/.gemrc
