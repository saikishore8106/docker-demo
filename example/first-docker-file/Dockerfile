from ubuntu:latest

# set the working directory in the image
workDIR /app

# copy the file from host file system to the images
COPY. /app

#install necessery packages
RUN apt-get update && apt-get install -y python3 python3-pip

#set environment variables
ENV NAME world

# Run a command to run application
CMD ["PYTHON3" , "app.py"]

