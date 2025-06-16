# Custom Ability: My test ability

## Objective
Create a new ability named **"My test ability"** and add it to the **Certifiable** adversary profile.

---

##  Steps Followed

### Create the Ability
1. Navigated to **CAMPAIGNS > Abilities**
2. Clicked **+ Create an Ability**

### Filled in the following fields:
- **Name**: My test ability  
- **Description**: My description  
- **Tactic**: discovery  
- **Technique ID**: T2000.01  
- **Technique Name**: Account Discovery: Domain Account

---

### ➕ Executors Configuration
- **Platform**: `darwin` (MacOS)
- **Executor**: `sh`
- **Command**:
  ```sh
  whoami
- **Add Cleanup Command:
  ifconfig -a
