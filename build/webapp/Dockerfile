FROM ruby:2.7.1-alpine3.11

RUN apk update && apk add \
		build-base \
		postgresql \
		postgresql-dev \
		postgresql-contrib \
		nodejs \
		bash \
		tzdata \
        curl-dev \
		curl \
		yarn \
		mc \
		&& rm -rf /var/cache/apk/*

WORKDIR /rails_app

COPY Gemfile* ./

RUN gem install bundler && \
    bundle install --retry=2 --jobs=20

COPY . .