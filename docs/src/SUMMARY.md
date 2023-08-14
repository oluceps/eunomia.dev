# Summary

# eBPF 实践教程：基于 libbpf 和 CO-RE

- [介绍 eBPF 的基本概念、常见的开发工具](0-introduce/README.md)
- [eBPF Hello World，基本框架和开发流程](1-helloworld/README.md)
- [使用 kprobe 监测捕获 unlink 系统调用](2-kprobe-unlink/README.md)
- [使用 fentry 监测捕获 unlink 系统调用](3-fentry-unlink/README.md)
- [捕获进程打开文件的系统调用集合，使用全局变量过滤进程 pid](4-opensnoop/README.md)
- [使用 uprobe 捕获 bash 的 readline 函数调用](5-uprobe-bashreadline/README.md)
- [捕获进程发送信号的系统调用集合，使用 hash map 保存状态](6-sigsnoop/README.md)
- [捕获进程执行/退出时间，通过 perf event array 向用户态打印输出](7-execsnoop/README.md)
- [使用 exitsnoop 监控进程退出事件，使用 ring buffer 向用户态打印输出](8-exitsnoop/README.md)
- [一个 Linux 内核 BPF 程序，通过柱状图来总结调度程序运行队列延迟，显示任务等待运行在 CPU 上的时间长度](9-runqlat/README.md)
- [使用 hardirqs 或 softirqs 捕获中断事件](10-hardirqs/README.md)
- [使用 bootstrap 开发用户态程序并跟踪 exec() 和 exit() 系统调用](11-bootstrap/README.md)
- [使用 libbpf-bootstrap 开发程序统计 TCP 连接延时](13-tcpconnlat/README.md)
- [使用 libbpf-bootstrap 记录 TCP 连接状态与 TCP RTT](14-tcpstates/README.md)
- [使用 USDT 捕获用户态 Java GC 事件耗时](15-javagc/README.md)
- [编写 eBPF 程序 Memleak 监控内存泄漏](16-memleak/README.md)
- [编写 eBPF 程序 Biopattern 统计随机/顺序磁盘 I/O](17-biopattern/README.md)
- [更多的参考资料](18-further-reading/README.md)
- [使用 LSM 进行安全检测防御](19-lsm-connect/README.md)
- [使用 eBPF 进行 tc 流量控制](20-tc/README.md)

# eBPF 高级特性与进阶主题

- [在 Android 上使用 eBPF 程序](22-android/README.md)
- [使用 eBPF 追踪 HTTP 请求或其他七层协议](23-http/README.md)
- [使用 sockops 加速网络请求转发](29-sockops/README.md)
- [使用 eBPF 隐藏进程或文件信息](24-hide/README.md)
- [使用 bpf_send_signal 发送信号终止进程](25-signal/README.md)
- [使用 eBPF 添加 sudo 用户](26-sudo/README.md)
- [使用 eBPF 替换任意程序读取或写入的文本](27-replace/README.md)
- [BPF的生命周期：使用 Detached 模式在用户态应用退出后持续运行 eBPF 程序](28-detach/README.md)

# bcc tutorial

- [BPF Features by Linux Kernel Version](bcc-documents/kernel-versions.md)
- [Kernel Configuration for BPF Features](bcc-documents/kernel_config.md)
- [bcc Reference Guide](bcc-documents/reference_guide.md)
- [Special Filtering](bcc-documents/special_filtering.md)
- [bcc Tutorial](bcc-documents/tutorial.md)
- [bcc Python Developer Tutorial](bcc-documents/tutorial_bcc_python_developer.md)
