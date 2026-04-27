# CrystalisAPI (VelocityAPI) Base
Note: this version is probably outdated
Newest version created with .NET 9.0 using VelocityAPI.
# API Using
## Injection:
```cs
int ProcessID = 0;
Process[] processes = Process.GetProcessesByName("RobloxPlayerBeta");
if (processes.Length > 0)
{
    ProcessID = processes[0].Id;
    CrystalisAPI.API.Inject(ProcessID);
}
else
{
    Console.WriteLine("Process not found");
}
```
## Execution:
```cs
string text = TextBox1.Text;
CrystalisAPI.API.Execute(text);
```

## Credits
Credits to VelocityAPI by @cg_official
https://discord.gg/velocityide
