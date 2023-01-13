# Under Construction :construction:

# Microsoft Event Matrix

The objective of this project is to compile in a table the relationships between events in the various Microsoft cloud security solutions and events in Windows (Event ID and Sysmon).

## Ressources
- [Azure Monitor Data Schema](https://learn.microsoft.com/en-us/azure/azure-monitor/reference/)
- [Windows Security Event IDs](https://learn.microsoft.com/en-us/windows/security/threat-protection/auditing/advanced-security-audit-policy-settings)
- [Sysmon Event IDs](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon)


## 🍰 Contributing    
Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
        

## License
This project is open source and available under the [MIT License](LICENSE).

  
# Matrix

| Microsoft Event ID  | Sysmon ID | Microsoft Cloud Product         | Data Table            | ActionType                 | Description                                                                                                                       |
| ------------------- | --------- | ------------------------------- | --------------------- | -------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| System 6, 219, 7026 | 6         | Microsoft Defender for Endpoint | DeviceEvents          | DriverLoad                 | Multiple event types, including events triggered by security controls such as Microsoft Defender Antivirus and exploit protection |
|                     | 17        |                                 |                       |                            |                                                                                                                                   |
| 5861,5858,5859      | 20        |                                 |                       |                            |                                                                                                                                   |
| 5861,5858,5860      | 21        |                                 |                       |                            |                                                                                                                                   |
| 5861,5858,5861      | 22        |                                 |                       |                            |                                                                                                                                   |
| 4663                | 11        | Microsoft Defender for Endpoint | DeviceFileEvents      | FileCreated                | File creation, modification, and other file system events                                                                         |
| 4663                |           |                                 |                       | FileModified               | File creation, modification, and other file system events                                                                         |
| 4663                |           |                                 |                       | FileRenamed                | File creation, modification, and other file system events                                                                         |
| 4660                | 23,26     |                                 |                       | FileDeleted                | File creation, modification, and other file system events                                                                         |
|                     | 7         | Microsoft Defender for Endpoint | DeviceImageLoadEvents | ImageLoaded                | DLL loading events                                                                                                                |
| 4624                |           | Microsoft Defender for Identity | IdentityLogonEvents   | LogonSuccess               |                                                                                                                                   |
| 4625                |           |                                 |                       | LogonFailed                |                                                                                                                                   |
| 4624                |           | Microsoft Defender for Endpoint | DeviceLogonEvents     | LogonSuccess               | Sign-ins and other authentication events on devices                                                                               |
| 4625                |           |                                 |                       | LogonFailed                | Sign-ins and other authentication events on devices                                                                               |
| 4648                |           |                                 |                       | LogonAttempted             | Sign-ins and other authentication events on devices                                                                               |
| 4688                | 1         | Microsoft Defender for Endpoint | DeviceProcessEvents   | ProcessCreated             | Process creation and related events                                                                                               |
| 4657                | 13,14     | Microsoft Defender for Endpoint | DeviceRegistryEvents  | RegistryValueSet           | Creation and modification of registry entries                                                                                     |
| 4657                | 12        |                                 |                       | RegistryValueDeleted       |                                                                                                                                   |
| 4656                | 12        |                                 |                       | RegistryKeyCreated         |                                                                                                                                   |
| 4660                | 12        |                                 |                       | RegistryKeyDeleted         |                                                                                                                                   |
| 5156                | 3         |                                 |                       | ConnectionSuccess          | Network connection and related events                                                                                             |
| 5156                | 3         |                                 |                       | NetworkSignatureInspected  |                                                                                                                                   |
| 5156                | 3         |                                 |                       | InboundConnectionAccepted  |                                                                                                                                   |
| 5156                | 3         |                                 |                       | ConnectionFailed           |                                                                                                                                   |
| 5156                | 3         |                                 |                       | ListeningConnectionCreated |                                                                                                                                   |
| 5156                | 3         |                                 |                       | ConnectionFound            |                                                                                                                                   |
| 5156                | 3         |                                 |                       | ConnectionAttempt          |                                                                                                                                   |
| 5156                | 3         |                                 |                       | ConnectionAcknowledged     |                                                                                                                                   |
| 5156                | 3         |                                 |                       | ConnectionRequest          |                                                                                                                                   |
| 4728                |           | Azure Monitoring                | AuditLogs             | Add member to a group      |                                                                                                                                   |
| 4724                |           |                                 |                       | Changer user password      |                                                                                                                                   |
| 4729                |           |                                 |                       | Remove member from group   |                                                                                                                                   |
| 4741                |           |                                 |                       | Add device                 |                                                                                                                                   |
| 4727                |           |                                 |                       | Add group                  |                                                                                                                                   |
| 4725                |           |                                 |                       | Disable account            |                                                                                                                                   |
| 4726                |           |                                 |                       | Delete User                |                                                                                                                                   |
| 4624                |           |                                 | SignInLogs            |                            |                                                                                                                                   |
        
