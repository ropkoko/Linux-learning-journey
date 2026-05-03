☁️ Day 2 — Linux File System & Git/GitHub Basics

    “Structure creates understanding. Version control creates control.”

Welcome to Day 2 of my Linux learning journey.

Today I focused on understanding how Linux organizes its system through the file system structure, and I also began learning Git and GitHub (about 40%), which are essential tools for modern Cloud Engineering and software workflows.
🚀 What I Learned Today

Today’s learning was divided into two main areas:

    Linux File System Structure (deep understanding)
    Introduction to Git & GitHub (version control basics)

🌳 Linux File System Structure

I learned that Linux organizes everything starting from the root directory:

/ ├── home ├── etc ├── var ├── usr ├── bin ├── sbin ├── boot ├── dev ├── proc ├── tmp
📌 Key Directories Explained
/ (Root Directory)

    The starting point of everything in Linux
    All files and folders branch from here

/home

    Contains personal user files
    Example: /home/brenda

/etc

    Stores system configuration files
    Controls system settings like users, networks, and services

/var

    Stores logs and changing data
    Important for system monitoring and debugging

/bin & /sbin

    /bin → basic user commands (ls, cp, mv)
    /sbin → system administration commands

/boot

    Contains files needed to start Linux (kernel + bootloader)

/dev

    Represents hardware devices as files

/proc

    Virtual system info (CPU, memory, processes)

/tmp

    Temporary files used by the system

🔥 Why This Matters

Understanding Linux file structure is important because:

    Servers use the same structure
    Cloud systems (AWS, Azure) run on Linux
    Logs and configurations live in these directories
    Helps in troubleshooting real systems

🧰 Git & GitHub Basics (40% Learned)

I also started learning Git and GitHub, which are tools used to track and manage code changes.
🧠 What is Git?

Git is a version control system that tracks changes in files over time.
Key Idea:

It allows you to:

    Save versions of your work
    Go back to previous versions
    Work safely without losing progress

🌍 What is GitHub?

GitHub is a cloud platform that stores Git repositories online.

It allows:

    Storing code in the cloud
    Collaboration with other developers
    Sharing and managing projects

🔄 Git Workflow

Working Directory → Staging Area → Repository → GitHub
🧪 Commands I Started Learning

git init
git status
git add .
git commit -m "message"
git push
git clone


## 💡 What Each Command Means
git init → starts a Git repository
git add → stages changes
git commit → saves a snapshot
git push → sends code to GitHub
git clone → copies a repository from GitHub


