docker build -f Dockerfile.dev .
docker run -p 3000:3000 -v $(pwd):/app e0fe5ba95ba3(image id)
docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app e0fe5ba95ba3(image id)

docker run 700d092e12bf npm run test (when you want to override the docker file command)

docker run -it bc99ab61b853 npm run test (it attribute gives full screen experience in the terminal)

docker ps (gets all the running container)
docker exec it <container id> npm run test
docker-compose up --build (build the docker-compose file if there is any changes)
docker exec -it 34f8b1dfc3a6 sh (opens up shell command for the container id)

nginx is used to serve the web application for production


