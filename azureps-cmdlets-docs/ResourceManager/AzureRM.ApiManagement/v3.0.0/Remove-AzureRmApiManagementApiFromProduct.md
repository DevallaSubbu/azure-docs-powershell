---
external help file: Microsoft.Azure.Commands.ApiManagement.ServiceManagement.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 8CEB3E1E-5E5B-46C3-A598-5B97CD6E8802
---

# Remove-AzureRmApiManagementApiFromProduct

## SYNOPSIS
Removes an API from a product.

## SYNTAX

```
Remove-AzureRmApiManagementApiFromProduct -Context <PsApiManagementContext> -ProductId <String> -ApiId <String>
 [-PassThru] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmApiManagementApiFromProduct** cmdlet removes an Azure API Management API from a product.

## EXAMPLES

### Example 1: Remove an API from a product
```
PS C:\> Remove-AzureRmApiManagementApiFromProduct -Context $ApiMgmtContext -ProductId "0123456789" -ApiId "0001" -PassThru
```

This commnd removes the specified API from a product.

## PARAMETERS

### -Context
Specifies a **PsApiManagementContext**.

```yaml
Type: PsApiManagementContext
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ProductId
Specifies the ID of the product from which to remove the API.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ApiId
Specifies the ID of the API to remove from the product.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -PassThru
Indicates that this cmdlet returns a value of $True if it succeeds, or $False, otherwise.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### bool

## NOTES

## RELATED LINKS

[Add-AzureRmApiManagementApiToProduct](./Add-AzureRmApiManagementApiToProduct.md)
