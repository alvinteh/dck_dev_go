FROM dev-iojs:latest

#Install prerequiites
RUN wget https://storage.googleapis.com/golang/go1.5.linux-amd64.tar.gz && \
    tar -C /usr/local -xzf go*.linux-amd64.tar.gz && \
    touch /root/.bashrc && \
    echo "export PATH=$PATH:/usr/local/go/bin" >> /root/.bashrc && \
    rm go*.linux-amd64.tar.gz

#Define default command
CMD ["bash"]
