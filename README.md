# Distroboxes

Distrobox images that I use.

## Requirements

### Distrobox

` curl -s https://raw.githubusercontent.com/89luca89/distrobox/main/install | sh -s -- --prefix ~/.local `

## How to use
Start with `source ./sourceme`

The scripts in sourceme autodetects podman (defult) or docker, set DBX_CONTAINER_MANAGER to choose manually.

### Build images

`buildimage ./ubuntu-distrobox/20.04` Builds an image with name ubuntu-distrobox and tag 20.04.

### Save images

`saveimage ./ubuntu-distrobox/20.04` Saves an already built image to a tar.gz file.

