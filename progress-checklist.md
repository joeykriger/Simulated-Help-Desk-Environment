### A1 Verification

- [X] `ipconfig /all` shows `HV-DC01`, IPv4 address `192.168.10.10`, and the default gateway you entered.
- [X] `ping 8.8.8.8` gets replies.
- [X] `slmgr /dlv` opens a dialog that lists the remaining evaluation time (about 180 days).

### A2 Verification

- [X] **Server Manager** shows **AD DS** and **DNS** with green status.
- [X] **Tools > Active Directory Users and Computers** opens, and **Domain Controllers** contains `HV-DC01`.

### A3 Verification

- [X] **Tools > Active Directory Users and Computers > harborview.local > Computers** lists `HV-WS01`.

### A5 Verification

- [X] **Entra ID > Overview** shows the tenant name and the license **Microsoft Entra ID Free**.
- [X] **Entra ID > Users** lists your administrator account.
- [X] **Properties > Manage security defaults** shows **Enabled**.

## Lab Completion Checklist

- [X] `HV-DC01` runs Windows Server 2022 with static IP `192.168.10.10`.
- [X] Domain `harborview.local` exists, and DNS resolves both internal and internet names.
- [X] `HV-WS01` runs Windows 11 Enterprise and shows in the **Computers** container.
- [X] Jira Service Management has 7 new request types and the priority table is defined.
- [X] A test ticket exists with Priority set to Medium.
- [X] The Entra ID Free tenant is confirmed, and security defaults are enabled.
- [X] Snapshots `A1-clean-install`,`A2-domain-controller`, and `A3-domain-joined` exist.