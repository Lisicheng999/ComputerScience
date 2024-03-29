# Register
# 寄存器

## 通用寄存器：
AX: 累加器寄存器（Accumulator Register）
BX: 基址寄存器（Base Register）
CX: 计数寄存器（Count Register）
DX: 数据寄存器（Data Register）
SI: 源索引寄存器（Source Index）
DI: 目的索引寄存器（Destination Index）
SP: 堆栈指针寄存器（Stack Pointer）
BP: 基址指针寄存器（Base Pointer）
IP: 指令指针寄存器（Instruction Pointer）

## 段寄存器：
CS: 代码段寄存器（Code Segment）
DS: 数据段寄存器（Data Segment）
ES: 额外段寄存器（Extra Segment）
SS: 堆栈段寄存器（Stack Segment）
FS: 未定义段寄存器（Far Segment，在x86架构中）
GS: 未定义段寄存器（Global Segment，在x86架构中）

## 状态和控制寄存器：
FLAGS: 标志寄存器（Flags Register），在x86架构中包含各种状态标志
CR: 控制寄存器（Control Register），用于控制CPU的操作模式和特性
DR: 调试寄存器（Debug Register），用于调试目的
MSR: 模式特定寄存器（Model-Specific Register），用于控制CPU的特定功能

## 浮点寄存器：
ST(0) - ST(7): 浮点堆栈寄存器（Floating Point Stack Registers），在x87浮点单元中使用
XMM0 - XMM7: 扩展浮点寄存器（SSE Extended Floating Point Registers），用于SSE指令集
YMM0 - YMM15: 扩展浮点寄存器（AVX Extended Floating Point Registers），用于AVX指令集
ZMM0 - ZMM31: 扩展浮点寄存器（AVX-512 Extended Floating Point Registers），用于AVX-512指令集

## 向量寄存器：
MMX: 多媒体扩展寄存器（Multimedia Extension Registers），用于MMX指令集
VMX: 虚拟机扩展寄存器（Virtual Machine Extension Registers），用于虚拟化技术
SMX: 可信执行技术寄存器（Safer Mode Extensions Registers），用于增强系统的安全性

## 链接

- [目录](directory.md)
- 下一节[1.2](01.2.md)