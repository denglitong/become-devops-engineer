[Become A DevOps Engineer in 2023: [Detailed Guide]](https://devopscube.com/become-devops-engineer)

CN: https://www.infoq.cn/article/tgurwxuivdr1txxp390i

1. 了解 DevOps 文化

2. 学习 Linix 系统

  Red Hat Enterprise Linux (RHEL)

  具体来说你可以从以下几点内容开始学起：

  - 了解 Linux 的启动过程
  - 安装和配置 Web 服务器（Apache、Nginx、Tomcat 等），并学习 Web 服务器的工作原理。
  - 学习 Linux 进程的工作原理。
  - 学习 SSH 的工作原理。
  - 学习不同的文件系统。
  - 学习卷（Volume）在 Linux 中的工作方式。
  - 学习有关系统日志、监控和故障排除的信息。
  - 学习重要的协议（SSL、TLS、TCP、UDP、FTP、SFTP、SCP、SSH）
  - 学习管理服务，并尝试自己创建服务（Initd、Systemd）
  - 在 Web 服务器上托管静态/动态网站。
  - 设置负载均衡器和反向代理（Nginx、HA 代理等）
  - 搞一些破坏，并学习故障排除。

3. 了解基础设施组件的工作原理

网络:
  - 子网
  - 公共网络
  - 私有网络
  - CIDR标识
  - 静态/动态IP
  - 防火墙
  - 代理
  - NAT
  - 公有和私有DNS

VPN
  - 站点到站点VPN
  - 客户端到站点的VPN

负载平衡器
  - L5负载平衡器
  - L7负载平衡器
  - 负载平衡算法
  - 反向代理

高可用性
  - 集群
  - FailOver机制
  - 故障恢复

安全
  - PKI基础设施
  - SSL证书

存储:
  - SAN
  - 备份（Backups）
  - NFS

单点登录（SSO）
  - Active Directory/LDAP

4. 获得云上认证

AWS Certificated DevOps

5. 学习自动化

针对开发环境:
  - Vagrant
  - Docker Desktop
  - Minikube
  - Minishift

基础设施配置:
  - Terraform
  - CLIs （各云提供商的）

针对配置管理:
  - Ansible
  - Chef
  - Puppet
  - Saltstack

VM镜像管理:
  - Packer

6. 容器、分布式系统及服务网格

容器: Docker

集群编排工具: Kubernetes, Docker Swarm

Kubernetes 认证、Service Mesh

7. 日志与监控

常用日志栈:
  - Splunk
  - ELK

监控:
  开源工具: Prometheus, Nagios
  企业工具: AppDynamics, Datadog, SignalFx

8. 了解安全的最佳实践

AWS Cetified Security

9. 学习编码和脚本

脚本语言: Bash/Shell, Python, Golang

10. 学习 Git 及相关文档，了解 GitOps

Git 分支策略是任何应用程序发布过程的一个重要方面。

GitOps 是一种为云原生应用程序实现持续部署的方法。

11. 了解端到端应用程序交付生命周期

持续集成（Continuous Integration）

持续交付（Continuous Delivery）

持续部署（Continuous Deployment）

Jenkins, Travis CI, GoCD.

12. DevOps 与 SRE

DevOps 和 SRE 并不是两种相互竞争的软件开发和运维方法，而是旨在打破组织障碍以更快地交付更好的软件的密友。

13. 不同类型的“DevOps 团队”

中台团队（Central Platform Team）：

  负责按需提供基础设施。他们不负责应用程序，而是负责底层平台。通过持续的平台支持和监控来确保生产系统 24×7 全天候可用。此外，他们将致力于新的工具和自动化，以满足未来的需要。这个团队的最终用户将是开发或 App Ops 团队。所以它更多的是共同责任。

DevOps 团队:

  虽然“DevOps 团队”没有任何意义，但是组织用它来命名运维团队。这个团队通常与开发人员密切合作，并为多个开发团队提供服务。他们负责端到端的应用程序交付。

App Ops 团队:

  这个团队是特定工程团队的一部分，在一个对特定领域有很好了解的组织中，与特定项目密切合作。例如，支付团队。该团队负责部署和管理支付应用程序。平台管理将由中台团队或 DevOps 团队负责。

SRE 团队:

  该团队负责自动化、可用性、延迟、性能、效率、变更管理、监控、应急响应和容量规划。他们与开发人员密切合作，解决运维问题。该团队由具有开发背景的基础设施工程师组成。

14. 阅读，阅读，再阅读


[List of DevOps Blogs and Resources for Learning](https://devopscube.com/list-of-devops-blogs-and-resources/)
