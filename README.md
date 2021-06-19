# cvm-docker-compose-yml

docker-compose.yml for fast setup on my CVM.

## CVM resources

|Item|Configuration|
|-|-|
|CPU Cores|2
|RAM|4G
|Swap|2G
|System volume| 50G
|Data volume| 100G
|Bandwidth|3M

## Docker components

|Name|Port|Reference|
|-|-|-|
|nextcloud|8000|https://github.com/nextcloud/docker
|gitlab|8929|https://docs.gitlab.com/omnibus/docker/
|pypiserver|8080|https://github.com/pypiserver/pypiserver#using-the-docker-image
|jupyter|8888|https://github.com/jupyter/docker-stacks
