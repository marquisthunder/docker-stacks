# Copyright (c) Jupyter Development Team.
# Distributed under the terms of the Modified BSD License.
FROM daocloud.io/creditx/all-spark-notebook

MAINTAINER Jupyter Project <jupyter@googlegroups.com>

USER root

RUN curl --silent --location https://deb.nodesource.com/setup_4.x | sudo bash - && \
    apt-get install --yes nodejs npm && \
    npm update -g npm && \
    npm install -g bower
