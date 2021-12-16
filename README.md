# WebApiAsWindowsService
NET 6.0 ASP.NET Core WebApi running as Windows Service


## Run as Windows Serice

### Create the Windows Service

```PowerShell
sc.exe create "MyWebApiServiceName" binpath="C:\Path\WebApiService.exe"
```

### Start the Windows Service

```PowerShell
sc.exe start "MyWebApiServiceName"
```

### Stop the Windows Service

```PowerShell
sc.exe stop "MyWebApiServiceName"
```

### Remove the Windows Service
```PowerShell
sc.exe delete "MyWebApiServiceName"
```
