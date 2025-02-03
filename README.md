# KernelSU susfs 定制内核  

**🔔 重要提示**  
本仓库为**个人自用仓库**，主要适配特定设备型号。  
如需其他设备支持，请自行：  
- Fork 本仓库进行修改，或  
- 基于源仓库 [WildPlusKernel/OnePlus_KernelSU_SUSFS](https://github.com/WildPlusKernel/OnePlus_KernelSU_SUSFS) 适配。  

---

**⚠️ 重要声明**  
使用本内核即表示您已知悉并接受以下条款：  

- 您的设备保修将**立即失效**。  
- 对设备变砖、数据丢失、硬件损坏或相关问题**概不负责**。  
- 所有修改均**由您自行决定**。请在使用前充分研究功能与风险。  

--- 

## 📥 安装指南  
本内核适用于**Android GKI 设备**。请按以下步骤操作：  

1. 确保已解锁 Bootloader 并安装自定义 Recovery（如 TWRP）。  
2. 从 [发布页](https://github.com/TheWildJames/kernel_build_scripts/releases) 下载最新的 `AnyKernel3` ZIP 包。  
3. 通过 Recovery 刷入：  
   ```bash  
   adb sideload kernel_package.zip  
   ```  
4. 重启设备并验证功能。  

详细说明请参考 [KernelSU 官方安装指南](https://kernelsu.org/guide/installation.html)。  

--- 

## ✨ 核心功能  
- **KernelSU 集成**  
  - 专为 Android GKI 设备设计的内核级 ROOT 方案。  
  - 直接在内核空间授予应用程序 ROOT 权限。  
- **SUSFS 扩展模块**  
  - 增强型 ROOT 隐藏补丁，兼容 KernelSU。  
  - 用户空间模块支持高级隐身配置。  

--- 

## 🛠️ 开发计划  
- [x] 发布 AnyKernel3 构建版本  
- [x] 提供预编译的 `boot.img` 文件  
- [ ] 部署 GitHub CI/CD 自动化流程  
- [x] ~~扩展设备兼容性~~（仅限当前设备，不再支持新机型）  

--- 

## 🙏 致谢  
- **KernelSU**：核心框架由 [tiann](https://github.com/tiann) 开发。  
- **SUSFS**：ROOT 隐藏模块由 [simonpunk](https://gitlab.com/simonpunk/susfs4ksu) 贡献。  

--- 

## ⚠️ 最终免责声明  
刷入自定义内核存在固有风险。请务必：  
- 提前备份重要数据。  
- 确认设备兼容性。  
- 熟悉故障恢复操作流程。  

**仅当完全接受上述条款时，方可继续操作。**  