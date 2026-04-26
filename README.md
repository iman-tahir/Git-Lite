<div align="center">

# 🔰 Secure Git-Lite

### A Lightweight Version Control System Built from Scratch

[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RavenX-Iman/Git-Lite)

*Understanding version control by building one*

[Quick Start](#-quick-start) • [Documentation](#-documentation) • [Features](#-features) • [Team](#-team)

</div>

---

## 📖 Overview

**Git-Lite** is a functional version control system that implements core Git operations using fundamental data structures. Built as an academic project at COMSATS University Islamabad, it demonstrates how hash tables, linked lists, and tree structures power version control under the hood.

> *"The best way to understand version control isn't to use Git—it's to build one."*

### Why Git-Lite?

- 🎓 **Educational**: Learn version control internals through implementation
- 🔧 **Practical**: Actually works for tracking files and commits
- 📊 **DSA-Focused**: Real-world application of data structures
- 🚀 **Extensible**: Clean architecture for adding features

---

## ✨ Features

| Command | Description |
|---------|-------------|
| `vcs init <name>` | Initialize a new repository |
| `vcs add <file>` | Stage files for commit |
| `vcs commit -m "msg"` | Create immutable snapshots |
| `vcs log` | View commit history |
| `vcs status` | Check repository state |

**Core Capabilities:**
- ✅ Hash-based content storage with deduplication
- ✅ Linked commit chains with parent tracking
- ✅ Staging area management
- ✅ Cross-platform support (Windows/Linux)
- 🔄 Branching and merging (planned)

---

## 🚀 Quick Start

```bash
# Clone and build
git clone https://github.com/RavenX-Iman/Git-Lite.git
cd Git-Lite
g++ vcsf.cpp -o vcs

# Initialize a repository
./vcs init MyProject
cd MyProject

# Start tracking files
echo "Hello, Git-Lite!" > test.txt
./vcs add test.txt
./vcs commit -m "Initial commit"

# View history
./vcs log
```

**Full installation guide:** See [docs/README_detailed.md](docs/README_detailed.md#-quick-start)

---

## 🆚 Git-Lite vs Git

| Feature | Git-Lite | Git |
|---------|----------|-----|
| **Hash Algorithm** | C++ `std::hash` | SHA-1 / SHA-256 |
| **Storage** | Plain file snapshots | Compressed packfiles |
| **Commits** | Single parent chain | Merge commits (multi-parent) |
| **Branches** | Basic pointers | Full ref system |
| **Network** | Local only | Remote protocols (SSH, HTTPS) |
| **Performance** | Educational scale | Production-optimized |

**Git-Lite is for learning**—use Git for real projects. But building Git-Lite teaches you how Git actually works.

---

## 📚 Documentation

- **[Architecture Guide](docs/ARCHITECTURE.md)** - System design, data structures, and algorithms
- **[Detailed README](docs/README_detailed.md)** - Complete feature list, testing, and examples
- **[Contributing Guide](docs/CONTRIBUTING.md)** - Code style, workflow, and guidelines

### Key Technical Concepts

```
Hash Tables  →  Content-addressable storage (O(1) lookup)
Linked Lists →  Commit history chain (parent pointers)
Trees        →  Directory structure and branches
File System  →  Persistent object storage
```

---

## 👥 Team

<table>
<tr>
<td align="center" width="33%">
<img src="https://github.com/RavenX-Iman.png" width="150px;" alt="Eman Tahir"/><br />
<b>Eman Tahir</b><br />
<a href="https://github.com/RavenX-Iman">@RavenX-Iman</a><br />
</td>
<td align="center" width="33%">
<img src="https://github.com/Huma-Ijaz.png" width="150px;" alt="Huma Ijaz"/><br />
<b>Huma Ijaz</b><br />
<a href="https://github.com/Huma-Ijaz">@Huma-Ijaz</a><br />
</td>
<td align="center" width="33%">
<img src="https://github.com/areebactech.png" width="150px;" alt="Areeba Asif"/><br />
<b>Areeba Asif</b><br />
<a href="https://github.com/areebactech">@areebactech</a><br />
</td>
</tr>
</table>

**Academic Context**  
COMSATS University Islamabad, Sahiwal Campus  
Data Structures Course • Fall 2025  
Supervisor: Shaheen Kausar

---

## 📖 References

### Learning Resources
- **[Pro Git Book](https://git-scm.com/book/en/v2)** - Comprehensive Git guide
- **[Git Internals](https://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain)** - How Git works under the hood
- **Data Structures and Algorithms in C++** by Adam Drozdek


- [Git Source Code](https://github.com/git/git) - The original implementation
- [Gitlet](http://gitlet.maryrosecook.com/) - JavaScript educational VCS
- [ugit](https://www.leshenko.net/p/ugit/) - Python Git implementation

---

## 🤝 Contributing

We welcome contributions from students, developers, and version control enthusiasts!

**Quick Links:**
- 🐛 [Report Issues](https://github.com/RavenX-Iman/Git-Lite/issues)
- 💡 [Request Features](https://github.com/RavenX-Iman/Git-Lite/issues/new)
- 📖 [Contributing Guide](docs/CONTRIBUTING.md)

```bash
# Contribution workflow
git checkout -b feature/your-feature
# Make changes...
git commit -m "Add: feature description"
git push origin feature/your-feature
# Open PR on GitHub
```

---

## 📝 License

Created for educational purposes as part of academic coursework at COMSATS University Islamabad.

**Free to use, modify, and learn from** • Please credit original authors

---

<div align="center">

**[⬆ Back to Top](#-git-lite)**


</div>
