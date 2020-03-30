FROM codenvy/cpp_gcc
COPY . /usr/src/myapp1
WORKDIR /usr/src/myapp1
RUN sudo chown -R "$USER:" /usr/src/myapp1/
RUN sudo chmod -R 777 /usr/src/myapp1/
RUN g++ -o myapp demo.cpp
CMD ["./myapp"]
