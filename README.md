## List of Docker aliases

### Available aliases


```bash
# List images
alias di="docker images"

# List containers
alias dps = "docker ps"

# List all containers (not only running)
alias dpsa = "docker ps -all"

# Get container IP
alias dip="docker inspect --format '{{ .NetworkSettings.IPAddress }}'"

# Remove all images
alias drmi = "docker rmi $(docker images -q)"

# Remove dangling images
alias drmig = "docker images prune"

# Remove all containers
alias drm = "docker rm $(docker ps -qa)"

# Remove all containers (force the removal of a running container)
alias drmf = "docker rm -f $(docker ps -qa)"

# Execute interactive container
alias dex = "docker exec -it"

```


