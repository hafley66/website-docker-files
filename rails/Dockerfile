FROM ruby:2.3.1

ENV APP /rails
RUN mkdir $APP
WORKDIR $APP

ENV PATH=/rails/bin:$PATH

COPY ./ $APP
