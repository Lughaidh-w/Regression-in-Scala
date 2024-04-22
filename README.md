# Jupyter notebook in Scala

This repo creates a docker container with almond docker image.

The Bash script runs the docker compose in the background, and then connects to jupyter notebook.

Scala 2.12, 2.13, and 3.3 kernels are available.

Add .env file similar to below.
```PROJECT_DIR=/home/scala
NOTEBOOK_DIR=/home/scala/notebooks
NOTEBOOK_TOKEN=15558396
NOTEBOOK_PORT=8889```
