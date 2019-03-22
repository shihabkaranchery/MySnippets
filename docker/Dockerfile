FROM ubuntu:latest
# FROM ubuntu:16.04
CMD echo "Hi this is the first message from my docker......."

# for run the command inside the docker
RUN echo "hi this is to a file" > test.txt

# for install new packages
RUN apt-get update && apt-get install -y --no-install-recommends vim && apt-get clean

# for build this image type
# sudo docker build . -t <image_name>