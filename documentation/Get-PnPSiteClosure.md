---
Module Name: PnP.PowerShell
title: Get-PnPSiteClosure
schema: 2.0.0
applicable: SharePoint Online
external help file: PnP.PowerShell.dll-Help.xml
online version: https://pnp.github.io/powershell/cmdlets/Get-PnPSiteClosure.html
---
 
# Get-PnPSiteClosure

## SYNOPSIS
Get the site closure status of the site which has a site policy applied

## SYNTAX

```powershell
Get-PnPSiteClosure [-Connection <PnPConnection>] [<CommonParameters>]
```

## DESCRIPTION

Allows to retrieve current site closure status of the site which has a site policy applied.

## EXAMPLES

### EXAMPLE 1
```powershell
Get-PnPSiteClosure
```

Get the site closure status of the site.

## PARAMETERS

### -Connection
Optional connection to be used by the cmdlet. Retrieve the value for this parameter by either specifying -ReturnConnection on Connect-PnPOnline or by executing Get-PnPConnection.

```yaml
Type: PnPConnection
Parameter Sets: (All)

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```



## RELATED LINKS

[Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp)

