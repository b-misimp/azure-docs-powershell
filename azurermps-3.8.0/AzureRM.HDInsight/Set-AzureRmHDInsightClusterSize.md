---
external help file: Microsoft.Azure.Commands.HDInsight.dll-Help.xml
ms.assetid: A9A8C4B9-6346-4186-9D73-3A56437BFB2F
online version:
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/preview/src/ResourceManager/HDInsight/Commands.HDInsight/help/Set-AzureRmHDInsightClusterSize.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/preview/src/ResourceManager/HDInsight/Commands.HDInsight/help/Set-AzureRmHDInsightClusterSize.md
gitcommit: https://github.com/Azure/azure-powershell/blob/94e42834e29c78cafba9e3f1e99e14af92561036
---

# Set-AzureRmHDInsightClusterSize

## SYNOPSIS
Sets the number of Worker nodes in a specified cluster.

## SYNTAX

```
Set-AzureRmHDInsightClusterSize [-ClusterName] <String> [-TargetInstanceCount] <Int32>
 [-ResourceGroupName <String>] [-InformationAction <ActionPreference>] [-InformationVariable <String>]
 [<CommonParameters>]
```

## DESCRIPTION
The **Set-AzureRmHDInsightClusterSize** cmdlet sets the number of Worker nodes in a specified Azure HDInsight cluster.

## EXAMPLES

### Example 1: Set the size of a specified cluster
```
PS C:\>Set-AzureRmHDInsightClusterSize -ClusterName "your-hadoop-001" -TargetInstanceCount 6
```

This command sets the size of the cluster named your-hadoop-001.

## PARAMETERS

### -ClusterName
Specifies the name of the cluster.

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

### -TargetInstanceCount
Specifies the desired number of Worker nodes in the cluster.

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationAction
Specifies how this cmdlet responds to an information event.

The acceptable values for this parameter are:

- Continue
- Ignore
- Inquire
- SilentlyContinue
- Stop
- Suspend

```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
Specifies an information variable.

```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

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

