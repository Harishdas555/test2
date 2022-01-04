#### Battery change in WZS12 - 172.16.10.22
```sh
Time required: 1-2 hours down time
```
| Host name | Server | Impact |
| --------- | ------ | ------ |
WZVDC02 |	Secondary Active Directory Controller |	No impact to production
WMV02 |	Fileserver , Print server	|Production Print server with Label Location
WMV04|	SQL Server 2005 Ent, Packworkz DB	|Packworkz
WZV04|	Web Server 	|CCP
WZV08|	New File Server	|T drive
WZV11|	Office 365 Sync	|No impact to production
WZV32|	MatrixPay and QB|	No impact to production (MatrixPay - HR)
WZV46|	Codesoft License server|	Impact on Label printing




