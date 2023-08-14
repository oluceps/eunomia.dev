# Summary

# eBPF Practice Tutorial: Based on libbpf and CO-RE

- [Introduction to basic concepts of eBPF and common development tools](0-introduce/README.md)
- [eBPF Hello World, basic framework and development process](1-helloworld/README.md)
- [Monitoring and capturing unlink system calls using kprobe](2-kprobe-unlink/README.md)
- [Monitoring and capturing unlink system calls using fentry](3-fentry-unlink/README.md)
- [Collection of system calls for capturing processes opening files, filtering process pid using global variables](4-opensnoop/README.md)
- [Capturing readline function calls of bash using uprobe](5-uprobe-bashreadline/README.md)
- [Collection of system calls for capturing process signal sending, saving state using hash map](6-sigsnoop/README.md)
- [Capturing process execution/exit time, printing output to user space using perf event array](7-execsnoop/README.md)
- [Monitoring process exit events using exitsnoop, printing output to user space using ring buffer](8-exitsnoop/README.md)
- [A Linux kernel BPF program that summarizes scheduler run queue latency using histograms, displaying time length tasks wait to run on the CPU](9-runqlat/README.md)
- [Capturing interrupt events using hardirqs or softirqs](10-hardirqs/README.md)
- [Developing user space programs and tracing exec() and exit() system calls using bootstrap](11-bootstrap/README.md)
- [Developing programs to measure TCP connection latency using libbpf-bootstrap](13-tcpconnlat/README.md)
- [Recording TCP connection state and TCP RTT using libbpf-bootstrap](14-tcpstates/README.md)
- [Capturing user space Java GC event duration using USDT](15-javagc/README.md)
- [Writing eBPF program Memleak to monitor memory leaks](16-memleak/README.md)
- [Writing eBPF program Biopattern to measure random/sequential disk I/O](17-biopattern/README.md)
- [More reference materials](18-further-reading/README.md)
- [Performing security detection and defense using LSM](19-lsm-connect/README.md)
- [Performing traffic control using eBPF and tc](20-tc/README.md)

# Advanced Features and Advanced Topics of eBPF

- [Using eBPF programs on Android](22-android/README.md)
- [Tracing HTTP requests or other layer 7 protocols using eBPF](23-http/README.md)
- [Accelerating network request forwarding using sockops](29-sockops/README.md)
- [Hiding process or file information using eBPF](24-hide/README.md)
- [Terminating processes by sending signals using bpf_send_signal](25-signal/README.md)
- [Adding sudo users using eBPF](26-sudo/README.md)
- [Replacing text read or written by any program using eBPF](27-replace/README.md)
- [BPF lifecycle: Running eBPF programs continuously after the user space application exits using Detached mode](28-detach/README.md)

# bcc tutorial

- [BPF Features by Linux Kernel Version](bcc-documents/kernel-versions.md)
- [Kernel Configuration for BPF Features](bcc-documents/kernel_config.md)
- [bcc Reference Guide](bcc-documents/reference_guide.md)
- [Special Filtering](bcc-documents/special_filtering.md)
- [bcc Tutorial](bcc-documents/tutorial.md)".- [bcc Python Developer Tutorial](bcc-documents/tutorial_bcc_python_developer.md)