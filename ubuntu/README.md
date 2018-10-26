# Ubuntu image with systemd enabled

You can use this image as a base container to run systemd services inside.

## Supported tags
 - `latest`, `18.04`
 - `16.04`

## Usage

Run the container as a daemon

`docker run -d --privileged --name systemd-ubuntu -v /sys/fs/cgroup:/sys/fs/cgroup:ro dr1s/molecule-ubuntu:18.04`

Enter to the container

`docker exec -it systemd-ubuntu bash`
