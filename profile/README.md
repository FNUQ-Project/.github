
# FNUQ-Project 🚀

**F**uck **N**o **U**EFI's **Q**EMU - A modern, macOS-native hypervisor ecosystem

> "Building virtualization tools that don't suck, for developers who value their sanity."

---

## 🎯 About This Organization

FNUQ-Project is a collection of open-source projects dedicated to creating modern, macOS-native virtualization tools. We believe virtualization should be fast, simple, and enjoyable to use.

### Our Projects

| Project | Status | Description |
|---------|--------|-------------|
| **https://github.com/FNUQ-Project/FNUQ-Core** | 🟢 Active | Core hypervisor engine  |
| **https://github.com/FNUQ-Project/FnuqCommand** | 🟢 Active |CLI|
| **https://github.com/FNUQ-Project/FNUQ-UI** | 🟡 Planning | Modern SwiftUI interface |
| **https://github.com/FNUQ-Project/FNUQ-UEFI** | 🟡 Planning | Native UEFI implementation |
| **https://github.com/FNUQ-Project/FNUQ-Docs** | 🟡 Planning | Documentation and guides |

### Why We Exist
One very simple reason is that we developed an operating system (a microkernel operating system called E-comOS). For security, we used UEFI + a 64-bit kernel. However, QEMU, unfortunately, has "less than ideal" support for UEFI. We were too lazy to develop another UTM or Broadcom's VMware Fusion—they're too large. So, we decided to rewrite a QEMU-like virtual machine software that has both a visual interface and a command-line interface for ease of use, to test our kernel.

---

## 🚀 Getting Started

### Quick Install
```bash
git clone https://github.com/FNUQ-Project/FNUQ-Core.git
cd FNUQ-Core
swift build -c release
```

### Your First VM
```bash
# Create a VM with sensible defaults
fnuq create my-vm --memory 4 --disk 20

# Start it
fnuq start my-vm

# Check status
fnuq list
```

---

## 🤝 Contributing

We welcome contributions! Here's how to get involved:

### For Developers
Check our https://github.com/FNUQ-Project/FNUQ-Core/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22


### For Users
- Report bugs via https://github.com/FNUQ-Project/FNUQ-Core/issues

- Improve our https://github.com/FNUQ-Project/FNUQ-Docs

### Code Standards
- Follow Swift API Design Guidelines
- Write tests for new features
- Document public APIs
- Keep it simple and maintainable

---



## 🏗️ Architecture

FNUQ projects follow a modular architecture:

```
FNUQ-Project/
├── FNUQ-Core/          # Hypervisor engine (Swift CLI)
├── FNUQ-UI/           # SwiftUI interface (Future)
├── FNUQ-UEFI/         # Native UEFI (Future)  
└── FNUQ-Docs/         # Documentation
```

### Technology Stack
- **Language**: Swift 5.5+
- **Virtualization**: Hypervisor.framework
- **Platform**: macOS 11.0+
- **Build**: Swift Package Manager

---

## 🌟 Our Principles

1. **Developer Experience First** - Tools should be joyful to use
2. **macOS Native** - Embrace the platform, don't fight it  
3. **Simplicity** - Complex problems, simple solutions
4. **Performance** - Fast, efficient, battery-friendly
5. **Openness** - Build in public, welcome contributions

---

## 📫 Connect With Us
- **Issues**: https://github.com/FNUQ-Project/FNUQ-Core/issues
- **Twitter**: https://twitter.com/Saladin131211
- **Email**: saladin510@outlook.com
---

## 📄 License

All FNUQ-Project repositories are released under the GNU AGPL License. See individual repositories for details.

---

## 🙏 Acknowledgments

- Apple for Hypervisor.framework and Swift
- The Swift community for amazing tools
- Early contributors and testers
- Everyone who believed virtualization could be better

---

<div align="center">

### **Better virtualization tools for macOS developers.**

https://github.com/FNUQ-Project • 
https://github.com/FNUQ-Project/FNUQ-Docs • 
https://github.com/FNUQ-Project/FNUQ-Docs/blob/main/CONTRIBUTING.md

*Built with ❤️ for developers who deserve better tools.*

</div>
```

