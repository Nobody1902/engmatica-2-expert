
# Installation

First run `docker build buildenv -t enigmatica2expert.buildenv` to build the docker image.

# Launch the server

Run `docker run -p 25565:25565 --rm -it -v %cd%:/root/env enigmatica2expert.buildenv /bin/bash -c "bash ./startforge.sh"` on Windows

Run `docker run -p 25565:25565 --rm -it -v $(pwd):/root/env enigmatica2expert.buildenv /bin/bash -c "bash ./startforge.sh"` on MacOS and Linux