# Week 1 — App Containerization

# run docker in background with environment variables"
docker container run --rm -p 4567:4567 -d -it -e FRONTEND_URL='*' -e BACKEND_URL='*' backend-flask

# other methods:
docker run --rm -p 4567:4567 -it backend-flask
docker run --rm -p 4567:4567 -it -e FRONTEND_URL='*' -e BACKEND_URL='*' backend-flask
docker run --rm -p 4567:4567 -it  -e FRONTEND_URL -e BACKEND_URL backend-flask
