FROM pandoc/ubuntu:2.11.3.1

RUN apt-get update \
  && apt-get install -y tzdata \
  && apt-get install -y wkhtmltopdf \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

