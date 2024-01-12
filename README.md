# 2023_xv6_riscv_project
This project is to add your own system call in xv6.

## Spec
- gcc – 11.4.0
- gcc make perl package
- gdb-multiarch – 12.1
- qemu-riscv64 – 6.2.0
- Ubuntu 22.04 LTS
- xv6-riscv (https://github.com/mit-pdos/xv6-riscv)

## Added System call
### Show free pages number 
Show free pages amount immediately when you start qemu.

### pages()
Show free pages amount manually.

### trace()
trace process and return the value of process that you want to trace

## Reference
https://hackmd.io/@Chang-Chia-Chi/rJUgZ6bqK#System-call-tracing-moderate  
https://blog.csdn.net/LostUnravel/article/details/121319645  
https://www.cnblogs.com/YuanZiming/p/14218997.html  
https://cs631.cs.usfca.edu/guides/adding-a-syscall-to-xv6  
