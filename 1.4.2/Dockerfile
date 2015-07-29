FROM dev-iojs:latest

#Install prerequiites
RUN wget https://storage.googleapis.com/golang/go1.4.2.linux-amd64.tar.gz && \
    tar -C /usr/local -xzf go1.4.2.linux-amd64.tar.gz && \
    cat "export GOROOT=/usr/local/go" >> /root/.bashrc && \
    cat "export GOPATH=$HOME/go" >> /root/.bashrc && \
    cat "export PATH=$PATH:$GOROOT/bin:$GOPATH/bin" >> /root/.bashrc

#Define default command
CMD ["bash"]
