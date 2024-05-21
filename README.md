# -Cat-Dog-Classification-Using-Docker
This project demonstrates a simple web application that predicts whether an uploaded image contains a cat or not. It uses a pretrained machine learning model (h5 format). It is deployed using Flask and containerized using docker.
## Docker Deployment

Build the Docker image: docker image build -t catdog .

Run the Docker container: docker run -p 5000:5000 -d catdog

Access the app at http://127.0.0.1:5000/upload

## Usage

Upload an image using the web form.

The app will predict whether the image contains a cat or not.

## Demo Video


## Acknowledgement and Links

DockerHub Link: https://hub.docker.com/repository/docker/arulyashwanth/flask_docker/general

Model Download link: https://huggingface.co/spaces/Sa-m/Dogs-vs-Cats/blob/main/best_model.h5
