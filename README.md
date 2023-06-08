# dumpbin.exe
Microsoft COFF Binary File Dumper - Extract from Visual Studio Community 2022
Download from [Releases](../../releases).

## Usage

This option displays all definitions exported from an executable file or DLL.
```
dumpbin.exe /exports *.dll
```

This option displays public symbols defined in a library.
```
dumpbin.exe /linkermember *.lib
```

Dumps the names of the DLLs from which the image imports functions. You can use the list to determine which DLLs to redistribute with your app, or find the name of a missing dependency.
```
dumpbin.exe /dependents *.exe
```
