# Traefik Micro Frontend routing (using Deno web servers)

An example of how to use Traefik with Docker Compose to make routing easier.

## Run

1. Build and run the stack with Docker Compose - `docker compose up --build`
2. Navigate to [localhost:8080](http://localhost:8080) to see the Traefik dashboard
3. Navigate to [deno-mfe.localhost](http://deno-mfe.localhost) to see the first app

## Why?

Working with a single web app that handles routing is pretty straightforward, but what about multiple web apps? Traefik can simplify this process and give you a nicer experience overall. Read my [article to learn more about setting up Traefik and Docker Compose](https://blog.sethcorker.com/traefik-routing-for-web-apps) and why you'd want to do this and some more explanation on the code
