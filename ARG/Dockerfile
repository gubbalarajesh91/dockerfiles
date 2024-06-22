ARG version
FROM almalinux:${version}
RUN cat /etc/*release
CMD [ "sleep","120" ]
#docker build -t arg:v1.0.0 --build-arg version=8 .