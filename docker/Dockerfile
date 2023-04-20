FROM busybox:latest
ARG repoA=v0.0.1
ARG repoB=v1.0.0
RUN echo "repoA: $repoA"
RUN echo "repoB: $repoB"
ENV repoA=$repoA
ENV repoB=$repoB

ADD sample /root/sample