```
_______________
|
|
|
|       ____________
|                   |
|                   |
|                   |
|___________________|


```
# Ghis.DotNetCore.Utility

Just a collection  and Interaces when  you use .Net Core 3 in Project

# Publishing New Package

To publish a new package:

- Update the `Project > Properties > Package > Package Version` 
- Change `Configuration` to `Release`
- Right-click project and select `Pack`
- Go to output folder `bin\Release` and you should see a `Ghis.DotNetCore.Utility.x.x.x.nupkg`
- Start a `cmd` in that folder and type: `dotnet nuget push Ghis.DotNetCore.Utility.x.x.x.nupkg -k yournugetkey -s https://api.nuget.org/v3/index.json`
- `yournugetkey`: Nuget.org context menu and Api key can be read. 