FROM codenvy/cpp_gcc
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN sudo chown -R "$USER:" /usr/src/myapp/
RUN sudo chmod -R 777 /usr/src/myapp/
RUN gcc -o myapp demo.c
CMD ["./myapp"]
