# Third-Party Open Source Licenses

SpeedPingur uses the following open source components.

*Last Updated: December 3, 2025*

---

## Python

**Version:** 3.11+  
**License:** PSF License Version 2  
**Copyright:** © 2001-2025 Python Software Foundation  
**Website:** https://www.python.org/  
**License URL:** https://docs.python.org/3/license.html

### Summary
Python runtime used as core application framework.

### License Type
BSD-style permissive license. Compatible with proprietary software.

### Compliance
- ✅ PSF copyright notice included
- ✅ License text provided (this file)
- ✅ No modifications to Python core

---

## PyQt6

**Version:** 6.10.0+  
**License:** GPL v3  
**Copyright:** © Riverbank Computing Limited  
**Website:** https://riverbankcomputing.com/software/pyqt/  
**License URL:** https://www.gnu.org/licenses/gpl-3.0.html

### Summary
GUI framework for application interface.

### License Type
GPL v3 - Compatible via dynamic linking.

### Distribution Method
SpeedPingur uses PyQt6 as a **dynamically linked library** (--onedir build):
- PyQt6 files in separate `_internal/` folder
- Not compiled into executable
- Users can replace PyQt6 libraries
- This is permitted under GPL v3

### Compliance
- ✅ PyQt6 distributed as separate DLL files
- ✅ Not statically linked into executable
- ✅ GPL v3 license included (this file)
- ✅ Source code available at: https://riverbankcomputing.com/software/pyqt/download
- ✅ Users can replace libraries
- ✅ SpeedPingur code remains proprietary

### Qt Framework (PyQt6-Qt6)

**Version:** 6.10.1+  
**License:** LGPL v3  
**Copyright:** © The Qt Company Ltd  
**Website:** https://www.qt.io/  
**License URL:** https://www.gnu.org/licenses/lgpl-3.0.html

### LGPL Compliance
- ✅ Qt used as dynamic library
- ✅ Qt source available at: https://code.qt.io/
- ✅ Users can replace Qt libraries
- ✅ LGPL license provided

---

## speedtest-cli

**Version:** 2.1.3+  
**License:** Apache License 2.0  
**Copyright:** © 2012-2025 Matt Martz  
**Repository:** https://github.com/sivel/speedtest-cli  
**License URL:** https://www.apache.org/licenses/LICENSE-2.0

### Summary
Network speed testing engine.

### License Type
Permissive license. Compatible with proprietary software.

### Compliance
- ✅ Apache 2.0 license included
- ✅ Copyright notice retained
- ✅ No modifications made

---

## License Summaries

### PSF License (Python)
- ✅ Use in proprietary software
- ✅ No source code disclosure required
- ✅ Commercial use allowed

### GPL v3 (PyQt6)
- ✅ Use in proprietary software (dynamic linking)
- ✅ Separate library files (--onedir)
- ✅ No source disclosure required for your app
- ✅ PyQt6 source publicly available

### LGPL v3 (Qt Framework)
- ✅ Use in proprietary software (dynamic linking)
- ✅ No source disclosure for your app
- ✅ Qt source publicly available
- ✅ Users can replace Qt libraries

### Apache 2.0 (speedtest-cli)
- ✅ Use in proprietary software
- ✅ No source code disclosure required
- ✅ Commercial use allowed

---

## Full License Texts

**PSF License:** https://docs.python.org/3/license.html  
**GPL v3:** https://www.gnu.org/licenses/gpl-3.0.html  
**LGPL v3:** https://www.gnu.org/licenses/lgpl-3.0.html  
**Apache 2.0:** https://www.apache.org/licenses/LICENSE-2.0

---

## Contact

License questions: thestoicspirit13@gmail.com  
GitHub Issues: https://github.com/TheStoicSpirit/SpeedPingur/issues

---

*This document reflects component licenses as of December 3, 2025. Verify current licenses before distribution.*