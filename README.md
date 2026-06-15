# Win-Object-Count

PowerShell script that checks whether a file or directory exists under a given path.

The script can be used for monitoring purposes and can trigger an alert when the object exists and is older than a defined number of days.

## Usage

```powershell
powershell.exe .\objectCount.ps1 -P [object_path] -D [days]
