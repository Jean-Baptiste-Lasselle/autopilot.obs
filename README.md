# Autopilot.obs

Experimenting OpenSUSE OBS


```bash


export URI_GIT=https://github.com/openSUSE/open-build-service
export OBS_RELEASE=2.10.1
git clone $URI_GIT
cd open-build-service
git checkout $OBS_RELEASE

# env ?
export CONTAINER_USERID=1001

docker-compose up -d

```
