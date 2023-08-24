## Docker walking skeleton for Python

Build image:

`docker build -t python-app .`

Run built image:

`docker run -it --rm python-app`

Run and build in one command:

`docker run --rm -it $(docker build -q .)`
# docker-python-walking-skeleton
# docker-python-walking-skeleton
