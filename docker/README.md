# bear-docker-container

This Python script facilitates running a Docker container with specified resource limits and mounts the current working directory into the container. The container will be launched interactively with a Bash shell.

### Script Details

- **Arguments**:
  - `image_id`: The ID of the Docker image to use (required).
  - `--container_name`: Optional name for the container.
  - `--memory_limit`: Memory limit for the container (default is `2g`).
  - `--cpu_limit`: CPU limit for the container (default is `4`).

- **Docker Run Command**:
  - The script constructs and executes a `docker run` command with the specified options.
  - The container is run interactively with the `-it` option and is removed after exit using the `--rm` option.
  - The current directory is mounted into the container using the `-v` option.
  - Memory and CPU limits are set with the `-m` and `--cpus` options, respectively.

# Setting up

Ensure you have the following installed:
- **Python 3.x**: [Python Installation Guide](https://www.python.org/downloads/)
- **Docker**: [Docker Installation Guide](https://docs.docker.com/get-docker/)


Assuming that you`ve cloned this repo: 

1. Run the following command to make sure that user can execute script:
     ```sh
     sudo chmod u+x bear-docker-container
     ```

2. Place script in local binary directory:
     ```sh
     sudo cp bear-docker-container /usr/local/bin/
     ```

3. You can now run the script at any time by typing:
     ```sh
     bear-docker-container <image id>
     ```
