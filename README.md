# Active Directory Permission Abuse Matrix


| Matrix  | User | Group  | Computer | Domain  | GPO | OU
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
|**GenericAll**   | Reset user password + Targeted Kerberoast  | Add user to Group|RBCD - Computer takeover + ReadLAPSPassword | N/A | N/A | N/A
| **GenericWrite**  | Create Logon Scripts + Targeted Kerberoast | Add user to Group | RBCD - Computer takeover|N/A | N/A | N/A
|**WriteOwner**  | Change Owner|Change Owner|Change Owner|N/A|N/A|N/A
|**WriteDACL** |Reset Password|Grant yourself the right to add members to the group|RBCD - Computer takeover + ReadLAPSPassword | N/A | N/A | N/A
|**AllExtendedRights** |Reset user password	|Add to Group	RBCD - Computer takeover|	N/A|N/A|N/A
|**ForcePasswordChange** 	|Reset user password|	N/A	|Reset user password|	N/A	|N/A|	N/A
|**Own** |Modify the DACL of the object|	Modify the DACL of the object|	Modify the DACL of the object	|modify the DACL of the object	|modify the DACL of the object	|Modify the DACL of the object
