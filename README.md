# Mobilise-D Python Docker container ([Dockerhub](https://hub.docker.com/r/madlabfau/mobilise-python))

This repo contains the build instructions for a set of containers that can be used to package Python based Gait Algorithms.
All images use pinned versions of all primary dependencies to ensure reproducibility.

## python-general

Up to date python 3 env based on miniconda with the basic data science stack installed

## python-gaitpy

A python container to run [gaitpy](https://github.com/matt002/gaitpy). The general container can not be used for this, as the repo specifies strict dependencies.