# Node.system 全部文档

![](/assets/nodesystem.png)

Node.system是wrtnode开发的物联网JavaScript开发框架。

wrtnode的观点是：物联网开发不应该是传统嵌入式开发的延续，而应该是互联网开发的延续。

传统嵌入式开发的方式主要的四大弊病：

1. 需要考虑中断、寄存器、内存分配等过于底层的工作
2. 编译、烧写、观察、借助调试设备的调试的开发生命周期
3. 不同SoC和系统的差异过大
4. 缺乏代码复用与开源的习惯

会导致开发周期长，技术封闭，行业发展缓慢。

而反观互联网开发，互联网蓬勃的发展有一个重要的成因是：互联网开发速度快迭代频次高，能快速适应各种场景的需求。

因此，wrtnode团队推出了Node.system物联网JavaScript开发框架。

Node.system着眼于解决传统嵌入式开发的弊病，导入互联网开发模式。使用JavaScript为所有不同的SoC和不同的操作系统提供统一的开发框架，为硬件数字模拟IO、传感器和控制器、网络协议、云服务、通讯管理、专用关键算法（如多媒体压缩、语音语意、图像识别、SLAM等）提供形式一致的、消息驱动响应式开发的、开源的JavaScript封装。并由wrtnode团队和社区一起，移植到从0.5美元到数百美元，从Cortex-Mx、mips、arm到x86，从Linux、Zephyr、LiteOs到FreeRtos的硬件基础设施上，并提供持续的维护服务。

本书是Node.system的全部文档，使用gitbook发布，所有读者均可提交pull request。

