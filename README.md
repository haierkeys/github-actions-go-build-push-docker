# Go Project Multi-platform Cross-build & Github Release & Docker Build & Push Container Registry
===

本项目是一个用于验证 基于 Go 代码项目 在 Github Actions 进行 CI/CD 相关的例子.. 

**项目目标:**

1. 在 Github Actions 实现多平台交叉构建,且支持 CGO
2. 构建完成后自动打包 发布 Github Release
3. 根据构建好的 Go 执行程序 构建 docker 容器镜像
4. 推送到 Github 容器镜像仓库
5. 推送到 官方 DockerHub 容器镜像仓库

This project is an example for validating CI/CD workflows for a Go-based codebase using GitHub Actions.

**Project Goals:**

1. Implement multi-platform cross-compilation in GitHub Actions, including support for CGO.  
2. Automatically package and publish builds to GitHub Releases after the build is completed.  
3. Build Docker container images based on the compiled Go executable.  
4. Push the Docker images to the GitHub Container Registry.  
5. Push the Docker images to the official DockerHub Container Registry.  
