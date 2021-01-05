# Visual Studio 2012
#### Update Registry 
```
C:\Users\boverhof\Desktop>more update_registry.reg
Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\.NETFramework\v4.0.30319]
"SchUseStrongCrypto"=dword:00000001

[HKEY_LOCAL_MACHINE\SOFTWARE\Wow6432Node\Microsoft\.NETFramework\v4.0.30319]
"SchUseStrongCrypto"=dword:00000001

C:\Users\boverhof\Desktop>update_registry.reg

```
#### Open TurbineLite project
##### Install NuGet command line tool
- Open Package Manager Console in Visual Studio under tab `Tools`, `Library Package Manager`
```
PM> Install-Package NuGet
```

