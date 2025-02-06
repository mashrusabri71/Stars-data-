# Stars-data-
# Download Dockerfile and devcontainer.json files
curl -Slo .devcontainer/Dockerfile https://raw.githubusercontent.com/devcontainers/images/main/src/javascript-node/.devcontainer/Dockerfile

curl -Slo .devcontainer/devcontainer.json https://raw.githubusercontent.com/devcontainers/images/main/src/javascript-node/.devcontainer/devcontainer.json

# rebuild the dev container
gitpod env devcontainer rebuild
