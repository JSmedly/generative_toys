# jupyter_tf_dev
Instantiations of common generative models for testing and playing with. Primarily based on the models shown in: 
https://keras.io/examples/generative/


To set up the docker environment, download the dockerfile and build the image with:
    docker build -t generative_toys . 

Run the docker container with:
    docker run --name generative_toys --gpus all --rm -v ./jupyter:/workspaces/generative_toys generative_toys

If using VS Code, it is possible to click the box in the bottom left hand corner of VS code and select the "reopen folder in container" option. This saves having to manually build the image and container.
