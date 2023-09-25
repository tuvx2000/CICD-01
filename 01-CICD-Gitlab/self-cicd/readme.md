# Self-CICD-Manifest
This repo contain Gitlab-Runner on ec2 + Variables

Variables:
- REGISTRY_USER: username of DockerHub
- REGISTRY_USER: password of DockerHub
- SSH_PRIVATE_KEY: private ssh key -> allow who have public key to connect
- user have: public ssh key in console -> to authen user with private key in local
- local store both: public and private key


- Dockerfile to build in CI
- make file to test in CI
- And contain source code of apps