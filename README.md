# Open Source Software - Audit

**VLC Media Player Analysis**  
A Capstone Project for OSS Course - VIT Bhopal

---

## Project Information

- **Course**: Open Source Software
- **Student**: Rohit Dubey
- **Registration Number**: 24BAI10353
- **University**: VIT Bhopal
- **Slot**: F11
- **Faculty**: Dr. Saravanan D
- **Submission Date**: 31st March 2026
- **Chosen Software**: VLC Media Player

## About This Project

This project is a comprehensive audit of VLC Media Player covering:
- Origin story and philosophy of open source
- License analysis (GPL)
- Ethics of open source development
- Linux installation and footprint
- FOSS ecosystem analysis
- Comparison with proprietary alternatives
- Five bash scripts demonstrating Linux skills

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

## Prerequisites

- Linux system (Ubuntu 22.04 or similar)
- Bash shell
- VLC Media Player
- Basic command-line utilities (grep, awk, du, ps)

## Setup Instructions

### 1. Install VLC

```bash
sudo apt update
sudo apt install vlc
```

### 2. Prepare Scripts

```bash
# Create project directory
mkdir ~/OSS_Capstone
cd ~/OSS_Capstone

# Make all scripts executable
chmod +x *.sh
```

## The Five Scripts

### 1. System Identity Report (`system_identity.sh`)

Displays system information for the open source audit.

**What it does:**
- Shows kernel version
- Displays current user
- Shows system uptime
- Displays distribution name, date, and license

**Usage:**
```bash
./system_identity.sh
```

---

### 2. FOSS Package Inspector (`package_inspector.sh`)

Checks if VLC is installed and displays package information.

**What it does:**
- Checks if package is installed using dpkg (Ubuntu/Debian)
- Displays version, license, and summary
- Includes philosophical notes about open-source packages

**Usage:**
```bash
./package_inspector.sh
```

**Note for Ubuntu users:** The script uses `dpkg` instead of `rpm`.

---

### 3. Disk & Permission Auditor (`disk_audit.sh`)

Audits system directories for permissions and disk usage.

**What it does:**
- Loops through critical directories (/etc, /var/log, /home, /usr/bin, /tmp)
- Shows permissions and owner for each directory
- Displays disk usage for each directory

**Usage:**
```bash
./disk_audit.sh
```

---

### 4. Log File Analyzer (`log_analyzer.sh`)

Searches log files for specific keywords.

**What it does:**
- Reads a log file line by line
- Counts occurrences of a keyword (default: "error")
- Displays the count and last 5 matching lines

**Usage:**
```bash
./log_analyzer.sh /var/log/syslog error
```

**Arguments:**
- `$1` - Path to log file
- `$2` - Keyword to search (optional, defaults to "error")

---

### 5. Open Source Manifesto Generator (`manifesto.sh`)

Creates a personalized open-source philosophy statement.

**What it does:**
- Asks three interactive questions
- Generates a manifesto paragraph
- Saves to a text file named `manifesto_username.txt`

**Usage:**
```bash
./manifesto.sh
```

## Common Issues

| Problem | Solution |
|---------|----------|
| Permission denied | `chmod +x *.sh` |
| Command not found | Use `bash script_name.sh` |
| Can't access log files | Use `sudo` |
| VLC not installed | `sudo apt install vlc` |

## Report Structure

The complete project report (`oss-audit_24BAI10353.pdf`) contains:

### Part A - Origin and Philosophy
- Introduction to open source and VLC
- The digital media landscape before VLC (late 1990s-early 2000s)
- The VideoLAN project - origin story (1996)
- Transition to open source under GPL (2001)

### Part B - License Analysis
- Understanding the GPL license
- The Four Freedoms of free software
- Copyleft clause and corporate use
- GPL vs MIT comparison

### Part C - Ethics of Open Source
- Open source as a philosophy of knowledge
- Debate: should all software be open source?
- Standing on the shoulders of giants

### Part D - Linux Footprint
- Installation via apt package manager
- Binary and key directories (/usr/bin, /usr/lib, /usr/share)
- Configuration files (~/.config/vlc, ~/.local/share/vlc)
- User permissions and security
- Process execution model
- Update mechanism

### Part E - FOSS Ecosystem
- Dependencies (FFmpeg, libMPEG2)
- Community-driven governance by VideoLAN
- Strategic position in tech stack
- The strength of the commons

### Part F - Comparison
- VLC vs Windows Media Player comparison table
- Conclusion and recommendation

## Key Conclusions

From the project analysis:

1. **VLC demonstrates open-source success** - A project that started in a Paris dorm room in 1996 became a global standard
2. **GPL ensures freedom** - The copyleft clause prevents corporate hijacking while allowing commercial use
3. **Community governance works** - VideoLAN's nonprofit, meritocratic model keeps VLC free of ads and tracking
4. **Open source accelerates innovation** - By building on shared foundations, developers solve higher-level problems
5. **Practical superiority** - VLC's format support and codec library outperform proprietary alternatives

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

## References

- GNU General Public License documentation
- VideoLAN project website
- Free Software Foundation - Four Freedoms
- Linux File System Hierarchy Standard

## Acknowledgments

- **Dr. Saravanan D** - Course Faculty, VIT Bhopal
- **VideoLAN Team** - For creating VLC Media Player
- **Open Source Community** - For making this possible

---

*"Standing on the shoulders of giants" - The essence of open source development*
