FROM ruby:2.6.5

WORKDIR /app

COPY \
  Gemfile \
  Gemfile.lock \
  /app/
RUN bundle install --jobs=4 --path=/bundle
