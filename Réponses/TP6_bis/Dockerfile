# Docker-app/Dockerfile
FROM node:15.5.1-alpine
LABEL maintainer="GERARD Angelo"

# Create and change working directory
WORKDIR /app

# Add application requirements
#COPY requirements.txt .

# Install requirements
#RUN pip install -r requirements.txt

# Add application
COPY app.js .
#COPY config.py .

# Create a specific user to run the Python application
RUN adduser -D my-user -u 1001
USER 1000

# Launch application
ENTRYPOINT ["node"]
CMD ["app.js"]
#CMD ["node", "app.js"]
