# 嵌入式开发常用术语
# Embedded Systems Common Terminology

---

## 📦 Hardware Terms | 硬件术语

| 英文 | 中文 |
|------|------|
| MCU (Microcontroller Unit) | 微控制器 / 单片机 |
| MPU (Microprocessor Unit) | 微处理器 |
| SoC (System on Chip) | 片上系统 |
| GPIO (General Purpose Input/Output) | 通用输入输出 |
| UART (Universal Asynchronous Receiver-Transmitter) | 通用异步收发传输器 |
| SPI (Serial Peripheral Interface) | 串行外设接口 |
| I2C (Inter-Integrated Circuit) | 内部集成电路 |
| ADC (Analog-to-Digital Converter) | 模数转换器 |
| DAC (Digital-to-Analog Converter) | 数模转换器 |
| PWM (Pulse Width Modulation) | 脉冲宽度调制 |
| RTC (Real-Time Clock) | 实时时钟 |
| EEPROM | 电可擦可编程只读存储器 |
| Flash Memory | 闪存 |
| SRAM (Static Random Access Memory) | 静态随机存取存储器 |
| DRAM (Dynamic Random Access Memory) | 动态随机存取存储器 |
| Crystal Oscillator | 晶振 |
| Voltage Regulator | 稳压器 |
| Pull-up Resistor | 上拉电阻 |
| Pull-down Resistor | 下拉电阻 |
| Interrupt | 中断 |
| DMA (Direct Memory Access) | 直接内存访问 |
| Watchdog Timer | 看门狗定时器 |

---

## 💻 Programming Terms | 编程术语

| 英文 | 中文 |
|------|------|
| Firmware | 固件 |
| Bootloader | 引导加载程序 |
| Driver | 驱动程序 |
| HAL (Hardware Abstraction Layer) | 硬件抽象层 |
| RTOS (Real-Time Operating System) | 实时操作系统 |
| FreeRTOS | 自由实时操作系统 |
| Embedded Linux | 嵌入式Linux |
| Bare-metal | 裸机（无操作系统） |
| Register | 寄存器 |
| Bitwise Operation | 位运算 |
| Pointer | 指针 |
| Memory Mapping | 内存映射 |
| Stack | 栈 |
| Heap | 堆 |
| Volatile Keyword | volatile关键字（防止编译器优化） |
| Inline Assembly | 内联汇编 |
| Cross-compiler | 交叉编译器 |
| Toolchain | 工具链 |
| Linker Script | 链接脚本 |
| Makefile | Make构建文件 |
| CMake | CMake构建工具 |

---

## 🔌 Communication Protocols | 通信协议

| 英文 | 中文 |
|------|------|
| CAN (Controller Area Network) | 控制器局域网 |
| LIN (Local Interconnect Network) | 本地互联网络 |
| RS-232 | 串行通信接口 |
| RS-485 | 差分串行通信接口 |
| USB (Universal Serial Bus) | 通用串行总线 |
| Ethernet | 以太网 |
| Wi-Fi | 无线保真 |
| Bluetooth | 蓝牙 |
| BLE (Bluetooth Low Energy) | 蓝牙低功耗 |
| ZigBee | 紫蜂协议 |
| LoRa | 长距离无线通信 |
| MQTT | 消息队列遥测传输协议 |
| HTTP | 超文本传输协议 |
| WebSocket | 全双工通信协议 |

---

## 🛠 Development Tools | 开发工具

| 英文 | 中文 |
|------|------|
| IDE (Integrated Development Environment) | 集成开发环境 |
| Keil MDK | Keil开发套件 |
| IAR Embedded Workbench | IAR嵌入式工作台 |
| STM32CubeIDE | STM32集成开发环境 |
| Eclipse | Eclipse开发环境 |
| VS Code | Visual Studio Code |
| JTAG (Joint Test Action Group) | 联合测试行动组（调试接口） |
| SWD (Serial Wire Debug) | 串行线调试 |
| GDB (GNU Debugger) | GNU调试器 |
| Oscilloscope | 示波器 |
| Logic Analyzer | 逻辑分析仪 |
| Multimeter | 万用表 |

---

## ⚡ Performance Terms | 性能术语

| 英文 | 中文 |
|------|------|
| Latency | 延迟 |
| Throughput | 吞吐量 |
| Real-time | 实时 |
| Hard Real-time | 硬实时（严格时间限制） |
| Soft Real-time | 软实时（宽松时间限制） |
| Deterministic | 确定性 |
| Time-slicing | 时间片 |
| Priority | 优先级 |
| Preemption | 抢占 |
| Scheduling | 调度 |
| Context Switch | 上下文切换 |
| Race Condition | 竞态条件 |
| Deadlock | 死锁 |
| Starvation | 饥饿 |
| Buffer Overflow | 缓冲区溢出 |
| Memory Leak | 内存泄漏 |

---

## 🔋 Power Management | 电源管理

| 英文 | 中文 |
|------|------|
| Low Power Mode | 低功耗模式 |
| Sleep Mode | 睡眠模式 |
| Deep Sleep Mode | 深度睡眠模式 |
| Standby Mode | 待机模式 |
| Power Consumption | 功耗 |
| Battery Life | 电池寿命 |
| Dynamic Power | 动态功耗 |
| Static Power | 静态功耗 |
| Power Gating | 电源门控 |
| Clock Gating | 时钟门控 |

---

## 🐛 Debugging Terms | 调试术语

| 英文 | 中文 |
|------|------|
| Breakpoint | 断点 |
| Watchpoint | 观察点 |
| Step Into | 单步进入 |
| Step Over | 单步跳过 |
| Step Out | 单步跳出 |
| Call Stack | 调用栈 |
| Register Dump | 寄存器转储 |
| Core Dump | 核心转储 |
| Trace | 跟踪 |
| Log | 日志 |

---

## 📝 Common Commands | 常用命令

| 英文 | 中文 |
|------|------|
| Reset | 复位 |
| Initialize | 初始化 |
| Configure | 配置 |
| Enable | 使能 |
| Disable | 禁用 |
| Read | 读取 |
| Write | 写入 |
| Poll | 轮询 |
| Interrupt-driven | 中断驱动 |
| Event-driven | 事件驱动 |

---

*Last updated: 2025-03-10*
