# Containerized Phoenix Framework

A beautiful pair, Phoenix running in a Docker container. Develop awesome Elixir
software easily with this container from initiating the project through release.

## Usage

### Starting a new project

    docker run -it --rm \
      -v "$PWD":/app
      mix phoenix.new /app --module MyPhoenixApp
