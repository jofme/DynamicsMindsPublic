!   ADMSysSecRoleAssignOM_Extension�g5    �   ADMConstants�g5�   �   ADMSysAdminReport_EventHandlers�g5�  u  (ADMRemoveUserAdminRoleEndDateTimeService�g5_    0ADMApplicationInsightsSysAdminToDateTimeProperty�g5s  S  ADMExportEnvConfig�g5�    ADMConfigsConstants�g5�    ADMSysQueryRunView�g5�  �   ADMBatchJobMerge�g5�  �  8ADMSysSecRolesEditUsers_AssignmentRulesButtons_Extension�g5}  j  DATMain�g5�  �   /ADMSysActiveDirectoryGroupImport_Form_Extension�g5|  3  <ADMSysSecRolesEditUsers_SecurityRoleAssignmentRule_Extension�g5�  |  ,ADMApplicationInsightsSysAdminUserIdProperty�g5+  Q  ADMSysAdminLogHelper�g5|  �  ADMUserInfo_EventHandlers�g5s  �  'ADMOMUserRoleOrganization_EventHandlers�g5  �  ADMExportRoleAccess�g5   �   ,ADMApplicationInsightsSysAdminReasonProperty�g5�   G  !ADMSecurityUserRole_EventHandlers�g5�!  �  ADMTableEvents�g5�%  �  ADMSysQueryForm_Extension�g5L(  �   %ADMSysSecRolesEditUsers_EventHandlers�g5()  8  ADMEntraIdGroupHelper�g5`,  �  "ADMEntraIDGroupUserSynchronization�g5�0    ADMDisableUserLastLogin�g5�6  �   2ADMApplicationInsightsSysAdminFromDateTimeProperty�g5�7  Y  ADMRevokeAdminRoleBatchJob�g5�8  v  ADMApplicationInsightsConstants�g5i:  9  $ADMDisabledUsersReport_EventHandlers�g5�>  �  ADMApplicationInsightsEventIds�g5'A  �  ADMDisableUserLastLoginBatchJob�g5�B  �  ADMEntraIdGroupUserImport�g5�E    � !     ExtensionOf        SysSecRoleAssignOM� � � formStr��f[ExtensionOf(formStr(SysSecRoleAssignOM))]
internal final class ADMSysSecRoleAssignOM_Extension
{
}   � 
init�  � �ADMSysSecRoleAssignOM_Extension�� ! �/// <summary>
/// The <c>ADMConstants</c> class holds constants for the D365 admin toolkit module.
/// </summary>
internal static class ADMConstants
{
    internal const str ext = '#EXT';
}   " ext  	 �ADMConstants�� ! :internal final class ADMSysAdminReport_EventHandlers
{
}   �     FormControlEventHandler        ADMSysAdminReport� StartDateControl� � formControlStr�     Modified�	 FormControlEventType��	
StartDateControl_OnModified   � sender FormControl�� e FormControlEventArgs��  � ��     FormControlEventHandler        ADMSysAdminReport� EndDateControl� � formControlStr�     Modified�	 FormControlEventType��	
EndDateControl_OnModified   � sender FormControl�� e FormControlEventArgs��  � �ADMSysAdminReport_EventHandlers�� ! �internal final class ADMRemoveUserAdminRoleEndDateTimeService
{
    private static str systemAdministratorRoleName = '-SYSADMIN-';

}   " systemAdministratorRoleName  	  �   � 
doDisableAdminRoles�  � �(ADMRemoveUserAdminRoleEndDateTimeService�� ! rinternal final class ADMApplicationInsightsSysAdminToDateTimeProperty extends SysApplicationInsightsProperty
{
}SysApplicationInsightsProperty   � 	
newFromValue   � _value  ��  0ADMApplicationInsightsSysAdminToDateTimeProperty� �� 

initialize�   � �0ADMApplicationInsightsSysAdminToDateTimeProperty�� ! �using Microsoft.Dynamics.AX.Security.Management;
using Microsoft.Dynamics.AX.Security.Management.Domain;
using Microsoft.Dynamics.AX.Security.Management.Interfaces;
using Microsoft.Dynamics.AX.Security.Management.Querying;
using Microsoft.Dynamics.AX.Security.Management.UI;
using D365FOAdminToolkitNET;
using D365FOAdminToolkitNET.Models;
using System.Collections;
using System.Collections.Generic;

public class ADMExportEnvConfig
{
}   � 	
main   � _args Args��  � �ADMExportEnvConfig�� ! �internal final class ADMConfigsConstants
{    
    public static str configNameDefaultNumDays              = 'DefaultNumDaysForReports';
    public static str configNameShowReasonDialog            = 'ShowReasonDialog';
    public static str configNameDisableUserNumDays          = 'DisableUserNumDays';
    public static str configNameShowExpiryDateDialog        = 'ShowRoleExpiryDateDialog';
    public static str configNameRoleDefaultExpiryHours      = 'DefaultNumHoursRoleExpiry';
    public static str configNameTelemetrySysAdminRole       = 'TelemetrySysAdminRole';

    public static int defaultValueReportOffset              = 30;
    public static int defaultValueReasonDialog              = NoYes::No;
    public static int defaultValueExipryDialog              = NoYes::No;
    public static int defaultValueDisableUser               = 90;
    public static int defaultValueRoleExpiryHours           = 8;
    public static int defaultValueTelemetrySysAdminRole     = NoYes::No;
}   " configNameDefaultNumDays  	 �" configNameShowReasonDialog  	 �" configNameDisableUserNumDays  	 �" configNameShowExpiryDateDialog  	 �"  configNameRoleDefaultExpiryHours  	 �" configNameTelemetrySysAdminRole  	 �" defaultValueReportOffset  	 �" defaultValueReasonDialog  	 �" defaultValueExipryDialog  	 �" defaultValueDisableUser  	 �" defaultValueRoleExpiryHours  	 �" !defaultValueTelemetrySysAdminRole  	 �ADMConfigsConstants�� ! m/// <summary>
/// Query run view only.
/// </summary>
class ADMSysQueryRunView extends SysQueryRun
{

}SysQueryRun   � 
new   � null_p1	  ��  � �� 	
	construct�  ADMSysQueryRunView� �ADMSysQueryRunView�� ! �/// <summary>
/// Merge one or more batch jobs into an existing one
/// </summary>
internal final class ADMBatchJobMerge
{
    public  ADMTmpBatchJobMerge tmpBatchJobMerge;
    public  RefRecId            mergeToBatchJob;
    private Map                 taskMapping;
    private RecordInsertList    recordInsertListConstraint;

}   " tmpBatchJobMerge ADMTmpBatchJobMerge	 �" mergeToBatchJob RefRecId	 �" taskMapping Map	  �" recordInsertListConstraint RecordInsertList	  �	   � 
initFromArgs   � _args Args��  � �� 
prompt�  boolean� �� 
validateParameters�  boolean� �� 
validateDestBatchJob   � _destBatchId RefRecId��  boolean� �� 
doMergeBatchJobs�  � �� 
	copyTasks   � _origBatchJob RefRecId��  ��� 
new�  � �� 	
	construct�  ADMBatchJobMerge� �� 	
Main   � _args Args��  � �ADMBatchJobMerge�� !     ExtensionOf        SysSecRolesEditUsers� assignmentRulesButtons� � formControlStr���[ExtensionOf(formControlStr(SysSecRolesEditUsers,assignmentRulesButtons))]
final class ADMSysSecRolesEditUsers_AssignmentRulesButtons_Extension
{
}   � 
setEnabledState�  � �8ADMSysSecRolesEditUsers_AssignmentRulesButtons_Extension�� ! Rusing Microsoft.Dynamics.AX.Security.GraphAPIHelper;

public class DATMain
{
}   � 	
main   � _args Args��  � �DATMain�� !     ExtensionOf        SysActiveDirectoryGroupImport� � � formStr��x[ExtensionOf(formStr(SysActiveDirectoryGroupImport))]
final class ADMSysActiveDirectoryGroupImport_Form_Extension
{
}   � 
ImportGroups�  boolean� �/ADMSysActiveDirectoryGroupImport_Form_Extension�� !     ExtensionOf        SysSecRolesEditUsers� securityRoleAssignmentRule� � formDataSourceStr���[ExtensionOf(formDataSourceStr(SysSecRolesEditUsers,securityRoleAssignmentRule))]
final class ADMSysSecRolesEditUsers_SecurityRoleAssignmentRule_Extension
{

}   � 
active�   � �<ADMSysSecRolesEditUsers_SecurityRoleAssignmentRule_Extension�� ! ninternal final class ADMApplicationInsightsSysAdminUserIdProperty extends SysApplicationInsightsProperty
{
}SysApplicationInsightsProperty   � 	
newFromValue   � _value 
WHSMessage��  ,ADMApplicationInsightsSysAdminUserIdProperty� �� 

initialize�   � �,ADMApplicationInsightsSysAdminUserIdProperty�� ! 5public class ADMSysAdminLogHelper
{
            
}   � 	
CheckReasonDialogConfig�   � �� 	
CheckExpiryDateDialog�   � �� 	
CheckTelemetrySysAdminRole�   � �� 	
GetDefaultNumDaysForReports�   � �� 	
GetDefaultNumHoursRoleExpiry�   � �� 	
setUserRoleAssignmentAsExpired   � _userId UserId��  � �� 	
#sendTelemetryAssignedExpiredRevoked   � _id  �� _name  �� _sysAdminLog ADMSysAdminLog��  � �ADMSysAdminLogHelper�� ! �/// <summary>
/// THe <c>ADMUserInfo_EventHandlers</c> class extends data events on the UserInfo table.
/// </summary>
internal final class ADMUserInfo_EventHandlers
{
}   �     DataEventHandler        UserInfo� � � tableStr�     Deleting�	 DataEventType��	
UserInfo_onDeleting   � sender Common�� e DataEventArgs��  � �ADMUserInfo_EventHandlers�� ! �/// <summary>
/// The <c>ADMOMUserRoleOrganization_EventHandlers</c> class contains logic to be executed
/// when date events occurs on the ADMOMUserRoleOrganization table.
/// </summary>
internal final class ADMOMUserRoleOrganization_EventHandlers
{
}   �     DataEventHandler        OMUserRoleOrganization� � � tableStr�     Inserted�	 DataEventType��	
!OMUserRoleOrganization_onInserted   � sender Common�� e DataEventArgs��  � ��     DataEventHandler        OMUserRoleOrganization� � � tableStr�     Deleting�	 DataEventType��	
!OMUserRoleOrganization_onDeleting   � sender Common�� e DataEventArgs��  � �'ADMOMUserRoleOrganization_EventHandlers�� ! Fusing D365FOAdminToolkitNET;

public class ADMExportRoleAccess
{
}   � 	
main   � _args Args��  � �ADMExportRoleAccess�� ! ninternal final class ADMApplicationInsightsSysAdminReasonProperty extends SysApplicationInsightsProperty
{
}SysApplicationInsightsProperty   � 	
newFromValue   � _value  ��  ,ADMApplicationInsightsSysAdminReasonProperty� �� 

initialize�   � �,ADMApplicationInsightsSysAdminReasonProperty�� ! �/// <summary>
/// The <c>ADMSecurityUserRole_EventHandlers</c> class contains logic to be executed
/// when date events occurs on the ADMSecurityUserRole table.
/// </summary>
internal final class ADMSecurityUserRole_EventHandlers
{
}   �     DataEventHandler        SecurityUserRole� � � tableStr�     Inserted�	 DataEventType��	
SecurityUserRole_onInserted   � sender Common�� e DataEventArgs��  � ��     DataEventHandler        SecurityUserRole� � � tableStr�     Updating�	 DataEventType��	
SecurityUserRole_onUpdating   � sender Common�� e DataEventArgs��  � ��     DataEventHandler        SecurityUserRole� � � tableStr�     Deleting�	 DataEventType��	
SecurityUserRole_onDeleting   � sender Common�� e DataEventArgs��  � �!ADMSecurityUserRole_EventHandlers�� ! )internal final class ADMTableEvents
{
}   �     DataEventHandler        SecurityUserRole� � � tableStr�     Inserted�	 DataEventType��	
SecurityUserRole_onInserted   � sender Common�� e DataEventArgs��  � ��     DataEventHandler        SecurityUserRole� � � tableStr�     Updating�	 DataEventType��	
SecurityUserRole_onUpdating   � sender Common�� e DataEventArgs��  � ��     DataEventHandler        SecurityUserRole� � � tableStr�     Deleted�	 DataEventType��	
SecurityUserRole_onDeleted   � sender Common�� e DataEventArgs��  � �ADMTableEvents�� !     ExtensionOf        SysQueryForm� � � formStr��Z[ExtensionOf(formStr(SysQueryForm))]
internal final class ADMSysQueryForm_Extension
{
}   � 
init�  � �ADMSysQueryForm_Extension�� ! �/// <summary>
/// The <c>ADMSysSecRolesEditUsers_EventHandlers</c> class contains event
/// handlers related to the form SysSecRolesEditUsers
/// </summary>
internal final class ADMSysSecRolesEditUsers_EventHandlers
{
}   �     FormControlEventHandler        SysSecRolesEditUsers� ADMViewQueryButton� � formControlStr�     Clicked�	 FormControlEventType��	
ADMViewQueryButton_OnClicked   � sender FormControl�� e FormControlEventArgs��  � ��     FormDataSourceEventHandler        SysSecRolesEditUsers� UserInfo� � formDataSourceStr�     QueryExecuted�	 FormDataSourceEventType��	
userInfo_OnQueryExecuted   � sender FormDataSource�� e FormDataSourceEventArgs��  � �%ADMSysSecRolesEditUsers_EventHandlers�� ! �using Microsoft.Dynamics.AX.Security.DirectoryHelper;
using System.Web;
/// <summary>
/// Class used to manage direct security role assignments based on Entra ID group memberships
/// </summary>

internal final class ADMEntraIdGroupHelper
{
}   � 	
syncEntraIdGroupsforUser   � curUserId()_userId UserId��  � �� 	
getEntraIdGroupsForUserId   � _userId UserId��  SysActiveDirectoryGroupTmp� �� 	
getEntraIdGroupsForUserObjectId   � 	_objectId
  �� ''_userId UserId��  SysActiveDirectoryGroupTmp� �� 	
createRoleAssignmentRule   � _secUserRole SecurityUserRole�� 	_userInfo UserInfo��  � �� 	
deleteRoleAssignmentRule   � _secUserRole SecurityUserRole�� 	_userInfo UserInfo��  � �� 	
$createRoleAssignmentRuleOrganization   � _omUserRoleOrganization OMUserRoleOrganization�� 	_userInfo UserInfo��  � �� 	
$deleteRoleAssignmentRuleOrganization   � _omUserRoleOrganization OMUserRoleOrganization�� 	_userInfo UserInfo��  � �� 	
isEntraIdGroupManaged   � _common Common��  boolean� �ADMEntraIdGroupHelper�� ! �/// <summary>
///    Periodic batch job to sync Entra ID Group membership information
///    and maintain security role assignments.
/// </summary>
/// <remarks>
///    This class adds one or more batch tasks.
/// </remarks>
public class ADMEntraIdGroupUserSynchronization extends RunBaseBatch implements BatchRetryable
{
    UserId userId;

}RunBaseBatch   BatchRetryable   " userId UserId�   � 

canGoBatch�  boolean� �� 
canGoBatchJournal�  boolean� �� 
canRunInNewSession�  boolean� ��     HMicrosoft.Dynamics.BusinessPlatform.SharedTypes.InternalUseOnlyAttribute�
run�  � ��     HMicrosoft.Dynamics.BusinessPlatform.SharedTypes.InternalUseOnlyAttribute�
runsImpersonated�  boolean� ��     HMicrosoft.Dynamics.BusinessPlatform.SharedTypes.InternalUseOnlyAttribute�	
	construct�  "ADMEntraIdGroupUserSynchronization� �� 	
description�  ClassDescription���     HMicrosoft.Dynamics.BusinessPlatform.SharedTypes.InternalUseOnlyAttribute�	
main   � _args Args��  � �� 

parmUserId   � userId_userId UserId��  UserId� �� 	
synchronize   � ''_userId UserId��  � ��     SubscribesTo        ApplicationStartupEventManager� � � classStr�     ApplicationStartupEventManager� onInteractiveSessionCreated� � staticDelegateStr��	
onInteractiveSessionCreated�  � ��     Hookable     False��
isRetryable�  boolean� �"ADMEntraIdGroupUserSynchronization�� ! *public class ADMDisableUserLastLogin
{
}   � 
DisableUsersBasedOnLastLogin   � numDays  ��  boolean� �ADMDisableUserLastLogin�� ! tinternal final class ADMApplicationInsightsSysAdminFromDateTimeProperty extends SysApplicationInsightsProperty
{
}SysApplicationInsightsProperty   � 	
newFromValue   � _value  ��  2ADMApplicationInsightsSysAdminFromDateTimeProperty� �� 

initialize�   � �2ADMApplicationInsightsSysAdminFromDateTimeProperty�� ! Bpublic class ADMRevokeAdminRoleBatchJob extends RunBaseBatch
{
}RunBaseBatch   � 
run�  � �� 

canGoBatch�  boolean� �� 
canGoBatchJournal�  boolean� �� 	
description�  ClassDescription��� 
pack�   � �� 
unpack   � packedClass  ��  boolean� �� 
runsImpersonated�  boolean� �ADMRevokeAdminRoleBatchJob�� ! �internal final class ADMApplicationInsightsConstants
{
    internal static const str ADMSysAdminAssigned   = 'ADMSysAdminAssigned';
    internal static const str ADMSysAdminRevoked    = 'ADMSysAdminRevoked';
    internal static const str ADMSysAdminExpired    = 'ADMSysAdminExpired';


    internal static const container UserId          = ['UserId',        SysApplicationInsightsComplianceDataType::SystemMetadata];
    internal static const container Reason          = ['Reason',        SysApplicationInsightsComplianceDataType::CustomerContent];
    internal static const container FromDateTime    = ['FromDateTime',  SysApplicationInsightsComplianceDataType::SystemMetadata];
    internal static const container ToDateTime      = ['ToDateTime',    SysApplicationInsightsComplianceDataType::SystemMetadata];
}   " ADMSysAdminAssigned  	 �" ADMSysAdminRevoked  	 �" ADMSysAdminExpired  	 �" UserId  	 �" Reason  	 �" FromDateTime  	 �" 
ToDateTime  	 �ADMApplicationInsightsConstants�� ! ?internal final class ADMDisabledUsersReport_EventHandlers
{
}   �     FormControlEventHandler        ADMDisableUserReport� StartDateControl� � formControlStr�     Modified�	 FormControlEventType��	
StartDateControl_OnModified   � sender FormControl�� e FormControlEventArgs��  � ��     FormControlEventHandler        ADMDisableUserReport� EndDateControl� � formControlStr�     Modified�	 FormControlEventType��	
EndDateControl_OnModified   � sender FormControl�� e FormControlEventArgs��  � �$ADMDisabledUsersReport_EventHandlers�� ! �internal final class ADMApplicationInsightsEventIds
{
    internal static const str SysAdminAssigned  = 'ATK000001';
    internal static const str SysAdminRevoked   = 'ATK000002';
    internal static const str SysAdminExpired   = 'ATK000003';
}   " SysAdminAssigned  	 �" SysAdminRevoked  	 �" SysAdminExpired  	 �ADMApplicationInsightsEventIds�� ! �public class ADMDisableUserLastLoginBatchJob extends RunBaseBatch
{
    DialogField dlgLastLogin;
    int daysSinceLastLogin;

    #define.CurrentVersion(1)
    #define.Version(1)
    #localmacro.CurrentList
        daysSinceLastLogin
    #endmacro

    ADMConfigs config;

}RunBaseBatch   " dlgLastLogin DialogField�" daysSinceLastLogin  �" config 
ADMConfigs�   � 
run�  � �� 
dialog�  Object� �� 
getFromDialog�  boolean� �� 
pack�   � �� 
unpack   � packedClass  ��  boolean� �� 	
description�  ClassDescription��� 
runsImpersonated�  boolean� �� 
canGoBatchJournal�  boolean� �ADMDisableUserLastLoginBatchJob�� ! �public class ADMEntraIdGroupUserImport extends RunBaseBatch implements BatchRetryable
{
    SysUserMSODSUserTmp tmp;
    
    UserId              groupId;

    
}RunBaseBatch   BatchRetryable   " tmp SysUserMSODSUserTmp�" groupId UserId�   � 

canGoBatch�  boolean� �� 
canGoBatchJournal�  boolean� �� 
canRunInNewSession�  boolean� ��     HMicrosoft.Dynamics.BusinessPlatform.SharedTypes.InternalUseOnlyAttribute�
run�  � �� 
fillTmpUserList�  ��� 

createUser   � _userToImport SysUserMSODSUserTmp�� _groupUserId UserId��  ��� 	

isGraphAPI�  boolean� ��     HMicrosoft.Dynamics.BusinessPlatform.SharedTypes.InternalUseOnlyAttribute�
runsImpersonated�  boolean� ��     HMicrosoft.Dynamics.BusinessPlatform.SharedTypes.InternalUseOnlyAttribute�	
	construct�  ADMEntraIdGroupUserImport� �� 	
description�  ClassDescription���     HMicrosoft.Dynamics.BusinessPlatform.SharedTypes.InternalUseOnlyAttribute�	
main   � _args Args��  � �� 
parmGroupId   � groupId_groupId UserId��  UserId� �� 	
synchronize   � ''_groupId UserId��  � ��     Hookable     False��
isRetryable�  boolean� �ADMEntraIdGroupUserImport�