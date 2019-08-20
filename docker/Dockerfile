ARG GOLANG_BASE=alpine
ARG GOLANG_BASE_DIGEST=

FROM $GOLANG_BASE$GOLANG_BASE_DIGEST

RUN mkdir /bcbin/
WORKDIR /bcbin/

ADD s3 ./
ADD cloudformation ./

RUN chmod +x ./*