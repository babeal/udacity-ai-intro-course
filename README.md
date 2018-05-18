# AI programming with Python

Contains the project work for the AI programming with Python course on Udacity. [link](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089)

Date - March 6th, 2018

## Details

Instead of installing python 3.5 on my mac system I want to containerize the execution environment using Docker.  I think this is a good time to start learning both technologies. So hopefully this works.  

## Getting Started

Download the anaconda 3 image

    $ docker pull continuumio/anaconda3

    $ docker run -i -t --rm continuumio/anaconda3 /bin/bash

The command I ran to mount the project directory into the container is:

    $ docker run -i -t --rm -v /Users/brandt/dev/projects/udacity-ai-intro-course:/my-project continuumio/anaconda3 /bin/bash

And even simplier

    $ bash start-container.sh

## Links
[Anaconda - Docker](https://medium.com/@patrickmichelberger/getting-started-with-anaconda-docker-b50a2c482139)

