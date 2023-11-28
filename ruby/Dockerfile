FROM ruby:2.7.6
COPY src/ /home
WORKDIR /home
RUN bundle install
CMD ["ruby", "web.rb"]