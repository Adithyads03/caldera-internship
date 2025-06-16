# Remote Agent Deployment

✅ **Objective**: Deploy an agent on a remote host (different OS) and ensure it beacons back.

### Setup

- **Caldera Server OS**: Linux (Ubuntu)
- **Remote Host OS**: Windows 10 (VirtualBox)
- **Agent Type**: Sandcat
- **Protocol**: HTTP

### Steps Followed

1. Started Caldera server on Linux.
2. Navigated to **CAMPAIGNS > Agents** → clicked **+ Deploy Agent**.
3. Selected:
   - Agent: **Sandcat**
   - Platform: **Windows**
   - Updated `app.contact.http` to: `http://10.0.2.15:8888`
4. Copied the PowerShell command and ran it on Windows VM.
5. Agent appeared in Caldera under Agents tab with a green dot.

✅ Agent successfully beaconed back to the server.

