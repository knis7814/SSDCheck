# SSDCheck

## 本项目初始说明

本项目初始时，只为测试SSD性能，因本人手上有一块SSD存在性能问题，送回厂家维修后厂家不认存在性能问题，并质疑个人是否有测试SSD性能的能力，因个人本就是一位测试工程师，测试的项目也会接触到各类硬件的测试，故创建此项目

项目的后续过程则逐渐变为作为个人系统学习SSD信息以及个人学习过程的记录

## 项目内容概述

项目将分为基础篇和实际脚本实操篇，基础篇将讲解基础SSD知识，实操篇为可以直接执行测试的基础命令，目前命令以Linux sh脚本为主，后续会统一更改为python脚本编写以方便多平台测试

如果你只想测试自己SSD的性能，可直接进入实操篇

# 基础篇

基础篇将分为以下几个内容：
1. SSD概述
2. 核心技术
3. 内部架构
4. 关键算法
5. 性能指标
6. 测试方法
7. 优化指南
8. 故障排除
9. 其他资源


# 实操篇
实操篇将分为以下几个内容：
1. 磁盘基础信息获取与设备预处理
2. SSD预处理
3. 性能测试篇
4. 可靠性与耐久性测试篇
5. 兼容性测试篇
6. 稳定性测试篇
7. 功能性测试篇
8. 用户场景测试篇


## 📚 资源

### 学习资源
- **官方文档**
  - [NVMe Specification](https://nvmexpress.org/specifications/)
  - [JEDEC NAND Standards](https://www.jedec.org/)
  - [SNIA SSD Performance Test Specification](https://www.snia.org/tech_activities/standards/curr_standards/ssd)

- **开源项目**
  - [SPDK (Storage Performance Development Kit)](https://spdk.io/)
  - [Linux NVMe Driver](https://github.com/torvalds/linux/tree/master/drivers/nvme)
  - [OpenSSD Project](http://www.openssd-project.org/)

- **测试工具**
  - [fio - Flexible I/O Tester](https://github.com/axboe/fio)
  - [nvme-cli - NVMe Management Tool](https://github.com/linux-nvme/nvme-cli)
  - [smartmontools - SMART Monitoring](https://www.smartmontools.org/)

### 制造商工具
- **三星**: Samsung Magician
- **英特尔**: Intel Memory and Storage Tool
- **西部数据**: WD Dashboard
- **金士顿**: Kingston SSD Manager
- **英睿达**: Crucial Storage Executive

### 社区论坛
- [r/SSD on Reddit](https://www.reddit.com/r/SSD/)
- [Tom's Hardware Storage Forum](https://forums.tomshardware.com/forums/storage.32/)
- [AnandTech Storage Forum](https://forums.anandtech.com/categories/storage.13/)

---

## 📝 贡献指南

欢迎提交问题、改进建议和代码贡献！

1. Fork本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开Pull Request

## 📄 许可证

本项目文档采用 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 许可证。

## ⭐️ 致谢

感谢所有为SSD技术发展做出贡献的研究人员、工程师和开源社区成员！
