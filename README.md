# Usage
This is deployment for [Ganime-FullBody](https://github.com/HRNPH/GANime-FullBody) API
Using AWS EC2 instance And Docker Container

you can complie and deploy the API by following the steps below:

docker build -t nameofyourimage .

docker images ls # To check if the image is built

docker run -p 8080:8080 nameofyourimage

if it worked you can search for tutorials on how to run the image on aws