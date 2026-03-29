# Open Source Software - Audit Report

## 📋 Project Overview

This repository contains a comprehensive audit and analysis of **VLC Media Player** as part of the Open Source Software course at VIT Bhopal. The project explores the technical, philosophical, and practical aspects of open-source software through the lens of one of the most successful FOSS projects in history.

## 👨‍🎓 Project Information

- **Course**: Open Source Software
- **Type**: Project Report
- **Student**: Rohit Dubey
- **Registration Number**: 24BAI10353
- **University**: VIT Bhopal
- **Slot**: F11
- **Faculty**: Dr. Saravanan D
- **Submission Date**: March 31, 2026

## 📑 Report Structure

### Part A: Conceptual Analysis

1. **Introduction**
   - The evolution of software development
   - Importance of open-source philosophy
   - Why VLC Media Player was chosen

2. **Origin Story of VLC**
   - Digital media landscape before VLC
   - The VideoLAN project beginnings (1996)
   - Transition to open source under GPL (2001)

3. **License Analysis**
   - GNU General Public License (GPL) breakdown
   - The Four Freedoms of free software
   - Copyleft clause and its implications
   - GPL vs MIT license comparison

4. **Ethics of Open Source**
   - Open source as a philosophy of knowledge
   - The debate: should all software be open?
   - Standing on the shoulders of giants

### Part B: Technical Implementation

5. **Linux Installation Method**
   - Installation via apt package manager
   - Binary and key directories (`/usr/bin`, `/usr/lib`, `/usr/share`)
   - Configuration files (`~/.config/vlc`, `~/.local/share/vlc`)
   - User permissions and security
   - Process execution model
   - Update mechanism

6. **FOSS Ecosystem**
   - VLC's dependencies (FFmpeg, libMPEG2)
   - Community-driven governance by VideoLAN
   - Strategic position in the tech stack
   - The strength of the commons

7. **Comparison**
   - VLC vs Windows Media Player
   - Feature analysis across multiple dimensions

## 🛠️ Included Scripts

This project includes five bash scripts demonstrating system administration and auditing capabilities:

### 1. System Identity Report (`system_identity.sh`)
Captures and displays system information including kernel version, username, and uptime.

**Usage:**
```bash
./system_identity.sh
```

### 2. FOSS Package Inspector (`package_inspector.sh`)
Checks if a package is installed and displays metadata (version, license, summary).

**Usage:**
```bash
./package_inspector.sh
```

### 3. Disk & Permission Auditor (`disk_audit.sh`)
Audits critical directories for permissions and disk usage.

**Usage:**
```bash
./disk_audit.sh
```

### 4. Log File Analyzer (`log_analyzer.sh`)
Searches log files for specific keywords and counts occurrences.

**Usage:**
```bash
./log_analyzer.sh /var/log/syslog error
```

### 5. Open Source Manifesto Generator (`manifesto.sh`)
Interactive script that generates a personalized open-source manifesto.

**Usage:**
```bash
./manifesto.sh
```

## 🔑 Key Takeaways

### Technical Insights
- VLC uses the GPL license to ensure code remains free and improvements flow back to the community
- The software demonstrates modularity through plugin architecture
- Installation follows Linux File System Hierarchy Standard
- Security through principle of least privilege

### Philosophical Insights
- Open source accelerates innovation by preventing redundant work
- Transparency enables better security through community auditing
- GPL's "copyleft" prevents corporate hijacking of community projects
- Open source represents a shift from scarcity to abundance mindset

## 🎯 Project Conclusions

VLC Media Player exemplifies the practical success of open-source philosophy:

1. **Universal Accessibility**: Free to use for any purpose without restrictions
2. **Technical Excellence**: Supports virtually all media formats without external codecs
3. **Community Strength**: Maintained by VideoLAN, a nonprofit organization
4. **Proven Reliability**: Used by millions worldwide, competing with commercial alternatives
5. **Sustainable Model**: Dependencies on other FOSS projects create a circular economy of knowledge

## 📚 References

- GNU General Public License documentation
- VideoLAN project official documentation
- Free Software Foundation's Four Freedoms
- Linux File System Hierarchy Standard

## 🔗 Related Links

- [VLC Official Website](https://www.videolan.org/)
- [VideoLAN Organization](https://www.videolan.org/videolan/)
- [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html)
- [Free Software Foundation](https://www.fsf.org/)

## 📄 License

This project report is submitted as academic work for VIT Bhopal. The analyzed software (VLC Media Player) is licensed under GPL v2+.

## 🤝 Acknowledgments

- **Dr. Saravanan D** - Course Faculty
- **VideoLAN Team** - For creating and maintaining VLC
- **Open Source Community** - For making projects like this possible

---

*"Standing on the shoulders of giants" - The essence of open source development*
