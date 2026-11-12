# 📓 Learning Log — My SOC Journey

A short log of the rooms I complete and what I learn along the way.
Goal: track my progress and show consistency over time.

---

### Nov 9, 2026 — TryHackMe: Windows Fundamentals
Explored a Windows Server 2019 workstation: navigated the desktop, taskbar and Start menu, checked system/device
info in Settings, managed files with File Explorer, used Task Manager to view users and processes, and ran a
custom scan in Windows Security. The scan flagged an EICAR test file; I traced it through Protection history to
its full path (...\NewHireDocs\tryhatmemaldoc.txt). Finished the room 100%.

**Next:** Linux CLI Basics & Windows CLI Basics — moving from the graphical interface to the command line.

**What I learned:** Windows navigation and system tools, and how an antivirus detects, quarantines and logs a
threat — including finding a detected file's exact path, which is core to investigating a host.

### Nov 12, 2026 — TryHackMe: Linux CLI Basics (completed)
Practiced the core Linux terminal commands: pwd, ls (and ls -al for hidden files), cd, find, cat, whoami,
uname -a and df -h. Completed two file-hunt missions — located hidden files (mission_brief.txt and
day1_report.txt) with `find` and read them with `cat` — and gathered system info (user, kernel version, free
disk space, Linux distribution). Finished the room 100%. Also booted my own Linux Mint VM in VirtualBox and ran
the same commands on my own machine for the first time.

**What I learned:** navigating the Linux filesystem from the command line, searching for and reading files,
inspecting system and disk information, and that Linux and Windows shells use different commands.
