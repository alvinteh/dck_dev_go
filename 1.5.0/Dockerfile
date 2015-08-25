FROM dev-iojs:latest

#Install prerequiites
RUN wget https://storage.googleapis.com/golang/go1.5.linux-amd64.tar.gz && \
    tar -C /usr/local -xzf go*.linux-amd64.tar.gz && \
    touch /root/.bashrc && \
    echo "export PATH=$PATH:/usr/local/go/bin" >> /root/.bashrc && \
    rm go*.linux-amd64.tar.gz && \
    mkdir -p /root/go/bin && \
    mkdir -p /root/go/pkg && \
    mkdir -p /root/go/src

#Define default command
CMD ["bash"]
