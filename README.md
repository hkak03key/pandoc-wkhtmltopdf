# pandoc-wkhtmltopdf
## overview
pandoc Dockerfile for wkhtmltopdf.
these use [pandoc docker image](https://hub.docker.com/u/pandoc).

## topics
### font install
this image is not installed Japanese fonts.
but you can install font by mounting to `/root/.fonts`

for example:
```
docker run --rm --volume "${host-font-dir}:/root/.fonts" pandoc-wkhtmltopdf README.md README.pdf
```
