It seems like you're trying to format a `README.md` file for a Docker container project related to "whisper". Here's a more organized and better formatted version:

---

# Whisper Container

Create a Docker container and an API for Whisper.

## Prerequisites

- Install [Docker](https://www.docker.com/get-started).

## Docker Commands

Here are some basic Docker commands you might find useful:

- List Docker images: 
  ```
  docker images
  ```

- List running Docker containers: 
  ```
  docker ps
  ```

## Building the Image

### Linux:
```bash
sudo docker build -t <container_name> <path_if_not_in_current_directory_use_.>
```

### Windows:
```bash
docker build -t <container_name> <path_if_not_in_current_directory_use_.>
```

## Running the Container

To run the container:
```bash
docker run -p 8000:8000 <image_name>
```

---

Make sure you replace `<container_name>`, `<path_if_not_in_current_directory_use_.>`, and `<image_name>` with your actual values. If you need to add more details or more instructions, you can always expand this formatted README.