FROM elixir:1.10

ENV DEBIAN_FRONTEND=noninteractive 
RUN curl -sL https://deb.nodesource.com/setup_12.x | bash -
RUN apt-get install -y nodejs inotify-tools
RUN mix local.hex --force
RUN mix local.rebar --force