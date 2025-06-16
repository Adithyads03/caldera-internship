# Manual Operation 

## Objective

Run and finish an operation using **any adversary profile except Check**, with **manual approval** enabled.  
At least **5 commands (links)** were either approved or discarded during the operation.

---

##  Steps Performed

### Agent Setup
- Ensured a responsive agent was deployed.

---

### Operation Setup

1. Navigated to: `CAMPAIGNS > Operations`
2. Clicked **+ Create Operation**

### Operation Configuration:
- **Operation Name**: Manual Link Review
- **Adversary Profile**: `Nosy Neighbor` (other than Check)
- **Fact Source**: `basic`
- Enabled **Manual approval required**
- Selected **Auto-close** disabled (to control the flow manually)

---

### ⚙️ Manual Link Review Process

Waited for links (commands) to queue up and manually reviewed each one.

### ✅ Approved / ❌ Discarded Commands

| # | Command Description              | Action Taken |
|---|----------------------------------|--------------|
| 1 | `whoami`                         | ✅ Approved  |
| 2 | `hostname`                       | ✅ Approved  |
| 3 | `ps -ef`                         | ✅ Approved  |
| 4 | `ifconfig`                       | ❌ Discarded |
| 5 | `cat /etc/passwd`                | ✅ Approved  |

> Some links were rejected if they seemed redundant or unnecessary during the run.

---

###  Completion

- After reviewing all links, clicked **Stop** to finish the operation.

✅ **Manual operation completed with 5 commands reviewed.**

---

