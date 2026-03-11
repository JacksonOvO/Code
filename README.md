# 嵌入式开发常用英语词汇与术语手册
# Embedded Development English Vocabulary & Terminology Handbook

> 🎯 学习目标：快速掌握嵌入式开发场景下的专业英语，轻松应对全英文IDE、技术文档、国际社区交流

---

## 📚 学习指南 | Study Guide

### 学习优先级建议：
1. **⭐ 核心高频词**：IDE操作、常用菜单、基础术语（先搞定常用IDE里天天见的词汇）
2. **⭐⭐ 领域术语**：硬件、编程、协议相关词汇（理解技术文档必备）
3. **⭐⭐⭐ 扩展词汇**：性能、调试、电源管理等进阶词汇（深入学习使用）

### 记忆技巧：
- 看到英文先想对应的中文含义，不用刻意背拼写
- 多用几次IDE自然就记住高频操作词汇
- 遇到不懂的词直接查这个手册，比百度翻译更准确

---

## 🖥️ IAR 常用操作词汇 | IAR Common Operation Terms
> 🔴 最高优先级：这些是IAR软件里天天见的菜单和选项，先记这些

| 英文 | 中文含义 | 场景说明 |
|------|----------|----------|
| **File 菜单** | | |
| New | 新建 | 新建工程、文件 |
| Open | 打开 | 打开已有工程、文件 |
| Close | 关闭 | 关闭当前文件/工程 |
| Save | 保存 | 保存当前文件 |
| Save All | 全部保存 | 保存所有修改的文件 |
| Exit | 退出 | 关闭IAR软件 |
| **Edit 菜单** | | |
| Undo | 撤销 | 撤销上一步操作 |
| Redo | 重做 | 恢复撤销的操作 |
| Cut | 剪切 | 剪切选中内容 |
| Copy | 复制 | 复制选中内容 |
| Paste | 粘贴 | 粘贴内容 |
| Find | 查找 | 查找文本 |
| Replace | 替换 | 替换文本 |
| Go to Definition | 跳转到定义 | 跳转到函数/变量的定义位置 |
| **Project 菜单** | | |
| Add Files | 添加文件 | 往工程里添加源文件/头文件 |
| Remove Files | 移除文件 | 从工程里移除文件 |
| Options | 选项 | 工程配置（最重要的菜单！） |
| Build | 编译 | 编译修改过的文件 |
| Rebuild All | 全部重新编译 | 重新编译整个工程 |
| Clean | 清理 | 删除编译生成的中间文件 |
| **Debug 菜单** | | |
| Download and Debug | 下载并调试 | 把程序下载到芯片并进入调试模式 |
| Start Debugging | 开始调试 | 进入调试模式 |
| Stop Debugging | 停止调试 | 退出调试模式 |
| Step Into | 单步进入 | 执行一行代码，进入函数内部 |
| Step Over | 单步跳过 | 执行一行代码，不进入函数内部 |
| Step Out | 单步跳出 | 跳出当前函数 |
| Run to Cursor | 运行到光标处 | 程序运行到光标所在行 |
| Breakpoint | 断点 | 调试时程序暂停的位置 |
| Toggle Breakpoint | 切换断点 | 添加/删除断点 |
| Enable Breakpoint | 启用断点 | 打开断点功能 |
| Disable Breakpoint | 禁用断点 | 关闭断点功能 |
| **View 菜单** | | |
| Workspace | 工作区 | 显示工程文件结构的窗口 |
| Output | 输出窗口 | 显示编译、调试信息 |
| Watch | 观察窗口 | 查看变量值 |
| Memory | 内存窗口 | 查看芯片内存内容 |
| Register | 寄存器窗口 | 查看外设寄存器值 |
| Call Stack | 调用栈 | 查看函数调用关系 |

---

## 🔨 KEIL MDK 常用操作词汇 | KEIL MDK Common Operation Terms

| 英文 | 中文含义 | 场景说明 |
|------|----------|----------|
| **File 菜单** | | |
| New Project | 新建工程 | 创建新工程 |
| Open Project | 打开工程 | 打开已有工程 |
| Save Project | 保存工程 | 保存工程配置 |
| **Project 菜单** | | |
| Manage Project Items | 管理工程项 | 添加/移除文件到工程 |
| Options for Target | 目标选项 | 工程配置（最重要的菜单！） |
| Build Target | 编译目标 | 编译当前目标 |
| Rebuild All Target Files | 全部重新编译 | 重新编译整个工程 |
| Clean Target | 清理目标 | 删除编译生成的中间文件 |
| **Flash 菜单** | | |
| Download | 下载 | 下载程序到芯片 |
| Erase | 擦除 | 擦除芯片Flash |
| Configure Flash Tools | 配置Flash工具 | 设置下载器 |
| **Debug 菜单** | | |
| Start/Stop Debug Session | 开始/停止调试会话 | 进入/退出调试模式 |
| Run | 运行 | 全速运行程序 |
| Stop | 停止 | 停止运行 |
| Reset | 复位 | 复位芯片 |
| Step | 单步 | 执行一行代码 |
| Step Over | 单步跳过 | 执行一行代码，不进入函数 |
| Step Out | 单步跳出 | 跳出当前函数 |
| Run to Cursor Line | 运行到光标行 | 运行到光标所在行 |
| **Peripherals 菜单** | | |
| System Viewer | 系统查看器 | 查看外设寄存器 |
| Function Editor | 功能编辑器 | 编辑调试函数 |
| **Utilities 菜单** | | |
| Settings | 设置 | 下载配置设置 |

---

## 📝 VSCode 常用操作词汇 | VSCode Common Operation Terms

| 英文 | 中文含义 | 场景说明 |
|------|----------|----------|
| **File 菜单** | | |
| New File | 新建文件 | 创建新文件 |
| Open File | 打开文件 | 打开单个文件 |
| Open Folder | 打开文件夹 | 打开项目文件夹 |
| Save | 保存 | 保存当前文件 |
| Save As | 另存为 | 另存为新文件 |
| **Edit 菜单** | | |
| Undo | 撤销 | 撤销上一步操作 |
| Redo | 重做 | 恢复撤销的操作 |
| Find | 查找 | 查找文本 |
| Replace | 替换 | 替换文本 |
| Find in Files | 在文件中查找 | 搜索整个项目 |
| **View 菜单** | | |
| Explorer | 资源管理器 | 显示项目文件结构 |
| Search | 搜索 | 搜索符号/文本 |
| Source Control | 源代码管理 | Git控制面板 |
| Debug | 调试 | 调试视图 |
| Terminal | 终端 | 集成终端 |
| Output | 输出 | 输出面板 |
| Problems | 问题 | 显示编译错误/警告 |
| **Go 菜单** | | |
| Go to File | 跳转到文件 | 快速打开文件 |
| Go to Symbol | 跳转到符号 | 跳转到函数/变量定义 |
| Go to Definition | 跳转到定义 | 跳转到定义位置 |
| Go to Implementation | 跳转到实现 | 跳转到实现位置 |
| Peek Definition | 速览定义 | 预览定义内容 |
| **Debug 菜单** | | |
| Start Debugging | 开始调试 | 启动调试 |
| Stop Debugging | 停止调试 | 停止调试 |
| Restart Debugging | 重启调试 | 重新开始调试 |
| Step Into | 单步进入 | 进入函数 |
| Step Over | 单步跳过 | 跳过函数 |
| Step Out | 单步跳出 | 跳出函数 |
| Continue | 继续 | 继续运行 |
| **Terminal 菜单** | | |
| New Terminal | 新建终端 | 创建新终端 |
| Run Task | 运行任务 | 执行任务 |
| Configure Tasks | 配置任务 | 编辑任务配置 |

---

## 🔧 ESP-IDF 常用操作词汇 | ESP-IDF Common Operation Terms

| 英文 | 中文含义 | 场景说明 |
|------|----------|----------|
| **idf.py 命令** | | |
| create-project | 创建工程 | 创建新ESP-IDF项目 |
| menuconfig | 菜单配置 | 打开项目配置菜单 |
| build | 编译 | 编译整个项目 |
| flash | 烧录 | 烧录程序到芯片 |
| monitor | 监视器 | 打开串口监视器 |
| erase-flash | 擦除Flash | 擦除芯片Flash |
| **配置术语** | | |
| Kconfig | 内核配置 | ESP-IDF的配置系统 |
| sdkconfig | SDK配置 | 项目特定配置 |
| partition table | 分区表 | Flash分区配置 |
| boot loader | 引导加载器 | ESP-IDF启动程序 |
| **组件术语** | | |
| component | 组件 | ESP-IDF模块化代码单元 |
| driver | 驱动 | 硬件外设驱动 |
| esp-idf components | ESP-IDF组件 | 官方提供的功能组件 |
| **常用IDF函数** | | |
| esp_restart | 重启 | 软重启芯片 |
| esp_log_level_set | 设置日志级别 | 配置日志输出级别 |
| esp_err_t | 错误类型 | ESP错误返回值 |

---

## 🔌 调试器常用词汇 | Debugger Common Terms

### J-Link / ST-Link 通用

| 英文 | 中文含义 | 场景说明 |
|------|----------|----------|
| Connect | 连接 | 调试器连接芯片 |
| Disconnect | 断开 | 断开调试器连接 |
| Reset | 复位 | 复位芯片 |
| Halt | 暂停 | 暂停程序运行 |
| Resume | 恢复 | 恢复程序运行 |
| Erase | 擦除 | 擦除芯片Flash |
| Program | 编程 | 烧录程序 |
| Verify | 验证 | 验证烧录内容 |
| **SWD 接口** | | |
| SWDIO | 双向数据线 | Serial Wire Debug数据线 |
| SWCLK | 时钟线 | Serial Wire Debug时钟线 |
| **JTAG 接口** | | |
| TDI | 数据输入 | JTAG数据输入 |
| TDO | 数据输出 | JTAG数据输出 |
| TCK | 时钟 | JTAG时钟 |
| TMS | 模式选择 | JTAG模式选择 |

---

## 🛠️ 构建工具常用词汇 | Build Tools Common Terms

| 英文 | 中文含义 | 场景说明 |
|------|----------|----------|
| Makefile | Make构建文件 | 自动化编译脚本 |
| CMake | CMake构建工具 | 生成Makefile的工具 |
| make | 构建命令 | 执行编译 |
| gcc | GNU编译器 | C/C++编译器 |
| gdb | 调试器 | GNU调试工具 |
| arm-none-eabi-gcc | ARM交叉编译器 | 编译ARM Cortex-M代码 |
| arm-none-eabi-gdb | ARM调试器 | 调试ARM程序 |
| ninja | 构建系统 | 高速构建工具 |
| cmake .. | 配置构建 | 运行CMake配置 |
| make -j4 | 多线程编译 | 使用4个线程并行编译 |

---

## 📦 硬件术语 | Hardware Terms

| 英文 | 中文 | 说明 |
|------|------|------|
| MCU (Microcontroller Unit) | 微控制器 / 单片机 | 嵌入式系统核心芯片，比如STM32 |
| MPU (Microprocessor Unit) | 微处理器 | 跑操作系统的高性能芯片，比如ARM Cortex-A系列 |
| SoC (System on Chip) | 片上系统 | 集成了CPU、外设、接口的单芯片 |
| GPIO (General Purpose Input/Output) | 通用输入输出 | 最常用的外设，可配置为输入/输出引脚 |
| UART (Universal Asynchronous Receiver-Transmitter) | 通用异步收发传输器 | 串口通信，常用作打印日志 |
| SPI (Serial Peripheral Interface) | 串行外设接口 | 同步串行通信，速度快，常用于连接Flash、显示屏 |
| I2C (Inter-Integrated Circuit) | 内部集成电路 | 半双工同步通信，两根线，常用于连接传感器 |
| ADC (Analog-to-Digital Converter) | 模数转换器 | 把模拟电压转换成数字值 |
| DAC (Digital-to-Analog Converter) | 数模转换器 | 把数字值转换成模拟电压 |
| PWM (Pulse Width Modulation) | 脉冲宽度调制 | 控制电机、LED亮度常用技术 |
| RTC (Real-Time Clock) | 实时时钟 | 记录时间的外设，掉电也能走 |
| EEPROM | 电可擦可编程只读存储器 | 小容量非易失性存储，掉电数据不丢 |
| Flash Memory | 闪存 | 大容量非易失性存储，存程序和数据 |
| SRAM (Static Random Access Memory) | 静态随机存取存储器 | 速度快，容量小，掉电数据丢 |
| DRAM (Dynamic Random Access Memory) | 动态随机存取存储器 | 速度较快，容量大，需要刷新 |
| Crystal Oscillator | 晶振 | 给芯片提供时钟源 |
| Voltage Regulator | 稳压器 | 稳定电压，给芯片供电 |
| Pull-up Resistor | 上拉电阻 | 把引脚电平默认拉到高电平 |
| Pull-down Resistor | 下拉电阻 | 把引脚电平默认拉到低电平 |
| Interrupt | 中断 | 外部事件触发CPU暂停当前任务处理事件 |
| DMA (Direct Memory Access) | 直接内存访问 | 外设直接读写内存，不用CPU参与 |
| Watchdog Timer | 看门狗定时器 | 程序跑飞时自动复位芯片 |

---

## 💻 编程术语 | Programming Terms

| 英文 | 中文 | 说明 |
|------|------|------|
| Firmware | 固件 | 跑在嵌入式设备上的程序 |
| Bootloader | 引导加载程序 | 芯片上电后第一个运行的程序，用来升级固件 |
| Driver | 驱动程序 | 操作硬件外设的代码 |
| HAL (Hardware Abstraction Layer) | 硬件抽象层 | STM32等厂商提供的封装好的硬件操作库 |
| RTOS (Real-Time Operating System) | 实时操作系统 | 嵌入式常用操作系统，比如FreeRTOS、UCOS |
| FreeRTOS | 自由实时操作系统 | 最常用的开源RTOS |
| Embedded Linux | 嵌入式Linux | 跑在MPU上的Linux系统，适合复杂应用 |
| Bare-metal | 裸机 | 没有操作系统，直接操作寄存器 |
| Register | 寄存器 | 外设的控制单元，通过读写寄存器控制外设 |
| Bitwise Operation | 位运算 | 按位与/或/非/移位操作，嵌入式常用 |
| Pointer | 指针 | C语言核心，直接操作内存地址 |
| Memory Mapping | 内存映射 | 把外设寄存器地址映射到内存地址空间 |
| Stack | 栈 | 存局部变量、函数调用信息，自动分配释放 |
| Heap | 堆 | 动态内存分配区域，需要手动管理 |
| Volatile Keyword | volatile关键字 | 告诉编译器不要优化该变量，常用在中断和寄存器操作 |
| Inline Assembly | 内联汇编 | C代码里嵌入汇编代码，操作特殊寄存器 |
| Cross-compiler | 交叉编译器 | 在PC上编译生成目标芯片能运行的代码 |
| Toolchain | 工具链 | 编译、链接、调试工具的集合 |
| Linker Script | 链接脚本 | 定义程序在内存中的分布 |
| Makefile | Make构建文件 | 自动化编译脚本 |
| CMake | CMake构建工具 | 生成Makefile的工具，更方便管理大型工程 |

---

## 🔌 通信协议 | Communication Protocols

| 英文 | 中文 | 说明 |
|------|------|------|
| CAN (Controller Area Network) | 控制器局域网 | 汽车、工业领域常用的可靠通信协议 |
| LIN (Local Interconnect Network) | 本地互联网络 | 汽车领域低成本低速通信协议 |
| RS-232 | 串行通信接口 | 老式串口，常用作调试 |
| RS-485 | 差分串行通信接口 | 长距离、抗干扰强的串行通信 |
| USB (Universal Serial Bus) | 通用串行总线 | 高速通信接口，连接电脑、外设 |
| Ethernet | 以太网 | 有线网络通信 |
| Wi-Fi | 无线保真 | 无线网络通信 |
| Bluetooth | 蓝牙 | 短距离无线通信 |
| BLE (Bluetooth Low Energy) | 蓝牙低功耗 | 低功耗蓝牙，适合物联网设备 |
| ZigBee | 紫蜂协议 | 低功耗、低速率物联网通信协议 |
| LoRa | 长距离无线通信 | 低功耗长距离无线通信，适合物联网 |
| MQTT | 消息队列遥测传输协议 | 物联网常用的轻量级消息协议 |
| HTTP | 超文本传输协议 | 网络通信基础协议 |
| WebSocket | 全双工通信协议 | 双向实时通信协议 |

---

## ⚡ 性能术语 | Performance Terms

| 英文 | 中文 | 说明 |
|------|------|------|
| Latency | 延迟 | 从请求到响应的时间 |
| Throughput | 吞吐量 | 单位时间内处理的数据量 |
| Real-time | 实时 | 任务必须在规定时间内完成 |
| Hard Real-time | 硬实时 | 严格时间限制，超时会导致严重后果 |
| Soft Real-time | 软实时 | 宽松时间限制，超时影响不大 |
| Deterministic | 确定性 | 执行时间可预测 |
| Time-slicing | 时间片 | RTOS调度任务的时间分配 |
| Priority | 优先级 | 任务的重要程度，高优先级先执行 |
| Preemption | 抢占 | 高优先级任务可以打断低优先级任务 |
| Scheduling | 调度 | RTOS分配CPU时间给任务的算法 |
| Context Switch | 上下文切换 | 任务切换时保存和恢复寄存器状态 |
| Race Condition | 竞态条件 | 多个任务访问共享资源导致的不确定结果 |
| Deadlock | 死锁 | 多个任务互相等待资源导致都无法执行 |
| Starvation | 饥饿 | 低优先级任务一直得不到CPU执行 |
| Buffer Overflow | 缓冲区溢出 | 写入数据超过缓冲区大小导致内存破坏 |
| Memory Leak | 内存泄漏 | 动态分配的内存没有释放，导致内存越来越少 |

---

## 🔋 电源管理 | Power Management

| 英文 | 中文 | 说明 |
|------|------|------|
| Low Power Mode | 低功耗模式 | 降低功耗的工作模式 |
| Sleep Mode | 睡眠模式 | 关闭部分外设，CPU停止，唤醒快 |
| Deep Sleep Mode | 深度睡眠模式 | 关闭大部分外设，功耗更低，唤醒慢 |
| Standby Mode | 待机模式 | 最低功耗模式，只有少量电路工作 |
| Power Consumption | 功耗 | 设备消耗的电量 |
| Battery Life | 电池寿命 | 电池供电的工作时间 |
| Dynamic Power | 动态功耗 | 电路工作时的功耗 |
| Static Power | 静态功耗 | 电路不工作时的漏电流功耗 |
| Power Gating | 电源门控 | 关闭不需要的模块的电源，降低功耗 |
| Clock Gating | 时钟门控 | 关闭不需要的模块的时钟，降低功耗 |

---

## 🐛 调试术语 | Debugging Terms

| 英文 | 中文 | 说明 |
|------|------|------|
| Breakpoint | 断点 | 调试时程序暂停的位置 |
| Watchpoint | 观察点 | 变量值改变时程序暂停 |
| Step Into | 单步进入 | 执行一行代码，进入函数内部 |
| Step Over | 单步跳过 | 执行一行代码，不进入函数内部 |
| Step Out | 单步跳出 | 跳出当前函数 |
| Call Stack | 调用栈 | 查看函数调用关系 |
| Register Dump | 寄存器转储 | 打印所有寄存器的值 |
| Core Dump | 核心转储 | 程序崩溃时保存的内存和寄存器状态 |
| Trace | 跟踪 | 记录程序执行路径 |
| Log | 日志 | 程序运行时打印的调试信息 |

---

## 📝 常用命令与描述 | Common Commands & Descriptions

| 英文 | 中文 | 说明 |
|------|------|------|
| Reset | 复位 | 重启芯片/外设 |
| Initialize | 初始化 | 外设/模块的初始化配置 |
| Configure | 配置 | 设置外设的参数 |
| Enable | 使能 | 打开外设/功能 |
| Disable | 禁用 | 关闭外设/功能 |
| Read | 读取 | 读寄存器/内存/外设数据 |
| Write | 写入 | 写寄存器/内存/外设数据 |
| Poll | 轮询 | 循环查询外设状态 |
| Interrupt-driven | 中断驱动 | 事件触发中断处理 |
| Event-driven | 事件驱动 | 事件触发相应处理函数 |

---

## 💡 学习计划建议 | Study Plan Suggestion

1. **第一周**：把常用IDE操作词汇全部记住，做到看到英文就知道是什么意思
2. **第二周**：熟悉硬件术语，结合手里的开发板对照学习
3. **第三周**：掌握编程术语，写代码的时候遇到不懂的词查这个手册
4. **后续**：遇到新的词汇随时添加到这个手册里，慢慢积累

---

## 🔗 相关资源 | Related Resources

- [IAR Embedded Workbench 官方文档](https://www.iar.com/)
- [KEIL MDK 官方文档](https://www.keil.com/)
- [VSCode 官方文档](https://code.visualstudio.com/docs)
- [ESP-IDF 官方文档](https://docs.espressif.com/)

---

*Last updated: 2026-03-11*
*Contributions welcome! Please submit PR on GitHub.*
