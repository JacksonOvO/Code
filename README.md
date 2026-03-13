# 嵌入式开发常用英语词汇与术语手册
# Embedded Development English Vocabulary & Terminology Handbook

> 🎯 学习目标：快速掌握嵌入式开发场景下的专业英语，轻松应对全英文IDE、技术文档、国际社区交流

---

## 📚 学习指南 | Study Guide

### 为什么学嵌入式英语很重要？

嵌入式开发是一个国际化程度非常高的领域：
- **IDE全是英文**：IAR、KEIL、STM32CubeIDE 全部是英文界面
- **芯片手册是英文**：datasheet、reference manual 都是英文
- **技术社区是英文**：Stack Overflow、GitHub、Reddit
- **开源项目是英文**：FreeRTOS、Linux、ESP-IDF 文档

掌握这些词汇，你就能：
- 独立阅读芯片手册，不再依赖中文翻译
- 使用英文 IDE，提高开发效率
- 参与国际技术社区交流
- 阅读开源项目源码

### 学习优先级建议：
1. **⭐ 核心高频词**：IDE操作、常用菜单、基础术语（先搞定常用IDE里天天见的词汇）
2. **⭐⭐ 领域术语**：硬件、编程、协议相关词汇（理解技术文档必备）
3. **⭐⭐⭐ 扩展词汇**：性能、调试、电源管理等进阶词汇（深入学习使用）

### 记忆技巧：
- 看到英文先想对应的中文含义，不用刻意背拼写
- 多用几次IDE自然就记住高频操作词汇
- 遇到不懂的词直接查这个手册，比百度翻译更准确
- 建议搭配实际项目学习，边做边记效果最好

---

## 🖥️ IAR Embedded Workbench 常用操作词汇
> 🔴 最高优先级：这些是IAR软件里天天见的菜单和选项，先记这些

IAR 是嵌入式开发最常用的IDE之一，特别是做汽车电子、工控领域的同学几乎天天接触。

### File 菜单
| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| New | 新建 | 新建工程、源文件 |
| Open | 打开 | 打开已有工程、文件 |
| Close | 关闭 | 关闭当前文件/工程 |
| Save | 保存 | 保存当前修改 |
| Save All | 全部保存 | 批量保存所有修改 |
| Exit | 退出 | 关闭IAR软件 |

### Edit 菜单
| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| Undo | 撤销 | 撤销上一步误操作 |
| Redo | 重做 | 恢复撤销的操作 |
| Cut | 剪切 | 移动代码片段 |
| Copy | 复制 | 复制代码片段 |
| Paste | 粘贴 | 粘贴代码片段 |
| Find | 查找 | 在文件中查找字符串 |
| Replace | 替换 | 批量替换变量名 |
| Find in Files | 在文件中查找 | 搜索整个工程 |
| Go to Definition | 跳转到定义 | 快速定位函数/变量定义 |
| Go to Declaration | 跳转到声明 | 查看函数声明 |
| Next Bookmark | 下一个书签 | 快速导航 |
| Toggle Bookmark | 切换书签 | 标记重要代码位置 |

### Project 菜单
| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| Add Files | 添加文件 | 把源文件添加到工程 |
| Remove Files | 移除文件 | 从工程中移除文件 |
| Add Group | 添加分组 | 组织工程文件结构 |
| Add Project Connection | 添加调试连接 | 配置调试器 |
| Options | 选项 | **最重要的菜单！** 配置芯片、编译器、优化选项 |
| Build | 编译 | 只编译修改过的文件 |
| Rebuild All | 全部重新编译 | 清理后重新编译整个工程 |
| Clean | 清理 | 删除编译生成的中间文件 |
| Batch Build | 批量编译 | 编译多个配置 |

### Debug 菜单
| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| Download and Debug | 下载并调试 | 把程序下载到芯片并进入调试模式 |
| Start Debugging | 开始调试 | 进入调试模式 |
| Stop Debugging | 停止调试 | 退出调试模式 |
| Step Into | 单步进入 | **高频使用** 进入函数内部 |
| Step Over | 单步跳过 | **高频使用** 执行一行，不进入函数 |
| Step Out | 单步跳出 | **高频使用** 执行完当前函数 |
| Run to Cursor | 运行到光标 | 让程序跑到光标处暂停 |
| Breakpoint | 断点 | **高频使用** 调试时暂停程序的位置 |
| Toggle Breakpoint | 切换断点 | **高频使用** 添加/删除断点 |
| Enable Breakpoint | 启用断点 | 暂时禁用断点 |
| Disable Breakpoint | 禁用断点 | 关闭断点功能 |
| Watch | 观察窗口 | **高频使用** 查看变量值 |
| Quick Watch | 快速观察 | 快速查看表达式值 |

### View 菜单
| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| Workspace | 工作区 | 显示工程文件结构 |
| Output | 输出窗口 | 显示编译错误、调试信息 |
| Memory | 内存窗口 | 查看芯片内存内容 |
| Register | 寄存器窗口 | 查看CPU寄存器、外设寄存器 |
| Call Stack | 调用栈 | 查看函数调用关系 |
| Disassembly | 反汇编窗口 | 查看反汇编代码 |
| Symbol Browser | 符号浏览器 | 查看所有函数、变量 |
| Thread List | 线程列表 | 查看FreeRTOS任务列表 |

---

## 🔨 KEIL MDK 常用操作词汇

KEIL MDK 是 ARM Cortex-M 开发最流行的IDE，STM32开发几乎离不开它。

### Project 菜单
| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| New μVision Project | 新建工程 | 创建新KEIL工程 |
| Open Project | 打开工程 | 打开已有工程 |
| Manage Project Items | 管理工程项 | **高频使用** 添加/移除文件到工程 |
| Options for Target | 目标选项 | **最重要** 配置芯片、时钟、调试器 |
| Build Target | 编译目标 | 编译当前目标 |
| Rebuild All Target Files | 全部重新编译 | 重新编译整个工程 |
| Clean Target | 清理目标 | 删除编译产物 |

### Flash 菜单
| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| Download | 下载 | 烧录程序到芯片 |
| Erase | 擦除 | 擦除芯片Flash |
| Configure Flash Tools | 配置Flash工具 | 设置J-Link/ST-Link |

### Debug 菜单
| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| Start/Stop Debug Session | 开始/停止调试 | **高频** 进入/退出调试模式 |
| Run | 运行 | 全速运行程序 |
| Stop | 停止 | 停止运行 |
| Reset | 复位 | **高频** 复位芯片 |
| Step | 单步 | 执行一行代码 |
| Step Over | 单步跳过 | 不进入函数 |
| Step Out | 单步跳出 | 执行完当前函数 |
| Run to Cursor Line | 运行到光标行 | 运行到指定位置 |

### Peripherals 菜单
| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| System Viewer | 系统查看器 | 查看外设寄存器 |
| Function Editor | 功能编辑器 | 编辑调试函数 |

---

## 📝 VSCode 常用操作词汇

VSCode 是现代开发首选，嵌入式结合 PlatformIO、ESP-IDF 很好用。

### File 菜单
| 英文 | 中文含义 | 快捷键 |
|------|----------|--------|
| New File | 新建文件 | Ctrl+N |
| Open File | 打开文件 | Ctrl+O |
| Open Folder | 打开文件夹 | Ctrl+K Ctrl+O |
| Save | 保存 | Ctrl+S |
| Save As | 另存为 | Ctrl+Shift+S |
| Close Editor | 关闭编辑器 | Ctrl+W |

### Edit 菜单
| 英文 | 中文含义 | 快捷键 |
|------|----------|--------|
| Undo | 撤销 | Ctrl+Z |
| Redo | 重做 | Ctrl+Y |
| Cut | 剪切 | Ctrl+X |
| Copy | 复制 | Ctrl+C |
| Paste | 粘贴 | Ctrl+V |
| Find | 查找 | Ctrl+F |
| Replace | 替换 | Ctrl+H |
| Find in Files | 在文件中查找 | Ctrl+Shift+F |
| Replace in Files | 在文件中替换 | Ctrl+Shift+H |

### View 菜单
| 英文 | 中文含义 | 快捷键 |
|------|----------|--------|
| Explorer | 资源管理器 | Ctrl+B |
| Search | 搜索 | Ctrl+Shift+F |
| Source Control | 源代码管理 | Ctrl+Shift+G |
| Debug | 调试 | Ctrl+Shift+D |
| Terminal | 终端 | Ctrl+` |
| Output | 输出 | Ctrl+Shift+U |
| Problems | 问题面板 | Ctrl+Shift+M |
| Extensions | 扩展 | Ctrl+Shift+X |

### Go 菜单
| 英文 | 中文含义 | 快捷键 |
|------|----------|--------|
| Go to File | 跳转到文件 | Ctrl+P |
| Go to Symbol | 跳转到符号 | Ctrl+Shift+O |
| Go to Definition | 跳转到定义 | F12 |
| Go to Implementation | 跳转到实现 | Ctrl+F12 |
| Peek Definition | 速览定义 | Alt+F12 |
| Peek References | 速览引用 | Shift+F12 |
| Go Back | 后退 | Alt+← |
| Go Forward | 前进 | Alt+→ |

### Debug 菜单
| 英文 | 中文含义 | 快捷键 |
|------|----------|--------|
| Start Debugging | 开始调试 | F5 |
| Stop Debugging | 停止调试 | Shift+F5 |
| Restart Debugging | 重启调试 | Ctrl+Shift+F5 |
| Step Into | 单步进入 | F11 |
| Step Over | 单步跳过 | F10 |
| Step Out | 单步跳出 | Shift+F11 |
| Continue | 继续 | F5 |
| Toggle Breakpoint | 切换断点 | F9 |

---

## 🔧 ESP-IDF 常用操作词汇

ESP-IDF 是乐鑫科技官方开发框架，适合ESP32开发。

### idf.py 命令行
| 英文 | 中文含义 | 使用场景 |
|------|----------|----------|
| create-project | 创建工程 | 初始化新项目 |
| menuconfig | 菜单配置 | 配置芯片选项、FreeRTOS等 |
| build | 编译 | 编译整个项目 |
| flash | 烧录 | 烧录程序到芯片 |
| monitor | 监视器 | 打开串口日志输出 |
| erase-flash | 擦除Flash | 清除整个Flash |
| partition-table | 分区表 | 查看/修改分区表 |
| size | 尺寸分析 | 查看固件大小 |
| fullclean | 完全清理 | 删除所有构建文件 |

### 常用配置项 (menuconfig)
| 英文 | 中文含义 |
|------|----------|
| Serial flasher config | 串口烧录配置 |
| Bootloader config | 引导加载器配置 |
| Partition Table | 分区表配置 |
| FreeRTOS | 实时操作系统配置 |
| Wi-Fi | Wi-Fi配置 |
| BLE | 蓝牙配置 |
| Component config | 组件配置 |

### 常用ESP-IDF API
| 英文 | 中文含义 |
|------|----------|
| esp_restart | 软重启芯片 |
| esp_log_level_set | 设置日志级别 |
| esp_err_t | 错误类型定义 |
| esp_read_mac | 读取MAC地址 |
| esp_wifi_init | 初始化WiFi |
| esp_wifi_connect | 连接WiFi |
| esp_timer_create | 创建定时器 |
| xTaskCreatePinnedToCore | 创建任务（带核绑定） |

---

## 🖥️ STM32CubeIDE 常用操作词汇

ST官方IDE，基于Eclipse，适合STM32开发。

| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| New STM32 Project | 新建STM32工程 | 创建新项目 |
| Pinout & Configuration | 引脚配置 | 可视化配置GPIO、外设 |
| Clock Configuration | 时钟配置 | 可视化配置系统时钟 |
| Project Manager | 工程管理 | 项目设置 |
| Generate Code | 生成代码 | 自动生成HAL库代码 |
| Debug as | 调试方式 | 选择调试器 |

---

## 📚 Arduino IDE 常用操作词汇

Arduino适合创客、入门学习。

| 英文 | 中文含义 |
|------|----------|
| New Sketch | 新建 sketch |
| Open | 打开 |
| Save | 保存 |
| Save As | 另存为 |
| Upload | 上传 | 烧录程序 |
| Upload Using Programmer | 编程器上传 | 使用外部编程器 |
| Board | 板型 | 选择开发板 |
| Port | 端口 | 选择串口 |
| Library Manager | 库管理器 | 管理第三方库 |
| Include Library | 包含库 | 添加头文件 |

---

## 🔌 调试器常用词汇

### J-Link 调试器
| 英文 | 中文含义 | 实际使用场景 |
|------|----------|--------------|
| Connect | 连接 | 调试器连接芯片 |
| Disconnect | 断开 | 断开调试连接 |
| Reset | 复位 | 复位芯片 |
| Halt | 暂停 | 暂停程序运行 |
| Resume | 继续 | 恢复程序运行 |
| Erase | 擦除 | 擦除芯片Flash |
| Program | 编程 | 烧录固件 |
| Verify | 验证 | 校验烧录内容 |

### ST-Link 调试器
| 英文 | 中文含义 |
|------|----------|
| Connect | 连接 |
| Disconnect | 断开 |
| Full Chip Erase | 全片擦除 |
| Option Bytes | 选项字节 |
| Target Voltage | 目标电压 |

### 调试接口
| 英文 | 中文含义 |
|------|----------|
| SWD (Serial Wire Debug) | 串行线调试 | 两线调试接口（SWDIO + SWCLK） |
| JTAG (Joint Test Action Group) | 联合测试行动组 | 传统四线/五线调试接口 |
| SWDIO | 双向数据线 |
| SWCLK | 时钟线 |
| TDI | JTAG数据输入 |
| TDO | JTAG数据输出 |
| TCK | JTAG时钟 |
| TMS | JTAG模式选择 |

---

## 🛠️ 构建工具常用词汇

### Makefile/CMake
| 英文 | 中文含义 |
|------|----------|
| Makefile | 构建脚本文件 |
| CMake | 构建配置工具 |
| make | 执行编译 |
| cmake .. | 运行CMake配置 |
| make -j4 | 多线程并行编译 |
| target | 编译目标 |
| prerequisite | 依赖文件 |
| recipe | 构建命令 |

### GCC 工具链
| 英文 | 中文含义 |
|------|----------|
| gcc | C编译器 |
| g++ | C++编译器 |
| gdb | 调试器 |
| ld | 链接器 |
| objcopy | 格式转换工具 |
| arm-none-eabi-gcc | ARM Cortex-M交叉编译器 |
| arm-none-eabi-gdb | ARM调试器 |
| arm-none-eabi-size | 查看文件大小 |

### Ninja 构建系统
| 英文 | 中文含义 |
|------|----------|
| ninja | 高速构建工具 |
| ninja -t targets | 查看所有构建目标 |
| ninja -t graph | 查看依赖图 |

---

## 📦 硬件术语 | Hardware Terms

### 芯片分类
| 英文 | 中文 | 说明 |
|------|------|------|
| MCU (Microcontroller Unit) | 微控制器 | 嵌入式核心芯片，内部集成CPU+RAM+Flash+外设 |
| MPU (Microprocessor Unit) | 微处理器 | 仅包含CPU，需要外接内存和外设 |
| SoC (System on Chip) | 片上系统 | 高度集成，CPU+外设+无线等 |
| CPU (Central Processing Unit) | 中央处理器 | 芯片的运算核心 |
| DSP (Digital Signal Processor) | 数字信号处理器 | 专用于信号处理 |
| FPGA (Field Programmable Gate Array) | 现场可编程门阵列 | 可编程硬件 |

### 存储器
| 英文 | 中文 | 说明 |
|------|------|------|
| Flash Memory | 闪存 | 非易失性存储，存放程序代码 |
| SRAM (Static RAM) | 静态随机存取存储器 | 速度快，掉电丢失，存放变量 |
| DRAM (Dynamic RAM) | 动态随机存取存储器 | 需要周期性刷新 |
| EEPROM | 电可擦除可编程只读存储器 | 非易失性，可擦写 |
| OTP (One-Time Programmable) | 一次性可编程 | 只能烧写一次 |

### 通信接口
| 英文 | 中文 | 说明 |
|------|------|------|
| GPIO (General Purpose Input/Output) | 通用输入输出 | 最基本的外设 |
| UART (Universal Asynchronous Receiver/Transmitter) | 通用异步收发器 | 串口，RS232/RS485 |
| SPI (Serial Peripheral Interface) | 串行外设接口 | 高速同步串行 |
| I2C (Inter-Integrated Circuit) | 集成电路互连 | 两线制I2C |
| I2S (Inter-IC Sound) | 集成电路音频 | 音频数据传输 |
| USB (Universal Serial Bus) | 通用串行总线 | 高速外设接口 |
| CAN (Controller Area Network) | 控制器局域网 | 汽车、工业总线 |
| Ethernet | 以太网 | 有线网络 |
| Wi-Fi | 无线局域网 | 无线网络 |
| Bluetooth | 蓝牙 | 短距离无线 |
| BLE (Bluetooth Low Energy) | 低功耗蓝牙 | 物联网蓝牙 |

### 模拟外设
| 英文 | 中文 | 说明 |
|------|------|------|
| ADC (Analog-to-Digital Converter) | 模数转换器 | 模拟→数字 |
| DAC (Digital-to-Analog Converter) | 数模转换器 | 数字→模拟 |
| PWM (Pulse Width Modulation) | 脉宽调制 | 电机调速、LED调光 |
| Comparato | 比较器 | 比较两个电压 |
| Amplifier | 放大器 | 信号放大 |

### 定时器
| 英文 | 中文 | 说明 |
|------|------|------|
| Timer | 定时器 | 定时、计数 |
| RTC (Real-Time Clock) | 实时时钟 | 日历时间，掉电走时 |
| Watchdog | 看门狗 | 系统超时复位 |
| SysTick | 系统滴答定时器 | ARM Cortex-M内核定时器 |

### 其他外设
| 英文 | 中文 | 说明 |
|------|------|------|
| DMA (Direct Memory Access) | 直接内存访问 | 外设与内存直接传输 |
| CRC (Cyclic Redundancy Check) | 循环冗余校验 | 数据校验 |
| RNG (Random Number Generator) | 随机数生成器 | 产生随机数 |
| TRNG (True Random Number Generator) | 真随机数生成器 |
| Crypto | 加密引擎 | 硬件加解密 |

### 电源管理
| 英文 | 中文 | 说明 |
|------|------|------|
| LDO (Low Dropout Regulator) | 低压差稳压器 | 线性稳压 |
| DC-DC | 直流-直流转换器 | 开关电源 |
| BOD (Brown-Out Detector) | 欠压检测 | 电压过低复位 |
| Power Gating | 电源门控 | 关闭模块电源 |
| Clock Gating | 时钟门控 | 关闭模块时钟 |

---

## 💻 编程术语 | Programming Terms

### 软件架构
| 英文 | 中文 | 说明 |
|------|------|------|
| Firmware | 固件 | 嵌入式设备上的软件 |
| Bootloader | 引导程序 | 芯片启动后第一个程序 |
| Application | 应用程序 | 主应用程序 |
| Driver | 驱动程序 | 操作硬件的代码 |
| HAL (Hardware Abstraction Layer) | 硬件抽象层 | 硬件操作封装库 |
| LL (Low Layer) | 低层驱动 | 直接操作寄存器 |
| BSP (Board Support Package) | 板级支持包 | 开发板相关代码 |

### 操作系统
| 英文 | 中文 | 说明 |
|------|------|------|
| RTOS (Real-Time Operating System) | 实时操作系统 |
| FreeRTOS | 免费RTOS | 最流行的嵌入式RTOS |
| RT-Thread | 国产RTOS | 国产实时操作系统 |
| ucOS | 微控制器操作系统 | 商业RTOS |
| Embedded Linux | 嵌入式Linux | 运行在MPU上的Linux |
| Zephyr | Zephyr系统 | Linux基金会RTOS |

### 编程概念
| 英文 | 中文 | 说明 |
|------|------|------|
| Bare-metal | 裸机编程 | 无OS，直接操作硬件 |
| Register | 寄存器 | 外设控制单元 |
| Bitwise Operation | 位运算 | &, |, ^, ~, <<, >> |
| Bit Banding | 位带操作 | Cortex-M特色功能 |
| Interrupt | 中断 | 异步事件处理 |
| ISR (Interrupt Service Routine) | 中断服务程序 |
| Vector Table | 中断向量表 | 中断处理函数列表 |
| Priority | 中断优先级 | 决定中断处理顺序 |
| Nested Vectored Interrupt Controller | 嵌套向量中断控制器 | ARM Cortex-M中断控制器 |

### 内存管理
| 英文 | 中文 | 说明 |
|------|------|------|
| Stack | 栈 | 函数调用、局部变量 |
| Heap | 堆 | 动态内存分配 |
| Data Section | 数据段 | 存放全局变量 |
| BSS Section | BSS段 | 存放未初始化变量 |
| Text Section | 代码段 | 存放程序代码 |
| Memory Map | 内存映射 | 地址空间分布 |
| Linker Script | 链接脚本 | 定义内存布局 |

---

## 🔌 通信协议 | Communication Protocols

### 有线通信
| 英文 | 中文 | 说明 |
|------|------|------|
| UART | 异步串口 | 最常用的调试接口 |
| RS-232 | 串口标准 | 传统PC串口 |
| RS-485 | 差分串口 | 工业总线 |
| SPI | 同步串口 | 高速通信 |
| I2C | 两线串口 | 传感器接口 |
| USB | 通用串行总线 | 高速外设接口 |
| CAN | 控制器局域网 | 汽车电子标准 |
| LIN | 本地互联网络 | 汽车低速网络 |
| Ethernet | 以太网 | 有线网络 |
| PCIe | 个人计算机express | 高速总线 |

### 无线通信
| 英文 | 中文 | 说明 |
|------|------|------|
| Wi-Fi | 无线保真 | 高速无线网络 |
| Bluetooth | 蓝牙 | 短距离通信 |
| BLE | 低功耗蓝牙 | 物联网蓝牙 |
| ZigBee | 紫蜂协议 | 低功耗Mesh网络 |
| LoRa | 远距离无线电 | 超远距离低功耗 |
| NB-IoT | 窄带物联网 | 蜂窝物联网 |
| 4G/LTE | 第四代移动通信 | 高速蜂窝网络 |
| 5G | 第五代移动通信 | 超高速蜂窝网络 |

### 应用层协议
| 英文 | 中文 | 说明 |
|------|------|------|
| MQTT | 消息队列遥测传输 | 物联网常用协议 |
| HTTP | 超文本传输协议 | Web基础 |
| WebSocket | 全双工通信 | 实时Web通信 |
| CoAP | 约束应用协议 | 物联网轻量协议 |
| Modbus | 工业通信协议 | 串口/TCP工业协议 |
| REST | 表征状态转移 | Web服务架构 |

---

## ⚡ 性能术语 | Performance Terms

### 实时性
| 英文 | 中文 | 说明 |
|------|------|------|
| Real-time | 实时性 | 任务按时完成 |
| Hard Real-time | 硬实时 | 必须按时完成 |
| Soft Real-time | 软实时 | 偶尔超时可接受 |
| Deterministic | 确定性 | 执行时间可预测 |
| Jitter | 时抖 | 时间偏差 |

### 资源相关
| 英文 | 中文 | 说明 |
|------|------|------|
| Latency | 延迟 | 响应时间 |
| Throughput | 吞吐量 | 单位时间处理量 |
| Bandwidth | 带宽 | 传输速率 |
| Footprint | 内存占用 | 代码/内存大小 |
| Overhead | 开销 | 额外消耗 |

### 任务调度
| 英文 | 中文 | 说明 |
|------|------|------|
| Task | 任务 | RTOS中的执行单元 |
| Thread | 线程 | 轻量级任务 |
| Process | 进程 | 独立运行单元 |
| Priority | 优先级 | 任务重要程度 |
| Scheduling | 调度 | 分配CPU时间 |
| Context Switch | 上下文切换 | 任务切换 |
| Preemption | 抢占 | 高优先级打断低优先级 |
| Time Slice | 时间片 | 轮转调度时间单位 |

### 同步与互斥
| 英文 | 中文 | 说明 |
|------|------|------|
| Mutex | 互斥锁 | 保护共享资源 |
| Semaphore | 信号量 | 资源计数/同步 |
| Critical Section | 临界区 | 不可中断代码段 |
| Race Condition | 竞态条件 | 并发访问问题 |
| Deadlock | 死锁 | 互相等待资源 |
| Starvation | 饥饿 | 长期无法执行 |

---

## 🔋 电源管理 | Power Management

| 英文 | 中文 | 说明 |
|------|------|------|
| Active Mode | 工作模式 | 全速运行 |
| Sleep Mode | 睡眠模式 | CPU停止，外设工作 |
| Deep Sleep | 深度睡眠 | 大部分关闭 |
| Stop Mode | 停止模式 | 最小功耗 |
| Standby Mode | 待机模式 | 最低功耗 |
| Power Consumption | 功耗 | 单位时间耗电 |
| Current | 电流 | 耗电大小 |
| Voltage | 电压 | 供电电压 |
| Battery Life | 电池寿命 | 续航时间 |

---

## 🐛 调试术语 | Debugging Terms

| 英文 | 中文 | 说明 |
|------|------|------|
| Breakpoint | 断点 | 程序暂停点 |
| Watchpoint | 观察点 | 变量变化暂停 |
| Step | 单步 | 执行一行 |
| Step Into | 进入函数 | |
| Step Over | 跳过函数 | |
| Step Out | 跳出函数 | |
| Call Stack | 调用栈 | 函数调用链 |
| Register | 寄存器 | CPU寄存器值 |
| Memory View | 内存查看 | 查看内存内容 |
| Variable Watch | 变量监视 | 观察变量值 |
| Core Dump | 崩溃转储 | 崩溃时内存快照 |
| Stack Trace | 堆栈跟踪 | 崩溃调用链 |
| Log | 日志 | 调试输出 |

---

## 💡 学习计划建议 | Study Plan Suggestion

### 第一阶段：IDE入门（1-2周）
1. 选择一个常用IDE（推荐IAR或KEIL）
2. 熟悉常用菜单和快捷键
3. 完成1-2个简单例程

### 第二阶段：硬件基础（2-3周）
1. 学习常见硬件术语
2. 阅读芯片数据手册
3. 理解外设工作原理

### 第三阶段：编程进阶（3-4周）
1. 掌握C语言嵌入式用法
2. 学习调试技巧
3. 完成综合项目

### 第四阶段：持续学习
1. 逐步增加英文文档阅读
2. 参与开源项目
3. 关注技术社区

---

## 📚 推荐学习资源

### 官方文档
- [IAR Embedded Workbench](https://www.iar.com/)
- [KEIL MDK](https://www.keil.com/)
- [STM32CubeIDE](https://www.st.com/)
- [ESP-IDF](https://docs.espressif.com/)
- [VSCode](https://code.visualstudio.com/)
- [FreeRTOS](https://www.freertos.org/)

### 在线学习
- [ST Microelectronics](https://www.st.com/)
- [Espressif Systems](https://www.espressif.com/)
- [ARM Developer](https://developer.arm.com/)

### 技术社区
- [Stack Overflow](https://stackoverflow.com/)
- [Reddit r/embedded](https://reddit.com/r/embedded)
- [GitHub](https://github.com/)

---

## 🤝 贡献指南

欢迎提交 PR 完善本手册！

### 提交格式
```
feat: 添加Arduino IDE常用词汇
fix: 修正XXX翻译错误
docs: 更新学习计划
```

---

*Last updated: 2026-03-11*
*Built with ❤️ for embedded developers*
*Contributions welcome! Please submit PR on GitHub.*

---

## 🐛 常见错误代码 | Common Error Codes

在嵌入式开发中，常见的错误提示：

| Error Code | 含义 | 常见场景 |
|------------|------|----------|
| undefined reference to `xxx` | 函数未定义 | 头文件未包含 / 函数未实现 |
| linker command file error | 链接脚本错误 | 内存配置不正确 |
| stack overflow | 栈溢出 | 递归调用过深 / 局部变量过大 |
| hard fault on exception | 硬件异常 | 数组越界 / 空指针 / 非法访问 |
| bus fault | 总线错误 | 访问未映射地址 |
| memory management fault | 内存管理错误 | 访问非法内存区域 |
| NMI fault | 不可屏蔽中断异常 | 看门狗超时 / 时钟失效 |
| segmentation fault | 段错误 | 内存访问违规 |
| timeout | 超时 | 通信无响应 / 硬件无应答 |
| no such file or directory | 文件不存在 | 头文件路径错误 |
| implicit declaration | 隐式声明 | 函数未在头文件声明 |
| conflicting types | 类型冲突 | 函数声明与定义不匹配 |

## 💡 开发技巧 | Development Tips

### 调试技巧
| 技巧 | 说明 |
|------|------|
| 使用RTT代替串口打印 | RTT速度更快，无需配置UART |
| 使用断点+Watch窗口 | 直接观察变量值，比打印更直观 |
| 查看汇编代码 | 理解编译器优化结果 |
| 使用逻辑分析仪 | 调试GPIO/通信时序 |

### 代码优化
| 技巧 | 说明 |
|------|------|
| 使用static修饰函数 | 增强链接器优化，减少代码体积 |
| 使用const修饰常量 | 节省RAM，编译器优化 |
| 避免浮点数运算 | 嵌入式尽量用定点数 |
| 使用位操作代替除法 | 提升执行效率 |

### 项目结构
| 技巧 | 说明 |
|------|------|
| 模块化设计 | 按功能划分目录 |
| 头文件保护 | 防止重复包含 |
| 统一命名规范 | 提高代码可读性 |
| 写好注释 | 便于后续维护 |

## 📞 技术支持 | Support

- 提交 Issue: GitHub Issues
- 交流讨论: 技术社群
- 文档反馈: 欢迎提交 PR
test 2026-03-13 16:53:22
