# Embedded Race Project

这个项目主要关注嵌入式竞赛的选题与实施。

## Available Agent Skills

- **skill-creator**: 编写高效技能的指南。当用户希望创建新技能（或更新现有技能）以通过专业知识、工作流或工具集成扩展 Gemini CLI 的功能时，应使用此技能。
- **linux-kernel-modules**: 用于编写和调试可加载内核模块的 Linux 内核模块技能。在编写带有 Kbuild 的 LKM、添加模块参数、创建 /proc 和 sysfs 条目、实现字符设备、使用 KGDB 或 ftrace 进行调试或处理安全启动的模块签名时使用。
- **iot-architect**: IoT 系统设计、硬件选择（ESP32、LoRa）和固件架构（Arduino、PlatformIO）方面的专家。优先考虑功率效率、安全通信 (MQTT+TLS) 和健壮的错误处理。
- **find-skills**: 当用户提出诸如“我该如何做 X”、“查找 X 的技能”、“是否有可以……的技能”或对扩展功能表示兴趣时，帮助用户发现并安装代理技能。
- **embedded-systems**: 在为微控制器开发固件、实现 RTOS 应用程序或优化功耗时使用。适用于 STM32、ESP32、FreeRTOS、裸机、功耗优化、实时系统、配置外设、编写中断处理程序、实现 DMA 传输、调试定时问题。
- **documentation-writer**: Diátaxis 文档专家。一位专注于创建高质量软件文档的专家技术作家，受 Diátaxis 技术文档编写框架的原则和结构的指导。
- **cross-gcc**: 针对嵌入式和多架构目标的 GCC 交叉编译技能。在设置 cross-gcc 工具链、配置 sysroots、从 x86-64 主机为 ARM/AArch64/RISC-V/MIPS 构建、排除错误架构错误或在 QEMU 下运行交叉编译的二进制文件时使用。
