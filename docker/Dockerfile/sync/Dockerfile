ARG NODE_VERSION
ARG PYTHON_VERSION

FROM node:${NODE_VERSION}

RUN apt update && apt install ffmpeg -y && apt-get install -y python3 pipx

# FROM python:${PYTHON_VERSION}

RUN pipx install youtube_dl
