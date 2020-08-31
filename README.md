# dockerfile

## jib resolve the Docker time zone is 8 hours apart

### docker build --force-rm -t openjdk8-alpine-tz .

### docker tag openjdk8-alpine-tz registry.cn-beijing.aliyuncs.com/fengsli/openjdk8-alpine-tz

### docker push registry.cn-beijing.aliyuncs.com/fengsli/openjdk8-alpine-tz

### docker run -i -t --rm registry.cn-beijing.aliyuncs.com/fengsli/openjdk8-alpine-tz /bin/sh