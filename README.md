# Toilet
Generates text banners, in a variety of typefaces, composed of conglomerations of smaller ASCII characters 

## Toilet (Project Info)
[Website](https://en.wikipedia.org/wiki/Toilet)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/toilet/)

## Build image
`$ docker build -t macabees/toilet:latest .`

## Docker Push
`$ docker push -t macabees/toilet:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm macabees/toilet "Hello World!"`

--OR--

`$ echo "Hello World!" | docker run -i --rm macabees/toilet --`

## Help
`$ docker run -it --rm macabees/toilet --help`
