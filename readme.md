# FileTimeModifier Version 1.2
![ICON](https://github.com/Arryboom/FTM/blob/master/clock_93.613766730402px_1159590.png)  
Source file ftm.e.
## 
|     Param      | Means                                       |
| :----------: | ---------------------------------------- |
|   -p   | Path to the File or Dir where need to modify timestamp  |
| -t | Specfic File Time you want,without this param will be Random |
| -nd | Don't Include Sub Directory |
| -od | Include Sub Directory and file in it,No Recursion |
| -rd | Include Recursion Sub Directory and file in it    |
| -ct | Modify Creation Time |
| -mt | Modify Modifiction Time |
| -at | Modify Access Time  |
| -utc | This use the time you input or random generated time as UTC time |
| -v | Print all new filename and timestamp to screen after finished  |
| -h | HelpText  |
## 
## example:
ftm -p 'd:\directory\' -v


> this will give a random timestamp from 1970-01-01 to 2100-01-01
 to all creation,modifiction,access time for all file or dir in d:\directory\
 
ftm -p 'd:\file\doc.txt' -t '1982-01-01' 
> this will modify the creation,modfied,access time of doc.txt to 
 '1982-01-01'
 
ftm -p 'd:\file\doc.txt' -t '1982-01-01' -ct 
> this will modify the creation time of doc.txt to '1982-01-01'

Time Format:
>current accepted these time format below.  
1973/11/15 12:30:25  
1973/11/15/12/30/25  
1973/11/15/12:30:25  
1973-11-15-12-30-25  
1973-11-15-12:30:25  
1973.11.15 12:30:25  
19731115123025  

## Version

File: ftm.exe  
Size: 927232 bytes  
File Version: 1.2.0.0  
Modified: 2018-06-11,15:58:42  
MD5: 0403366845114980BAACA949312E9BAF  
SHA1: C746CC17B825373E4E5A1FE06466F877C463912B  
CRC32: FBD678E4  

File: ftm_upx.exe  
Size: 413696 bytes  
File Version: 1.2.0.0  
Modified: 2018-06-11,15:58:42  
MD5: BC71CAFAEB08E24AEACA331BD4DA68FD  
SHA1: B5863A8208CD8A0E6F898E792AC5920DB2CFED5D  
CRC32: 936AE9D5  

>ftm_upx.exe was compressed by UPX packer. 
