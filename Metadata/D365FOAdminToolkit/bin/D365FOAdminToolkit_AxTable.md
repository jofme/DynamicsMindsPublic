
   ADMSysAdminLog�g5      ADMTmpBatchJobMerge�g5  F  ADMUserDisableLog�g5X  4  ADMEntraIdGroupUserLastSync�g5�  �  
ADMConfigs�g5;  �  )ADMEntraIdGroupSecurityRoleAssignmentRule�g5�  �  ADMParameters�g5�  �  $ADMEntraIdGroupDynamicRoleAssignment�g5�    ADMExcludedUsers�g5�  }  ADMEntraIDGroupUserMembership�g5$  N  � �	 
 0public class ADMSysAdminLog extends common
{
}   �
AutoReport��
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse�   �$@D365FOAdminToolkit:AssignmentReasonReason�   ��ADMSysAdminAction@D365FOAdminToolkit:ActionAction��UserId_2   ��EndDateTime EndDateTime��NoYes	NoYesId 
@SYS107504
HasExpired  �   �    �CreatedDateTime�	DateTime��    �EndDateTime��
HasExpired�	EndDateTimeExpiredIdx�   � 
insert�  � �!ADMSysAdminLog(  9  ��� �BatchMergeIdx5public class ADMTmpBatchJobMerge extends common
{
}*@D365FOAdminToolkit:TmpBatchJobMergeDevDoc   �   �Caption��
BatchGroup��CanMerge�
AutoReport��   �Caption��
BatchGroup��CanMerge�
AutoLookup�� AutoIdentification��   �Caption��
BatchGroup��CanMerge�AutoSummary��   �Caption��
BatchGroup��CanMerge�
AutoBrowse��   �Caption��
BatchGroup��CanMerge�	@SYS26263Grid�   �    Customer Content	BatchCaption
@SYS114518 Caption��    	BatchGroupId  
BatchGroup��    RefRecId  BatchJobRecId��NoYes	NoYesId-@D365FOAdminToolkit:BatchJobMergeCanMergeHelp .@D365FOAdminToolkit:BatchJobMergeCanMergeLabelCanMerge�   �    �BatchJobRecId�	BatchMergeIdx�!@D365FOAdminToolkit:BatchJobMerge   � 	
createFromBatchJob   � _tmpBatchJobMerge ADMTmpBatchJobMerge�� 	_batchJob BatchJob��  � �� 
initFromBatchJob   � 	_batchJob batchJob��  � �� 
setCanMerge�  ��� 
insert�  � �!ADMTmpBatchJobMerge9  �0 1 3Caption4
BatchGroup�� �A 
 3public class ADMUserDisableLog extends common
{
}   �
AutoReport��
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse�   �UserId_2   ��Reason�   �   �    �CreatedDateTime�	DateTime�%@D365FOAdminToolkit:UserDisableReport!ADMUserDisableLog(  9  ��� �	UserIdIdx=public class ADMEntraIdGroupUserLastSync extends common
{
}8@D365FOAdminToolkit:ADMUserEntraIdGroupLastSyncDeveloper   �   �User��LastSyncDateTime�
AutoReport��   �User��LastSyncDateTime�
AutoLookup��    �User�AutoIdentification��AutoSummary��
AutoBrowse��   �LastSyncDateTime��User�@SYS6047	AllFields�   �Customer ContentADMSysUserLastSyncTimeUTC LastSyncDateTime��  Customer Content 	UserId User�   �    �User�		UserIdIdx�/@D365FOAdminToolkit:ADMUserEntraIdGroupLastSync   � 	
syncRequired   � curUserId()_userId UserId��  boolean� �� 	
setLastSync   � curUserId()_userId UserId��  � �;SystemAdministration!ADMEntraIdGroupUserLastSync$	UserIdIdx%   �    �UserUseridUserId�Id	UserInfoUserInfo UserInfo ADMUserEntraIdGroupLastSync  �&	UserIdIdx(  0 3User4LastSyncDateTime�� �A  NameIdx,public class ADMConfigs extends common
{
}   �
AutoReport��
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse�   �Name2   ��Value�����   �    �Name�	NameIdx�&@D365FOAdminToolkit:ConfigurationSetup   � 	
getConfigValue   � 	_configId  ��   � �� 	
setConfigValue   � 	_configId  �� _value  ��  � �!
ADMConfigs(  9  �0 �� �A  Mpublic class ADMEntraIdGroupSecurityRoleAssignmentRule extends common
{
}
F@D365FOAdminToolkit:ADMEntraIdGroupSecurityRoleAssignmentRuleDeveloper   �   �SecurityRoleAssignmentRule��UserInfo��SecurityRole��OMUserRoleOrganization�
AutoReport��
AutoLookup��    �SecurityRole��UserInfo��OMUserRoleOrganization�AutoIdentification��AutoSummary��
AutoBrowse�   �System MetadataRefRecIdSecurityRoleAssignmentRule��RefRecId UserInfo��System MetadataRefRecIdSecurityRole��System MetadataRefRecIdOMUserRoleOrganization�   �    �SecurityRole��UserInfo��OMUserRoleOrganization�		UniqueIdx��    �UserInfo�	UserInfoIdx��    �SecurityRoleAssignmentRule�	SecurityRoleAssignmentRuleIdx��    �OMUserRoleOrganization�	OMUserRoleOrganizationIdx�5@D365FOAdminToolkit:EntraIdGroupDynamicRoleAssignment;SystemAdministration!)ADMEntraIdGroupSecurityRoleAssignmentRule%   �    �SecurityRoleAssignmentRuleSecurityRoleAssignmentRuleRecId�RecIDIdx	SecurityRoleAssignmentRuleSecurityRoleAssignmentRule  ��    �UserInfoUserInfoRecId�RecId	UserInfoUserInfo  ��    �SecurityRoleSecurityRoleRecId�RecIDIdx	SecurityRoleSecurityRole    ��    �OMUserRoleOrganizationOMUserRoleOrganizationRecId�RecIDIdx	OMUserRoleOrganizationOMUserRoleOrganization  �&	UniqueIdx(  9  �0 3UserInfo4SecurityRole�� �A  Key/public class ADMParameters extends common
{
}*@D365FOAdminToolkit:ADMParametersDeveloper   �   �AutomaticRoleAssignment��SynchronousUserEntraIDGroupSync��SyncPattern��SyncFrequency�
AutoReport��
AutoLookup��    �Key�AutoIdentification��AutoSummary��
AutoBrowse�   �    Customer ContentParametersKeyKey  ��NoYes+@D365FOAdminToolkit:AutomaticRoleAssignmentAutomaticRoleAssignment��NoYes.@D365FOAdminToolkit:SynchronousSynchronizationSynchronousUserEntraIDGroupSync��ADMSecondMinuteHourDay+@D365FOAdminToolkit:EntraIdGroupSyncPatternSyncPattern��ADMEntraIdGroupSyncFrequency SyncFrequency�ADMParameters   �    �Key�	Key�@D365FOAdminToolkit:Parameters   � 
delete�  � �� 
update�  � �� 	
find   � false
_forupdate boolean��  ADMParameters� �� 
SyncFrequencySeconds�  Seconds� �� 
	initValue�  � �  ;SystemAdministration!ADMParameters$Key&Key(  / 0 �� �A  Hpublic class ADMEntraIdGroupDynamicRoleAssignment extends common
{

}A@D365FOAdminToolkit:ADMEntraIdGroupDynamicRoleAssignmentDeveloper   �   �AutomaticRoleAssignment��UserInfo�
AutoReport��
AutoLookup��    �UserInfo�AutoIdentification��AutoSummary��
AutoBrowse�   �NoYes+@D365FOAdminToolkit:AutomaticRoleAssignmentAutomaticRoleAssignment��RefRecId UserInfo�SysGroupManagementPage   �    �UserInfo�	UserInfoIdx�5@D365FOAdminToolkit:EntraIdGroupDynamicRoleAssignment   � 
delete�  � �� 
update�  � �;SystemAdministration!$ADMEntraIdGroupDynamicRoleAssignment%   �    �UserInfoUserInfoRecId�RecId	UserInfoUserInfo  �&UserInfoIdx(  9  �0 3UserInfo4AutomaticRoleAssignment�� �A 2public class ADMExcludedUsers extends common
{
}   �
AutoReport��
AutoLookup�� AutoIdentification��AutoSummary��
AutoBrowse�   �UserId2   ��UserNamed   �   � 	
addSelectedUsers   � 	_userInfo UserInfo��  � �� 	
addDefaultUsers�  � �� 
initFromUserInfo   � 	_userInfo UserInfo��  � �!ADMExcludedUsers(  9  ��� �A   Apublic class ADMEntraIDGroupUserMembership extends common
{
}
:@D365FOAdminToolkit:ADMEntraIDGroupUserMembershipDeveloper   �   �User��EntraIdGroup�
AutoReport��
AutoLookup��    �EntraIdGroup��User�AutoIdentification��AutoSummary��
AutoBrowse�   �Customer Content	UserId@D365FOAdminToolkit:GroupIdEntraIdGroup��Customer Content	UserIdUser�   �    �EntraIdGroup��User�	GroupUserIdx��    �User��EntraIdGroup�	UserGroupIdx�'@D365FOAdminToolkit:ADMUserEntraIdGroup;SystemAdministration!ADMEntraIDGroupUserMembership%   �    �EntraIdGroupEntraIdGroup1id��accountTypeaccountType   �Id	UserInfoGroupUserInfo    ��    �UserUserid�Id	UserInfoUserUserInfo    �&GroupUserIdx(  9  �0 3User4EntraIdGroup�