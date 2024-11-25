The Powershell script found in this folder will remove the Log Analytics Agent for all your Azure virtual machines. This script is especially useful if you want to switch to using AMA (Azure Monitor Agent) and no longer require the Log Analytics Agent.
The script (once run in the Azure terminal) will do remove the Log Analytics Agent in 3 steps:
1. Find all the Windows VMs in your subscription which have the Log Analytics Agent configured on them.
2. Start each VM (if it's not already running), because the running of a VM is a requirement for removing the Log Analytics Agent.
3. Remove the Log Analytics Agent from each VM.
