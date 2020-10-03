# App Overview

[![Build Status](https://travis-ci.org/NurOrNuLL/docker-react.svg?branch=main)](https://travis-ci.org/NurOrNuLL/docker-react)

## run Dockerfile.dev

`docker-compose up --build -d`

## run Dockerfile.prod

`docker build -f Dockerfile.prod .`
`docker run -it -p 8080:80 {docker id}`
