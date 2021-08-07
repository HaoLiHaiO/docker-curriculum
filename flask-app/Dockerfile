FROM python:3

# set dir for app
WORKDIR /usr/src/app

# copy all files to container
COPY . .

# install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# specify port number to expose
EXPOSE 5000

# cmd for running the app
CMD ["python", "./app.py"]