FROM ruby:2.7.8
COPY src/ /home
WORKDIR /home
RUN bundle install
CMD ["ruby", "web.rb"]