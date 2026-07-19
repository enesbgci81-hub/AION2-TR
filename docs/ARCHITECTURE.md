# AION2-TR Architecture

## 📖 Overview

AION2-TR is an open-source platform that provides Turkish localization and supporting tools for AION 2.

The project is designed to be modular, scalable, and maintainable.

---

# System Architecture

```text
                    AION2-TR
                        │
        ┌───────────────┼───────────────┐
        │               │               │
    Launcher        Documentation     Website
        │
        ▼
  Version Checker
        │
        ▼
 GitHub Releases
        │
        ▼
  Patch Downloader
        │
        ▼
 Patch Installer
        │
        ▼
 Game Files
```

---

# Modules

## Launcher

Responsible for:

- Checking updates
- Downloading patches
- Launching the game
- Displaying announcements

---

## Patch Engine

Responsible for:

- Installing localization files
- Restoring original files
- Verifying file integrity

---

## Translation System

Responsible for:

- Turkish localization
- Translation packages
- Versioning

---

## Documentation

Contains:

- Installation guides
- Contribution guides
- Development documentation

---

## Website

Provides:

- News
- Downloads
- Documentation
- Release Notes

---

# Technologies

| Module | Technology |
|---------|------------|
| Launcher | Flutter |
| Backend | GitHub Releases |
| Version Control | Git |
| Documentation | Markdown |
| CI/CD | GitHub Actions |

---

# Future Modules

- Discord Integration
- Auto Translation Assistant
- Plugin Support
- Multi-language Support