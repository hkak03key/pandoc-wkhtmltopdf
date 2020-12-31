FROM pandoc/ubuntu:2.11.3.1

RUN DEBIAN_FRONTEND=noninteractive \
  && apt-get update \
  && apt-get install -q -y keyboard-configuration \
  && apt-get install -q -y tzdata \
  && apt-get install -q -y wkhtmltopdf \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

