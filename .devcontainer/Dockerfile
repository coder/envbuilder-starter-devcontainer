FROM ubuntu

RUN apt-get update
RUN apt-get install vim sudo curl -y

RUN useradd -m -s /bin/bash -G sudo coder
USER coder

# Let's make a boring prompt.
RUN echo "PS1='\u@\h> '" > ~/.bashrc
