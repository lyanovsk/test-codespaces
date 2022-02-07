# syntax = docker/dockerfile:1.3
FROM ubuntu:20.04

RUN --mount=type=cache,target=/var/cache/apt apt update && \
apt -y upgrade && apt -y install g++ make less htop git