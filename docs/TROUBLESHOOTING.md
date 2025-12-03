# Troubleshooting

Quick fixes for common issues.

---

## 🛠️ Installation

**Install fails:**
```
1. Run as administrator
2. Check 100MB free space
3. Close SpeedPingur if running
4. Disable antivirus temporarily
```

**SmartScreen blocks:**
```
"More info" → "Run anyway"
```

**Antivirus flags:**
```
Add to exclusions: C:\Program Files\SpeedPingur
```

## 🚫 Won't Start

**Nothing happens:**
```
1. Install: https://aka.ms/vs/17/release/vc_redist.x64.exe
2. Run as administrator
3. Check Windows 10+ (64-bit)
```

**Missing DLL:**
```
Install Visual C++ Redistributable (link above)
```

**Crashes:**
```
1. Delete: %localappdata%\SpeedPingur
2. Reinstall
```

## 🧪 Test Problems

**Test fails:**
```
1. Check internet (open browser)
2. Disable VPN
3. Restart app
4. Restart router
```

**Test hangs:**
```
1. Wait 2-3 minutes
2. Close bandwidth-heavy apps
3. Restart router
```

**Can't connect:**
```
cmd: ipconfig /flushdns
cmd: netsh winsock reset
Restart computer
```

## 📉 Slow Results

**Much slower than plan:**
```
1. Close all apps
2. Use Ethernet (not WiFi)
3. Run 3 tests, average them
4. If still slow → ISP issue
```

**Fixes WiFi:**
- Move closer to router
- Use Ethernet cable
- Restart router

**Results vary:**
```
Normal! Internet fluctuates.
Run 5 tests, calculate average.
```

**High ping:**
```
- Use Ethernet
- Disable VPN
- Test late night
- Contact ISP if persistent
```

## 📜 History Issues

**Not saving:**
```
1. Check disk space
2. Delete: %localappdata%\SpeedPingur\history.json
3. Restart app (creates new)
```

**Export fails:**
```
1. Save to Desktop
2. Close Excel/CSV viewers
```

**History gone:**
```
Check backup: %LocalAppData%\SpeedPingur\backup\
Use file recovery (Recuva)
```

## 🛡️ Defender/Firewall

**Defender blocks:**
```
Windows Security → Protection history → Restore
Add exclusion: C:\Program Files\SpeedPingur
```

**Firewall blocks:**
```
Windows Firewall → Allow app → Add SpeedPingur.exe
Check Private + Public networks
```

## 🌐 Network

**VPN interfering:**
```
Test with VPN off (ISP speed)
Test with VPN on (VPN speed)
```

**Work/school blocks:**
```
Contact IT or use personal network
```

---

## 📞 Still Stuck?

- [GitHub Issues](https://github.com/TheStoicSpirit/SpeedPingur/issues)
- [Discussions](https://github.com/TheStoicSpirit/SpeedPingur/discussions)

Include:
- SpeedPingur version
- Windows version
- Error message
- What you tried