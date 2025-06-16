# Empty Operation with Manual Links

## Objective

Run and complete a Caldera operation without selecting any adversary profiles, and manually add at least 5 manual commands or potential links  before completing the operation.

---

##  Steps Performed

### Preparation
- Verified that at least one agent was online and responsive.

---

### Operation Setup

1. Navigated to: `CAMPAIGNS > Operations`
2. Clicked **+ Create Operation**

### Operation Configuration:
- **Operation Name**: Empty Op Manual Test
- **Adversary**: _Not selected_
- **Agent Group**: _Not selected_
- **Fact Source**: basic
- Clicked **Start**

---

### 🔗 Manually Added Commands (Links)

Once the operation started, manually added 5 commands to the agent from the **Manual Command entry** in the operation window.

| # | Command                          | Purpose                              |
|---|----------------------------------|--------------------------------------|
| 1 | `whoami`                         | Identify current user                |
| 2 | `hostname`                       | Get host machine name                |
| 3 | `ifconfig` / `ip addr`           | View network interfaces              |
| 4 | `ps -ef`                         | List all running processes           |
| 5 | `uptime`                         | Check system uptime                  |

> All commands were run successfully through the agent and responses were reviewed.

---

### Completion

- After all 5 links were executed, the operation was stopped manually.

✅ Empty operation completed with 5 manual links added and executed.
