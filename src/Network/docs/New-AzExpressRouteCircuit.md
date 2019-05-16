---
external help file: Az.Network-help.xml
Module Name: Az.Network
online version: https://docs.microsoft.com/en-us/powershell/module/az.network/new-azexpressroutecircuit
schema: 2.0.0
---

# New-AzExpressRouteCircuit

## SYNOPSIS
Creates or updates an express route circuit.

## SYNTAX

### CreateSubscriptionIdViaHost (Default)
```
New-AzExpressRouteCircuit -CircuitName <String> -ResourceGroupName <String> [-Parameter <IExpressRouteCircuit>]
 [-DefaultProfile <PSObject>] [-AsJob] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### CreateExpanded
```
New-AzExpressRouteCircuit -CircuitName <String> -ResourceGroupName <String> -SubscriptionId <String>
 [-AllowClassicOperation <Boolean>] [-Authorization <IExpressRouteCircuitAuthorization[]>]
 [-BandwidthInGbp <Single>] [-CircuitProvisioningState <String>] [-ExpressRoutePortId <String>]
 [-GatewayManagerEtag <String>] [-GlobalReachEnabled <Boolean>] [-Id <String>] [-Location <String>]
 [-Peering <IExpressRouteCircuitPeering[]>] [-ProvisioningState <String>] [-ServiceKey <String>]
 [-ServiceProviderNote <String>] [-ServiceProviderPropertiesBandwidthInMbp <Int32>]
 [-ServiceProviderPropertiesPeeringLocation <String>] [-ServiceProviderPropertiesServiceProviderName <String>]
 [-ServiceProviderProvisioningState <ServiceProviderProvisioningState>]
 [-SkuFamily <ExpressRouteCircuitSkuFamily>] [-SkuName <String>] [-SkuTier <ExpressRouteCircuitSkuTier>]
 [-Tag <IResourceTags>] [-DefaultProfile <PSObject>] [-AsJob] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-AzExpressRouteCircuit -CircuitName <String> -ResourceGroupName <String> -SubscriptionId <String>
 [-Parameter <IExpressRouteCircuit>] [-DefaultProfile <PSObject>] [-AsJob] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### CreateSubscriptionIdViaHostExpanded
```
New-AzExpressRouteCircuit -CircuitName <String> -ResourceGroupName <String> [-AllowClassicOperation <Boolean>]
 [-Authorization <IExpressRouteCircuitAuthorization[]>] [-BandwidthInGbp <Single>]
 [-CircuitProvisioningState <String>] [-ExpressRoutePortId <String>] [-GatewayManagerEtag <String>]
 [-GlobalReachEnabled <Boolean>] [-Id <String>] [-Location <String>] [-Peering <IExpressRouteCircuitPeering[]>]
 [-ProvisioningState <String>] [-ServiceKey <String>] [-ServiceProviderNote <String>]
 [-ServiceProviderPropertiesBandwidthInMbp <Int32>] [-ServiceProviderPropertiesPeeringLocation <String>]
 [-ServiceProviderPropertiesServiceProviderName <String>]
 [-ServiceProviderProvisioningState <ServiceProviderProvisioningState>]
 [-SkuFamily <ExpressRouteCircuitSkuFamily>] [-SkuName <String>] [-SkuTier <ExpressRouteCircuitSkuTier>]
 [-Tag <IResourceTags>] [-DefaultProfile <PSObject>] [-AsJob] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Creates or updates an express route circuit.

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AllowClassicOperation
Allow classic operations

```yaml
Type: System.Boolean
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -AsJob
Run the command as a job

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Authorization
The list of authorizations.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IExpressRouteCircuitAuthorization[]
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BandwidthInGbp
The bandwidth of the circuit when the circuit is provisioned on an ExpressRoutePort resource.

```yaml
Type: System.Single
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### -CircuitName
The name of the circuit.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CircuitProvisioningState
The CircuitProvisioningState state of the resource.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DefaultProfile
The credentials, account, tenant, and subscription used for communication with Azure.

```yaml
Type: System.Management.Automation.PSObject
Parameter Sets: (All)
Aliases: AzureRMContext, AzureCredential

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExpressRoutePortId
Resource ID.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GatewayManagerEtag
The GatewayManager Etag.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GlobalReachEnabled
Flag denoting Global reach status.

```yaml
Type: System.Boolean
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Resource ID.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Location
Resource location.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Parameter
ExpressRouteCircuit resource

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IExpressRouteCircuit
Parameter Sets: CreateSubscriptionIdViaHost, Create
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Peering
The list of peerings.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IExpressRouteCircuitPeering[]
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProvisioningState
Gets the provisioning state of the public IP resource.
Possible values are: 'Updating', 'Deleting', and 'Failed'.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroupName
The name of the resource group.

```yaml
Type: System.String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ServiceKey
The ServiceKey.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ServiceProviderNote
The ServiceProviderNotes.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ServiceProviderPropertiesBandwidthInMbp
The BandwidthInMbps.

```yaml
Type: System.Int32
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### -ServiceProviderPropertiesPeeringLocation
The peering location.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ServiceProviderPropertiesServiceProviderName
The serviceProviderName.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ServiceProviderProvisioningState
The ServiceProviderProvisioningState state of the resource.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Support.ServiceProviderProvisioningState
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SkuFamily
The family of the SKU.
Possible values are: 'UnlimitedData' and 'MeteredData'.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Support.ExpressRouteCircuitSkuFamily
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SkuName
The name of the SKU.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SkuTier
The tier of the SKU.
Possible values are 'Standard', 'Premium' or 'Local'.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Support.ExpressRouteCircuitSkuTier
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SubscriptionId
The subscription credentials which uniquely identify the Microsoft Azure subscription.
The subscription ID forms part of the URI for every service call.

```yaml
Type: System.String
Parameter Sets: CreateExpanded, Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Tag
Resource tags.

```yaml
Type: Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IResourceTags
Parameter Sets: CreateExpanded, CreateSubscriptionIdViaHostExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: System.Management.Automation.SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Azure.PowerShell.Cmdlets.Network.Models.Api20190201.IExpressRouteCircuit
## NOTES

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/az.network/new-azexpressroutecircuit](https://docs.microsoft.com/en-us/powershell/module/az.network/new-azexpressroutecircuit)
