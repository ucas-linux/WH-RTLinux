## 1. 项目介绍
- 望获实时Linux系统是基于开源Linux深度优化的硬实时Linux版本，可以支持工业控制、汽车电子等对实时性有高要求的应用场景。
- 望获实时Linux系统旨在维护一个硬实时Linux版本，在已适配硬件上获得高于现有Linux版本的实时性。
- 了解更多望获实时Linux系统的信息，请访问[https://www.onewos.com/](https://www.onewos.com/)
- 获得更多试用版本，请访问[https://www.onewos.com/resource-center/iso](https://www.onewos.com/resource-center/iso)
- 若您想业务咨询，请通过邮箱与我们联系：[wanghuo@ucas.com.cn]([wanghuo@ucas.com.cn)

## 2. 目录说明
- source/平台/:对应平台的开源代码或配置

## 3. 版本说明
- realtime-linux：基于不同平台的硬实时系统版本
- 下载：[https://www.onewos.com/resource-center/iso/free](https://www.onewos.com/resource-center/iso/free)
- 文档：realtime-linux/平台/doc/
- 镜像：realtime-linux/平台/images/
- 工具: realtime-linux/平台/tools/

- fastboot-linux：基于不同平台的快速启动系统版本
- 下载：[https://www.onewos.com/resource-center/iso/free](https://www.onewos.com/resource-center/iso/free)
- 文档：fastboot-linux/平台/doc/
- 镜像：fastboot-linux/平台/images/
- 工具: fastboot-linux/平台/tools/

## 4. 支持镜像
已发布镜像：
- 瑞芯微

计划发布镜像：
- 飞腾
- Zynq
- 英特尔
- ...

## 5. 性能测试
- 实时性测试
  - 执行命令：
    1. 加压：'hackbench -l10000000 &'
    2. 测试实时性：'./cyclictest -a7 -i1000 -n -p90 -d0 --latency=0 --policy=fifo -D 30m'
  - 结果：max=6us

- 快速启动测试
  - 结果：系统启动后，串口打印本次实时启动时间

## 6. 参考资源
瑞芯微TB-RK3588官方说明文档：[https://t.rock-chips.com/wiki/CN/tb-rk3588x/index.html](https://t.rock-chips.com/wiki/CN/tb-rk3588x/index.html)

---

## 1. Project Introduction
- WangHuo rt-os is hard real-time versions of Linux based on open-source Linux that have been deeply optimized. They are capable of supporting applications with high real-time requirements, such as industrial control and automotive electronics.
- WangHuo rt-os aims to maintain a hard real-time version of Linux that achieves higher real-time performance than existing Linux versions on compatible hardware.
- To obtain more trial versions, please visit [https://www.onewos.com/resource-center/iso](https://www.onewos.com/resource-center/iso).
- If you have any business inquiries, please contact us via email at [wanghuo@ucas.com.cn](wanghuo@ucas.com.cn).

## 2. Directory Description
- source/platform/:source code or configuration for the platform

## 3. Version Description
- realtime-linux：Versions of Hard Real-time Systems based on Different Platforms
- Download：[https://www.onewos.com/resource-center/iso/free](https://www.onewos.com/resource-center/iso/free)
- Documentation：realtime-linux/platform/doc/
- Images：realtime-linux/platform/images/
- Tools: realtime-linux/platform/tools/

- fastboot-linux：Fast Boot System Versions Based on Different Platforms
- Download：[https://www.onewos.com/resource-center/iso/free](https://www.onewos.com/resource-center/iso/free)
- Documentation：fastboot-linux/platform/doc/
- Images：fastboot-linux/platform/images/
- Tools: fastboot-linux/platform/tools/

## 4. Support Images
Released Images:
- Rockchip

Planned Release Images:
- Phytium
- Zynq
- Intel
- ...

## 5. Performance Testing
- Real-time Performance Testing
    - Command：
      1. tress：'hackbench -l10000000 &'
      2. Real-time Testing：'./cyclictest -a7 -i1000 -n -p90 -d0 --latency=0 --policy=fifo -D 30m'
    - Result：max=6us

- Fast Boot Testing
    - Result:After system boot, print the real-time boot time on the serial port.

## 6. Reference Resources
Rockchip TB-RK3588's wiki：[https://t.rock-chips.com/wiki/CN/tb-rk3588x/index.html](https://t.rock-chips.com/wiki/CN/tb-rk3588x/index.html)
