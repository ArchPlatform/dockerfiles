  FROM python:3.8-buster

  ENV AWSCLI_VERSION='1.18.14'

  RUN pip install --quiet --no-cache-dir awscli==${AWSCLI_VERSION}
  RUN curl https://omnitruck.chef.io/install.sh | bash -s -- -P chefdk -c current
