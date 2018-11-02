---
external help file: Microsoft.Azure.Commands.Profile.dll-Help.xml
Module Name: Az.Profile
online version:
schema: 2.0.0
---

# Get-AzContext

## SYNOPSIS
{{Fill in the Synopsis}}

## SYNTAX

### GetSingleContext (Default)
```
Get-AzContext [-DefaultProfile <IAzureContextContainer>] [[-Name] <String>] [<CommonParameters>]
```

### ListAllContexts
```
Get-AzContext [-ListAvailable] [-DefaultProfile <IAzureContextContainer>] [<CommonParameters>]
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: Microsoft.Azure.Commands.Common.Authentication.Abstractions.IAzureContextContainer
Parameter Sets: (All)
Aliases: AzureRmContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ListAvailable
List all available contexts in the current session.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: ListAllContexts
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
The name of the context

```yaml
Type: System.String
Parameter Sets: GetSingleContext
Aliases:
Accepted values: Microsoft Azure Internal Consumption (07a45d58-11b5-4fd3-8cb6-12ac232d1c3f) - stephen.tramer@microsoft.com, Visual Studio Enterprise (ba04b8a1-d48f-4bc8-a53e-aa05cb7a7d06) - stephen.tramer@microsoft.com, Email Platform Prod(Converted to EA) (0db7356d-b487-4ce3-9768-e57afe0763c6) - stephen.tramer@microsoft.com, Visual Studio Enterprise (0b186e08-ea4c-4dcf-a82e-da80567adc1c) - stephen.tramer@microsoft.com, Cosmos_WDG_Core_BnB_100348 (dae41bd3-9db4-4b9b-943e-832b57cac828) - stephen.tramer@microsoft.com, SETO_SCId4384303_Glass_Dev_Corpnet (b171ea33-bd59-444a-a6d6-94e31f5bef1f) - stephen.tramer@microsoft.com, Microsoft Azure Internal Consumption (07a45d58-11b5-4fd3-8cb6-12ac232d1c3f) - sttramer@microsoft.com, Microsoft Azure Internal Consumption (3a114192-82f9-4b59-a788-3cb958275193) - stephen.tramer@microsoft.com, PMFB (24a7e655-6046-40ef-9a31-8f8a40208620) - stephen.tramer@microsoft.com, Core-ES-BLD (54e18c35-3863-4a17-8e52-b5aa1e65847e) - stephen.tramer@microsoft.com, Azure SDK Infrastructure (6b085460-5f21-477e-ba44-1035046e9101) - stephen.tramer@microsoft.com, CodeMine-Prod (dc4948fc-fa86-4bee-9410-c0891a1f62b0) - stephen.tramer@microsoft.com

Required: False
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### Microsoft.Azure.Commands.Profile.Models.PSAzureContext

## NOTES

## RELATED LINKS