# 🧪 Configuration

> ⚠️ Run everything as Administrator

---

# 🖥️ Open Command Prompt

| Step | Action |
|------|--------|
| 1 | Open Start Menu |
| 2 | Search "cmd" |
| 3 | Right-click |
| 4 | Run as Administrator |

---

# ⚡ System Commands

| Command | Purpose |
|--------|--------|
| bcdedit /set testsigning on | Enables test mode |
| bcdedit /set nointegritychecks on | Disables integrity checks |

---

# ▶️ Execution Steps

| Step | Command |
|------|--------|
| 1 | bcdedit /set testsigning on |
| 2 | bcdedit /set nointegritychecks on |

---

# ⚠️ Notes

| Info | Description |
|-----|------------|
| Test Mode | Allows unsigned drivers |
| Integrity Checks | Normally protects system |
| Risk | Reduced system security |

---

## ✅ Status

| Check | Result |
|------|--------|
| Commands executed | ✔ |
| No errors | ✔ |
