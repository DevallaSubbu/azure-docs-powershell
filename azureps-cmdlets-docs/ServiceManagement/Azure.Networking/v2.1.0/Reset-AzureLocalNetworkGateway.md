---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.Network.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 5D5676EB-47EB-448A-A33A-BF9721AC8AE3
---

# Reset-AzureLocalNetworkGateway

## SYNOPSIS
Resets a local network gateway.

## SYNTAX

```
Reset-AzureLocalNetworkGateway [-GatewayId] <String>
 [-AddressSpace] <System.Collections.Generic.List`1[System.String]> [[-Asn] <UInt32>]
 [[-BgpPeeringAddress] <String>] [[-PeerWeight] <Int32>] [-Profile <AzureSMProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **Reset-AzureLocalNetworkGateway** cmdlet resets a local network gateway.

## EXAMPLES



## PARAMETERS

### -AddressSpace
Specifies the address space.

```yaml
Type: System.Collections.Generic.List`1[System.String]
Parameter Sets: (All)
Aliases:

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Asn
Specifies the autonomous system number (ASN).

```yaml
Type: UInt32
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BgpPeeringAddress
Specifies the Border Gateway Protocol (BGP) peering address.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GatewayId
Specifies the ID of the gateway.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 0
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -PeerWeight
```yaml
Type: Int32
Parameter Sets: (All)
Aliases:

Required: False
Position: 4
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Profile
Specifies the Azure profile from which this cmdlet reads.
If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureSMProfile
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Get-AzureLocalNetworkGateway](./Get-AzureLocalNetworkGateway.md)

[New-AzureLocalNetworkGateway](./New-AzureLocalNetworkGateway.md)

[Remove-AzureLocalNetworkGateway](./Remove-AzureLocalNetworkGateway.md)
