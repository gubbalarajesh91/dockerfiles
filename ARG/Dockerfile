ARG version
FROM almalinux:${version}
#FROM almalinux:${version:-8}
#default version
ARG course=Docker
ARG Triner
ARG duration=120HRS
ENV duration=${duration}
RUN echo "Course is ${course}, Triner is ${Triner}, Duration is: ${duration}"
#RUN cat /etc/*release
CMD [ "sleep","120" ]
#docker build -t arg:v1.0.0 --build-arg version=8 .
#docker build -t arg:v1.0.0 --build-arg version=8 --build-arg course=DevOps --build-arg Trainer=Shiva .