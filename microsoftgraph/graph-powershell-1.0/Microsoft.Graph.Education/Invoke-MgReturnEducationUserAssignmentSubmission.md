---
external help file: Microsoft.Graph.Education-help.xml
Module Name: Microsoft.Graph.Education
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.education/invoke-mgreturneducationuserassignmentsubmission
schema: 2.0.0
ms.prod: education
---

# Invoke-MgReturnEducationUserAssignmentSubmission

## SYNOPSIS
Make the grade and feedback associated with this submission available to the student.
This action changes the status of the submission from 'submitted' to 'returned' and indicates that feedback is provided or grading is done.
This action can only be done by the teacher.
This API is available in the following national cloud deployments.

> [!NOTE]
> To view the beta release of this cmdlet, view [Invoke-MgBetaReturnEducationUserAssignmentSubmission](/powershell/module/Microsoft.Graph.Beta.Education/Invoke-MgBetaReturnEducationUserAssignmentSubmission?view=graph-powershell-beta)

## SYNTAX

### Return (Default)
```
Invoke-MgReturnEducationUserAssignmentSubmission -EducationAssignmentId <String>
 -EducationSubmissionId <String> -EducationUserId <String> [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ReturnViaIdentity
```
Invoke-MgReturnEducationUserAssignmentSubmission -InputObject <IEducationIdentity> [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Make the grade and feedback associated with this submission available to the student.
This action changes the status of the submission from 'submitted' to 'returned' and indicates that feedback is provided or grading is done.
This action can only be done by the teacher.
This API is available in the following national cloud deployments.

## EXAMPLES

## PARAMETERS

### -EducationAssignmentId
The unique identifier of educationAssignment

```yaml
Type: String
Parameter Sets: Return
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EducationSubmissionId
The unique identifier of educationSubmission

```yaml
Type: String
Parameter Sets: Return
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EducationUserId
The unique identifier of educationUser

```yaml
Type: String
Parameter Sets: Return
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IEducationIdentity
Parameter Sets: ReturnViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
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
Type: SwitchParameter
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

### Microsoft.Graph.PowerShell.Models.IEducationIdentity
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphEducationSubmission
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

INPUTOBJECT \<IEducationIdentity\>: Identity Parameter
  \[EducationAssignmentId \<String\>\]: The unique identifier of educationAssignment
  \[EducationAssignmentResourceId \<String\>\]: The unique identifier of educationAssignmentResource
  \[EducationCategoryId \<String\>\]: The unique identifier of educationCategory
  \[EducationClassId \<String\>\]: The unique identifier of educationClass
  \[EducationOutcomeId \<String\>\]: The unique identifier of educationOutcome
  \[EducationRubricId \<String\>\]: The unique identifier of educationRubric
  \[EducationSchoolId \<String\>\]: The unique identifier of educationSchool
  \[EducationSubmissionId \<String\>\]: The unique identifier of educationSubmission
  \[EducationSubmissionResourceId \<String\>\]: The unique identifier of educationSubmissionResource
  \[EducationUserId \<String\>\]: The unique identifier of educationUser

## RELATED LINKS
[Invoke-MgBetaReturnEducationUserAssignmentSubmission](/powershell/module/Microsoft.Graph.Beta.Education/Invoke-MgBetaReturnEducationUserAssignmentSubmission?view=graph-powershell-beta)

[https://learn.microsoft.com/powershell/module/microsoft.graph.education/invoke-mgreturneducationuserassignmentsubmission](https://learn.microsoft.com/powershell/module/microsoft.graph.education/invoke-mgreturneducationuserassignmentsubmission)


