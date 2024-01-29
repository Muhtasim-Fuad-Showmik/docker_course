# Build

To build the docker image, execute:\
`docker build -t hello-docker .`\
Here dot is used assuming you are within the application folder. Also, a tag of "hello-docker" is used for the image

# Images

To view all images or verify if an image created was created successfully, you can run the following command:\
`docker images`\
This will list all successfully generated docker images.

# Run

To run the image generated for your application you can use the following command:\
`docker run hello-docker`

# Access OS Shell

You can access the shell of your OS and use commands inside by first executing the following command:\
`docker run -it hello-docker sh`\
You can for example execute the JS logic of the `hello.js` file from within this shell by running the following command:\
`node hello.js`
