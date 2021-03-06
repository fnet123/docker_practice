# 本章小结
本章讲解了典型操作系统镜像的下载和使用。

除了官方的镜像外，在 DockerHub 上还有许多第三方组织或个人上传的 Docker 镜像。

读者可以根据具体情况来选择。一般来说：

* 官方镜像体积都比较小，只带有一些基本的组件。 精简的系统有利于安全、稳定和高效的运行，也适合进行定制化。
* 个别第三方（如 tutum，已被 Docker 收购）镜像质量也非常高。这些镜像通常针对某个具体应用进行配置，比如：包含 LAMP 组件的 Ubuntu 镜像。
* 处于安全考虑，几乎所有官方制作的镜像都没有安装 SSH 服务，无法使用用户名和密码直接登录。

后续章节中，笔者将介绍如何创建一个带 SSH 服务的 Docker 镜像。
