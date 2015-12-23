# docker-tools
Simple scripts for working with Docker

## Programs

* dt-images-clean
    - This command will remove dangling images (images with no tag).
* dt-nuke
    - This command will stop and remove all containers, delete all images, and delete all volumes.
* dt-stop
    - This command will stop all running docker containers.
* dt-version
    - This command will show the versions of docker client/server, machine, and compose.
* dt-volumes-clean
    - This command will remove dangling volumes (volumes with no associated containers).

## Installation

* Clone the repository to your local system: `git clone git@github.com:fenderton/docker-tools.git`
* Add the `bin/` folder to your local `PATH` env variable.
