linux0.01/
├── boot
│   ├── boot.s
│   └── head.s
├── fs
│   ├── bitmap.c
│   ├── block_dev.c
│   ├── buffer.c
│   ├── char_dev.c
│   ├── exec.c
│   ├── fcntl.c
│   ├── file_dev.c
│   ├── file_table.c
│   ├── inode.c
│   ├── ioctl.c
│   ├── Makefile
│   ├── namei.c
│   ├── open.c
│   ├── pipe.c
│   ├── read_write.c
│   ├── stat.c
│   ├── super.c
│   ├── truncate.c
│   └── tty_ioctl.c
├── include
│   ├── a.out.h
│   ├── asm
│   │   ├── io.h
│   │   ├── memory.h
│   │   ├── segment.h
│   │   └── system.h
│   ├── const.h
│   ├── ctype.h
│   ├── errno.h
│   ├── fcntl.h
│   ├── linux
│   │   ├── config.h
│   │   ├── fs.h
│   │   ├── hdreg.h
│   │   ├── head.h
│   │   ├── kernel.h
│   │   ├── mm.h
│   │   ├── sched.h
│   │   ├── sys.h
│   │   └── tty.h
│   ├── signal.h
│   ├── stdarg.h
│   ├── stddef.h
│   ├── string.h
│   ├── sys
│   │   ├── stat.h
│   │   ├── times.h
│   │   ├── types.h
│   │   ├── utsname.h
│   │   └── wait.h
│   ├── termios.h
│   ├── time.h
│   ├── unistd.h
│   └── utime.h
├── init
│   └── main.c
├── kernel
│   ├── asm.s
│   ├── console.c
│   ├── exit.c
│   ├── fork.c
│   ├── hd.c
│   ├── keyboard.s
│   ├── Makefile
│   ├── mktime.c
│   ├── panic.c
│   ├── printk.c
│   ├── rs_io.s
│   ├── sched.c
│   ├── serial.c
│   ├── sys.c
│   ├── system_call.s
│   ├── traps.c
│   ├── tty_io.c
│   └── vsprintf.c
├── lib
│   ├── close.c
│   ├── ctype.c
│   ├── dup.c
│   ├── errno.c
│   ├── execve.c
│   ├── _exit.c
│   ├── Makefile
│   ├── open.c
│   ├── setsid.c
│   ├── string.c
│   ├── wait.c
│   └── write.c
├── Makefile
├── mm
│   ├── Makefile
│   ├── memory.c
│   └── page.s
└── tools
    └── build.c

11 directories, 88 files
