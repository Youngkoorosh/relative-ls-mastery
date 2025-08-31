# relative-ls-mastery

> ❓ How can Salib, a new Linux user, master relative pathing and the `ls` command under time pressure?

## 🧠 Scenario

Salib has just installed Linux and is learning its basics. With a busy schedule, he needs help understanding:
- How to use relative paths
- How to use the `ls` command with useful flags

He has extracted a directory tree from Quera containing folders for **Alireza**, **Arshia**, and **Salib**:

quera
├── alireza
│   ├── final
│   │   └── final-code
│   └── sub
│       ├── 1.sh
│       ├── 2.py
│       ├── 3.py
│       ├── 4.sh
│       ├── 5.sh
│       └── 6.py
├── arshia
│   ├── final
│   │   └── final-code
│   └── sub
│       ├── 1.sh
│       ├── 2.sh
│       ├── 3.sh
│       ├── 4.sh
│       ├── 5.sh
│       ├── 6.sh
│       └── 7.sh
└── salib
    ├── final
    │   └── final-code
    └── sub
        ├── 1.py
        ├── 2.py
        ├── 3.py
        ├── 4.py
        └── 5.py

## 🧪 Task Breakdown

Salib opens a terminal in three different locations and wants to run `ls` with the following goals:

1. **From inside `quera/`**  
   → List contents of the current directory with detailed info, sorted by last modified time, and human-readable sizes.

2. **From inside `quera/salib/`**  
   → Without changing directories, list contents of `alireza/` using relative pathing and the same `ls` options.

3. **From inside `quera/salib/sub/`**  
   → Without changing directories, list contents of `arshia/sub/` using relative pathing and the same `ls` options.

## ✅ Expected Commands

```bash
ls -lht
ls -lht ../alireza
ls -lht ../../arshia/sub
```
## 🎯 Learning Outcome

By solving this, Salib will:

*    Understand how relative paths work in nested directories

*    Use ls effectively with flags: -l (long format), -h (human-readable), -t (sort by time), -r (reverse order)

*    Improve terminal fluency without relying on cd
