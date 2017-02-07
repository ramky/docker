FROM base-image

# Install rbenv
RUN git clone https://github.com/sstephenson/rbenv.git /root/.rbenv
RUN git clone https://github.com/rbenv/ruby-build.git /root/.rbenv/plugins/ruby-build
ENV PATH $PATH:/root/.rbenv/bin:/root/.rbenv/shims

# Install ruby version 2.3.1
RUN rbenv install 2.3.1
RUN rbenv global 2.3.1

# Install gems
RUN gem install bundler
RUN gem install rails -v 5.0.1
