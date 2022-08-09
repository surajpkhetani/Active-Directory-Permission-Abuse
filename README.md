# Active-Directory-Permission-Abuse

| Matrix | User | Group | Computer | Domain | GPO | OU |
| ------ |
| GenericAll | "Reset user password
Targeted Kerberoast" | Add user to Group | RBCD - Computer takeover | N/A | N/A | N/A
GenericWrite | "Create Logon scripts
Targeted Kerberoast" | Add user to Group | RBCD - Computer takeover | N/A | N/A | N/A
WriteOwner | Change Owner | Change Owner | Change Owner | N/A | N/A | N/A
WriteDACL | Reset Password | Grant yourself the right to add members to the group | "Read LAPS password
RBCD - Computer takeover" | Grant Dcsync permission | Grant full control of the GPO | Grant full control of the OU
AllExtendedWrite | Reset user password | Add to Group | RBCD - Computer takeover | N/A | N/A | N/A
ForcePasswordChange | Reset user password | N/A | Reset user password | N/A | N/A | N/A
Own | Modify the DACL of the object | Modify the DACL of the object | Modify the DACL of the object | modify the DACL of the object | modify the DACL of the object | Modify the DACL of the object
CanRDP | N/A | N/A | RDP Permission to AD Account | N/A | N/A | N/A
AdminTo | N/A | N/A | Remote login permission via RMI, RDP, DCOM, SMB | N/A | N/A | N/A

| Matrix  | User | Group  | Computer | Domain  | GPO | OU
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| GenericAll  | Reset user password + Targeted Kerberoast  | Add user to Group|RBCD - Computer takeover | N/A | N/A | N/A
| Content Cell  | Content Cell  |


![image](https://user-images.githubusercontent.com/25839564/183571990-7628110e-7d18-4aec-883e-41e3b26408ad.png)
