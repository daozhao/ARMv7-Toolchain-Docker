# ARMv7 developer environment

Base on Ubuntu 12.04.5 ，include developer tool for ARMv7.

include: vi,ssh,scp,git,hg

### Get docker 

docker pull [daozhao/armv7-toolchain](https://registry.hub.docker.com/u/daozhao/armv7-toolchain/)

### Start docker
docker run -d -p 2222:22 -v /host/folder:/home/data daozhao/armv7-toolchain

### Use the docker
ssh -p 2222 root@127.0.0.1  (password: root )


#ARMv7开发环境

ARMv7开发环境，基于Ubuntu12.04.5版本创建的。集成了基本的编译工具和开发工具。

包括 vi、ssh、scp、git、hg等常用工具。

### 获取docker 

docker pull [daozhao/armv7-toolchain](https://registry.hub.docker.com/u/daozhao/armv7-toolchain/)

### 启动docker

docker run -d -p 2222:22 -v /host/folder:/home/data daozhao/armv7-toolchain

### 使用：
ssh -p 2222 root@127.0.0.1  (password: root )




