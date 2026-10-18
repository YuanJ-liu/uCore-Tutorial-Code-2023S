# Details

Date : 2026-10-17 20:42:04

Directory /home/yuanjia/uCore-Tutorial-Code-2023S

Total : 60 files,  4473 codes, 581 comments, 666 blanks, all 5720 lines

[Summary](results.md) / Details / [Diff Summary](diff.md) / [Diff Details](diff-details.md)

## Files
| filename | language | code | comment | blank | total |
| :--- | :--- | ---: | ---: | ---: | ---: |
| [.github/workflows/github-autotest.yml](/.github/workflows/github-autotest.yml) | YAML | 42 | 0 | 3 | 45 |
| [.github/workflows/gitlab-mirror.yml](/.github/workflows/gitlab-mirror.yml) | YAML | 20 | 0 | 3 | 23 |
| [.gitlab-ci.yml](/.gitlab-ci.yml) | YAML | 10 | 0 | 3 | 13 |
| [Makefile](/Makefile) | Makefile | 103 | 4 | 31 | 138 |
| [README.md](/README.md) | Markdown | 19 | 0 | 9 | 28 |
| [nfs/Makefile](/nfs/Makefile) | Makefile | 9 | 0 | 5 | 14 |
| [nfs/fs.c](/nfs/fs.c) | C | 224 | 6 | 38 | 268 |
| [nfs/fs.h](/nfs/fs.h) | C++ | 43 | 15 | 16 | 74 |
| [nfs/types.h](/nfs/types.h) | C++ | 10 | 0 | 2 | 12 |
| [os/bio.c](/os/bio.c) | C | 79 | 25 | 11 | 115 |
| [os/bio.h](/os/bio.h) | C++ | 21 | 0 | 5 | 26 |
| [os/console.c](/os/console.c) | C | 13 | 1 | 3 | 17 |
| [os/console.h](/os/console.h) | C++ | 6 | 0 | 3 | 9 |
| [os/const.h](/os/const.h) | C++ | 14 | 10 | 7 | 31 |
| [os/defs.h](/os/defs.h) | C++ | 18 | 1 | 5 | 24 |
| [os/entry.S](/os/entry.S) | Assembly | 11 | 0 | 2 | 13 |
| [os/fcntl.h](/os/fcntl.h) | C++ | 8 | 0 | 2 | 10 |
| [os/file.c](/os/file.c) | C | 128 | 18 | 13 | 159 |
| [os/file.h](/os/file.h) | C++ | 50 | 6 | 9 | 65 |
| [os/fs.c](/os/fs.c) | C | 321 | 82 | 52 | 455 |
| [os/fs.h](/os/fs.h) | C++ | 61 | 18 | 17 | 96 |
| [os/kalloc.c](/os/kalloc.c) | C | 42 | 8 | 7 | 57 |
| [os/kalloc.h](/os/kalloc.h) | C++ | 6 | 0 | 2 | 8 |
| [os/kernelld.py](/os/kernelld.py) | Python | 58 | 0 | 11 | 69 |
| [os/kernelvec.S](/os/kernelvec.S) | Assembly | 70 | 12 | 4 | 86 |
| [os/loader.c](/os/loader.c) | C | 56 | 2 | 4 | 62 |
| [os/loader.h](/os/loader.h) | C++ | 13 | 0 | 4 | 17 |
| [os/log.h](/os/log.h) | C++ | 98 | 0 | 25 | 123 |
| [os/main.c](/os/main.c) | C | 31 | 0 | 2 | 33 |
| [os/pipe.c](/os/pipe.c) | C | 95 | 0 | 5 | 100 |
| [os/plic.c](/os/plic.c) | C | 23 | 8 | 5 | 36 |
| [os/plic.h](/os/plic.h) | C++ | 19 | 3 | 5 | 27 |
| [os/printf.c](/os/printf.c) | C | 72 | 2 | 9 | 83 |
| [os/printf.h](/os/printf.h) | C++ | 4 | 0 | 3 | 7 |
| [os/proc.c](/os/proc.c) | C | 396 | 50 | 35 | 481 |
| [os/proc.h](/os/proc.h) | C++ | 76 | 9 | 10 | 95 |
| [os/queue.c](/os/queue.c) | C | 29 | 0 | 5 | 34 |
| [os/queue.h](/os/queue.h) | C++ | 15 | 2 | 5 | 22 |
| [os/riscv.h](/os/riscv.h) | C++ | 231 | 38 | 55 | 324 |
| [os/sbi.c](/os/sbi.c) | C | 39 | 0 | 5 | 44 |
| [os/sbi.h](/os/sbi.h) | C++ | 8 | 0 | 4 | 12 |
| [os/string.c](/os/string.c) | C | 82 | 2 | 16 | 100 |
| [os/string.h](/os/string.h) | C++ | 11 | 0 | 3 | 14 |
| [os/switch.S](/os/switch.S) | Assembly | 31 | 5 | 4 | 40 |
| [os/sync.c](/os/sync.c) | C | 130 | 11 | 10 | 151 |
| [os/sync.h](/os/sync.h) | C++ | 30 | 3 | 6 | 39 |
| [os/syscall.c](/os/syscall.c) | C | 411 | 22 | 34 | 467 |
| [os/syscall.h](/os/syscall.h) | C++ | 4 | 0 | 3 | 7 |
| [os/syscall\_ids.h](/os/syscall_ids.h) | C++ | 308 | 0 | 1 | 309 |
| [os/timer.c](/os/timer.c) | C | 17 | 4 | 3 | 24 |
| [os/timer.h](/os/timer.h) | C++ | 13 | 1 | 5 | 19 |
| [os/trampoline.S](/os/trampoline.S) | Assembly | 86 | 34 | 10 | 130 |
| [os/trap.c](/os/trap.c) | C | 131 | 18 | 18 | 167 |
| [os/trap.h](/os/trap.h) | C++ | 68 | 0 | 6 | 74 |
| [os/types.h](/os/types.h) | C++ | 10 | 0 | 2 | 12 |
| [os/virtio.h](/os/virtio.h) | C++ | 67 | 24 | 15 | 106 |
| [os/virtio\_disk.c](/os/virtio_disk.c) | C | 176 | 73 | 47 | 296 |
| [os/vm.c](/os/vm.c) | C | 274 | 64 | 35 | 373 |
| [os/vm.h](/os/vm.h) | C++ | 20 | 0 | 3 | 23 |
| [scripts/initproc.py](/scripts/initproc.py) | Python | 13 | 0 | 1 | 14 |

[Summary](results.md) / Details / [Diff Summary](diff.md) / [Diff Details](diff-details.md)