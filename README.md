Docker build for Unity MasterServer
================================

This repository provides Dockerfile for [Unity MasterServer][0] 

### Status
- Unity MasterServer: 2.0.1f1
- CentOS: 6

Built images are uploaded to [index.docker.io][1]

### Usage:

 - Install Docker: [http://docs.docker.io/][2]
 - Execute
 `docker run -d --name MasterServer -p 23466:23466 shaker/unity-master-server`
 - MasterServer will be running on 23466
 - Stop and start again
   - `docker stop MasterServer`
   - `docker start MasterServer`

  [0]: http://unity3d.com/master-server/
  [1]: https://index.docker.io/u/shaker/
  [2]: http://docs.docker.io/en/latest/ "docs.docker.io"

