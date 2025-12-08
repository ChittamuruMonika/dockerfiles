ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="docker" \
    STUDENT="monika"
ENV course=${COURSE}
RUN echo "course:${COURSE}, student:${STUDENT}"
CMD {"sleep", "100"}