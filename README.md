<div align="center">

## Get Windows and TEMP Folders the easy way, without APIs


</div>

### Description

It returns the path of the windows or temp folders.
 
### More Info
 
The path of the requested folder.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Luis Cantero](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/luis-cantero.md)
**Level**          |Beginner
**User Rating**    |4.7 (14 globes from 3 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Windows System Services](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-system-services__1-35.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/luis-cantero-get-windows-and-temp-folders-the-easy-way-without-apis__1-24604/archive/master.zip)





### Source Code

```
strWindir = Environ("WinDir") ' ->C:\Windows
strTempDir = Environ("temp") ' ->C:\Windows\Temp
strTempDir = Environ("tmp") ' ->C:\Windows\Temp
```

