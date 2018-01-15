# visualstudiocode-usersetting
User setting files for [Visual Studio Code](https://code.visualstudio.com/)

## How to use

Make symlink to User directory.

### On Windows

Run the following commands on PowerShell as Administrator.

```PowerShell
PS > cd "C:\Users\$(Get-Content env:username)\AppData\Roaming\Code"
PS > rm .\User\
PS > cmd /c mklink /D User "C:\Users\$(Get-Content env:username)\Documents\git\visualstudiocode-usersetting\User" 
```
