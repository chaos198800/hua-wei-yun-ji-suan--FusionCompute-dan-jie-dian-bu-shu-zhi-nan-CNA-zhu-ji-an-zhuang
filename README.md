# 华为云计算 - FusionCompute 单节点部署指南（CNA主机安装）

本教程详细指导如何进行华为FusionCompute的单节点部署，专注于CNA（Computing Node Agent）主机的安装步骤。FusionCompute是华为云数据中心虚拟化平台的核心组件，它使IT基础设施能够高效地管理和分配，以支持云环境下的各种应用程序和服务。

## 准备阶段

在开始安装前，请确保：

- **资源下载**：下载必要的ISO安装文件和相关软件，包括CNA安装镜像，可在华为官方网站的企业用户软件下载区域找到相应版本。
- **实验环境**：需要一台兼容性良好的服务器（如ThinkPad），以及一个用于实验的Dell服务器，其默认管理员账户为root，密码为calvin。
- **网络配置**：笔记本电脑设置特定的IP地址范围（192.168.0.x），禁用除所需网络接口之外的所有连接，并且关闭可能干扰安装的防火墙和安全软件。

## 实施步骤

### 1. **服务器准备与连接**

- 通过控制口（远程口）用网线连接服务器和笔记本。
- 使用Firefox浏览器访问服务器管理地址（例如：https://192.168.0.120），处理安全警告，以便登录并启动服务器。

### 2. **CNA ISO镜像挂载与启动**

- 通过虚拟控制台挂载下载的CNA ISO镜像文件。
- 引导服务器进入BIOS，设置从CD启动安装。

### 3. **安装配置**

- 配置主机信息，包括IP（如192.168.10.80）、子网掩码、网关及密码，设置适当的主机名称。
- 开始安装过程，耐心等待直至安装完成。

### 4. **验证与登录**

- 安装完毕后，使用root账户和设定的密码通过网络登录CNA主机，验证安装是否成功。

## 注意事项

- 在整个安装过程中，确保遵循软件的版本指南，不同版本之间可能存在细微差别。
- 确保网络配置正确，尤其是对于新手，正确的网络设置是成功部署的关键。
- 考虑到安全性，安装完成后，可以更改初始设置，增强系统的安全性。

此份指南旨在帮助初学者和专业人员快速熟悉FusionCompute的单节点部署流程，为更复杂的云环境搭建打下基础。祝您部署顺利！

## 下载链接

[华为云计算-FusionCompute单节点部署指南CNA主机安装](https://pan.quark.cn/s/e94eed5ea844)