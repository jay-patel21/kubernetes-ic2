#define the base image for our project
FROM python:3.9-slim

# define the directory inside the container
# where we will put our all code
WORKDIR /app

# copy project files to workdir
COPY . .

# install depedencies of the projects
RUN pip install -r requirements.txt

# Expose the port for communication
EXPOSE 5000

# Instructions to run the application
CMD ["python", "main.py"]