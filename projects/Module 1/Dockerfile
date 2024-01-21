## can use the command: docker run hello-world
# Can use the above to test if docker is installed correctly

# docker run -it python:3.9
# Can run a specific version of python within Docker

# In order to download and install modules, I need to install it via an entrypoint:
# docker run -it --entrypoint=bash python:3.9
# Then I can run the regural pip install: pip install pandas

# If running locally, when I exit the docker image, and try to reload the library - it wont be there, so have to list out the instructions

FROM python:3.9

RUN pip install pandas

ENTRYPOINT [ "bash" ]

# then can build the docker image:
# docker build test:pandas .