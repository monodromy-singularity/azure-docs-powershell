---
external help file: Microsoft.Azure.Commands.Websites.dll-Help.xml
ms.assetid: BBC85035-DCF7-44FA-A747-A1563A55B820
online version: 
schema: 2.0.0
---

# Get-AzureRmWebAppBackupList

## SYNOPSIS
Gets a list of backups for an Azure Web App.

## SYNTAX

### FromResourceName
```
Get-AzureRmWebAppBackupList [-ResourceGroupName] <String> [-Name] <String> [[-Slot] <String>]
 [<CommonParameters>]
```

### FromWebApp
```
Get-AzureRmWebAppBackupList [-WebApp] <Site> [<CommonParameters>]
```

## DESCRIPTION
The **Get-AzureRmWebAppBackupList** cmdlet gets a list of backups for an Azure Web App.

## EXAMPLES

### Example 1:
```
PS C:\> Get-AzureRmWebAppBackupList -ResourceGroupName "Default-Web-WestUS" -Name "WebAppStandard"
```

This command returns a backup list pertaining to WebApp WebAppStandard associated with the resource group ContosoResourceGroup.

## PARAMETERS

### -ResourceGroupName
Specifies the name of the resource group.

```yaml
Type: String
Parameter Sets: FromResourceName
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Specifies the name of the Web App.

```yaml
Type: String
Parameter Sets: FromResourceName
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Slot
Specifies the name of the WebApp slot.

```yaml
Type: String
Parameter Sets: FromResourceName
Aliases: 

Required: False
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -WebApp
Specifies the piped WebApp.

```yaml
Type: Site
Parameter Sets: FromWebApp
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS