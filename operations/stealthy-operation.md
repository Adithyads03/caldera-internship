# Stealthy Operation - Using Obfuscation and Jitter

## Objective

Run and complete an operation using:
- **Check** adversary profile (from Stockpile)
- **base64** obfuscation
- **Jitter**: 10/20
- Auto-close enabled

---

##  Steps Followed

### Agent Setup
- Ensured at least one agent was deployed and responsive.

---

### Operation Setup

1. Navigated to: **CAMPAIGNS > Operations**
2. Clicked **+ Create Operation**

### Operation Configuration:
- **Operation Name**: Stealthy Base64 Test
- **Adversary**: `Check` (from Stockpile plugin)
- **Fact Source**: `basic`

### Advanced Options:
- Clicked **ADVANCED**
- **Obfuscator**: Selected `base64`
- **Auto-close Operation**: Enabled
- **Jitter (sec/sec)**: Set to `10/20`

---

### Execution
- Pressed **Start** to run the operation.
- Waited for the operation to finish automatically.

---

✅ **Operation completed successfully with base64 obfuscation and 10/20 jitter.**
