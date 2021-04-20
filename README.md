# hassio-docker-openconnect-global-protect

docker run --rm --privileged -v \
~/.docker:/root/.docker homeassistant/amd64-builder \
--all -t

docker build --build-arg BUILD_FROM="homeassistant/amd64-base:latest" \
-t lopesdasilva/hassio-docker-openconnect-gp-aarch64:0.2 .


docker push lopesdasilva/hassio-docker-openconnect-gp-aarch64:0.2

