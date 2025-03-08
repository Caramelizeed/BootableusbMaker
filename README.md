# 💾 USB Bootable Creator

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.6+-blue.svg)](https://www.python.org/downloads/)

A modern, user-friendly GUI application to create bootable USB drives from ISO images across multiple operating systems.

## ✨ Features

- 🖥️ Modern, intuitive user interface
- 🔄 Cross-platform compatibility (Windows, macOS, Linux)
- 💽 Support for multiple file systems (FAT32, NTFS, exFAT)
- 🚀 Simple 3-step process to create bootable USB drives
- 📊 Real-time progress tracking and operation logs
- 🛡️ Safety confirmations to prevent accidental data loss
- 🔧 Customizable formatting options

## 📋 Requirements

- Python 3.6 or newer
- Tkinter (usually included with Python)
- Platform-specific dependencies:
  - Windows: `pywin32` package
  - Linux: Administrative privileges for device access
  - macOS: Administrative privileges for device access

## 🔧 Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/usb-bootable-creator.git
cd usb-bootable-creator
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

*Note: On Windows, you'll need to install the pywin32 package: `pip install pywin32`*

## 🚀 Usage

Run the application:

```bash
python main.py
```

### Creating a Bootable USB:

1. **Select ISO Image**: Click "Browse" to select your bootable ISO file
2. **Select USB Drive**: Choose your USB drive from the detected devices list
3. **Configure Options**: Set file system type and other formatting options
4. **Create**: Click "Create Bootable USB" to start the process

## ⚙️ Advanced Options

- **File System Selection**: Choose between FAT32, NTFS, or exFAT
- **Cluster Size**: Customize allocation unit size for optimal performance
- **Format Drive**: Option to format drive before creating bootable USB

## 🔒 Safety Features

The application includes multiple safety measures:
- Drive selection confirmation with drive details
- Clear warnings before any destructive operations
- Real-time logging of all operations

## 🛠️ Technical Details

The application uses:
- Tkinter for the GUI framework
- Platform-specific disk utilities for device operations
- Threading to prevent UI freezing during operations
- Modern styling with custom TTK theme configuration

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## ⚠️ Disclaimer

This software modifies storage devices at a low level. While safety measures are in place, 
incorrect use can result in data loss. Always back up important data before using this tool.
The developers are not responsible for any data loss that may occur.

## 🙏 Acknowledgments

- Thanks to all the testers and contributors
- Inspired by similar tools like Rufus, UNetbootin, and Etcher
