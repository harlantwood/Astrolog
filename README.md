# Astrolog 7.60

This is a copy of the "official" version of Astrolog 7.60 (released April 9, 2023) described at: http://www.astrolog.org/astrolog.htm

The files here were copied from: http://www.astrolog.org/ftp/ast76src.zip

The changes in version 7.60 are described at: http://www.astrolog.org/ftp/updat760.htm

No modifications have been made to any of these files, and the only addition is this GITHUB format README.

## Docker

A Dockerfile is included to build a Docker image that can be used to run Astrolog in a Docker container.

To build the image and run interactively:

```bash
docker build -t astrolog .
docker run -it astrolog bash
```

Then within the container, run Astrolog:

```bash
# -H to see all options:
./astrolog -H

# or run interactively:
./astrolog
```
