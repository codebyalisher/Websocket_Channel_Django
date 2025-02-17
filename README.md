Install Redis via Docker:

You can also run Redis using Docker. If you have Docker installed, use the following command to pull the Redis image and run it:

docker run --name redis -p 6379:6379 -d redis
This will run Redis on your local machine and map the Redis port (6379) to your host machine. You can access Redis from your Django project by pointing it to localhost:6379
## Command for your project to run the asgi app
daphne websockets_channels.asgi:application