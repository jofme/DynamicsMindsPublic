   ADMConfiguration�g5    �  ADMSysAdminReport�g5�  �  ADMParameters�g5}  6	  ADMSysAdminReason�g5�  w  ADMSysAdminAssignment�g5*  7  ADMExcludedUsers�g5a  E  ADMDisableUserReport�g5�"  �  ADMDisableUserJob�g5U'  �  ADMPartUsersForEntraIdGroup�g52)  O  ADMBatchJobMergeDialog�g5�1  e  ADMPartEntraIdGroupsForUser�g5�5  �  � � � 
 �&@D365FOAdminToolkit:ConfigurationSetup   � 
 �     �     �) �2(@D365FOAdminToolkit:DefaultNumDaysReport8 �GReportNumDaysY   ��   � �!$@D365FOAdminToolkit:ShowReasonDialog' �2ShowReasonDialog��   � �!0@D365FOAdminToolkit:ShowSysAdminExpiryDateDialog' �2ShowAdminExpiryDate�, <FormGroupControl1@FieldsFieldGroupsA1.1F S ��  
 �   �   �" �.   � 
clicked�  � �0Cancel@@D365FOAdminToolkit:Cancel��   �" �.   � 
clicked�  � �0Save@@D365FOAdminToolkit:Submit�5FormButtonGroupControl1@ L �0Dialog11.2: �   " config 
ADMConfigs�
   � 
classDeclaration� ��� 
init�  � �ADMConfiguration�� �    � 
   � Action�� 	CreatedBy�� CreatedDateTime�� EndDateTime�� 
HasExpired�� 	Partition�� Reason�� RecId�� TableId�� UserId_�   � 
init�  � �� 
executeQuery�  � �ADMSysAdminLogADMSysAdminLog�� 
 �(@D365FOAdminToolkit:SysAdminAssignReport   � )FormActionPaneControl1��  
 �   � �    � targetControlName AdmSysAdminLogGrid�� placeholderText �� defaultColumnName �QuickFilterControl�QuickFilterControl1��   �, �5@D365FOAdminToolkit:StartDate; �KStartDateControl��   �, �5@D365FOAdminToolkit:EndDate; �KEndDateControl�* <FormGroupControl1@CustomAndQuickFiltersA1.1F P S ��  � �  	  �   �  �CreatedDateTimeADMSysAdminLog( �0@D365FOAdminToolkit:DateTime6 �FADMSysAdminLog_CreatedDateTime��  �UserId_ADMSysAdminLog' �0@D365FOAdminToolkit:User6 �GADMSysAdminLog_UserId_��  �ReasonADMSysAdminLog' �0@D365FOAdminToolkit:Reason6 �GADMSysAdminLog_Reason��  �ActionADMSysAdminLog% �/@D365FOAdminToolkit:Action5 �@ADMSysAdminLog_Action��  �	CreatedByADMSysAdminLog' �0@D365FOAdminToolkit:ModifiedBy6 �GADMSysAdminLog_CreatedBy��  �EndDateTimeADMSysAdminLog( �6 �FADMSysAdminLog_EndDateTime�ADMSysAdminLog2  3AdmSysAdminLogGrid�0ListPage1UX7 1.07  8  : H �   " qbr_date QueryBuildRange�" ds QueryBuildDataSource�" qry Query�" qryRun QueryRun�
   � 
classDeclaration� ��� 
init�  � �ADMSysAdminReport�� �    �     
   � AutomaticRoleAssignment�� Key�� 
ModifiedBy�� ModifiedDateTime�� 	Partition�� RecId�� SyncFrequency�� SynchronousUserEntraIDGroupSync   � 
modified�  � ��� SyncPattern�� TableId�         � 
showHideFields�  � �� 
active�   � �ADMParametersADMParameters�� 
 �@D365FOAdminToolkit:Parameters   � 
 �   � 
 �@D365FOAdminToolkit:General   �   
 �   �  �! �,FormStaticTextControl11 2 4@D365FOAdminToolkit:Parameters= �* <GeneralTitleE F
 S ��  
 �   � 
 �@D365FOAdminToolkit:General     � 
 �   �     �) �2(@D365FOAdminToolkit:DefaultNumDaysReport8 �GReportNumDaysY   �<ReportNumDaysGroup�� 
 �   �   � �!$@D365FOAdminToolkit:ShowReasonDialog' �2ShowReasonDialog�<ShowReasonDialogGroup�� 
 �   �   �) �2&@D365FOAdminToolkit:DisableUserNumDays8 �GDisableUserNumDaysYZ   �<DisableUserNumDaysGroup�� 
 �@PDS1938   �   � �!0@D365FOAdminToolkit:ShowSysAdminExpiryDateDialog' �1   � 
modified�  boolean� �2ShowAdminExpiryDate��   �) �22@D365FOAdminToolkit:SysAdminExpiryDateDefaultHours8 �GAdminExpiryDateDefaultHours�<ShowAdminExpiryDateGroup�� 
 �!@MonitoringAndTelemetry:Telemetry   �   � �0@D365FOAdminToolkit:SendTelemetrySysAdminLogHelp!1@D365FOAdminToolkit:SendTelemetrySysAdminLogLabel' �2SendTelemetrySysAdminLog�<SendTelemetryGroup�0
GeneralTab5FieldsFieldGroups61.1�0GeneralFastTab< �0General�� 
 � @D365FOAdminToolkit:EntraIdGroup   �   
 �   �  �! �,StaticTextEntraIdGroupSetup1 2 4.@D365FOAdminToolkit:SetUpInfoEntraIdSecGrpSync= �* <EntraIdGroupTitleE F
 S ��  
 �   � 
 �/@D365FOAdminToolkit:EntraIdGroupSynchronization     �  �AutomaticRoleAssignmentADMParameters �' �2%ADMParameters_AutomaticRoleAssignment��  �SynchronousUserEntraIDGroupSyncADMParameters �' �2-ADMParameters_SynchronousUserEntraIDGroupSync��  �SyncPatternADMParameters% �5 �@ADMParameters_SyncPattern��  �SyncFrequencyADMParameters) �8 �GADMParameters_SyncFrequency�0EntraIdGroupsTabPage5FieldsFieldGroups61.1�0EntraIdGroupFastTab< �ADMParameters0TabEntraIdGroup�0ADMTab< �0TableOfContents11.1:
 �   " config 
ADMConfigs�
   � 
classDeclaration� ��� 
init�  � �� 
close�  � �ADMParameters�� � � 
 �%@D365FOAdminToolkit:ASTSysAdminChange   � 
 �     �   �' �0 @D365FOAdminToolkit:ChangeReason6 �F GstrSysAdminReason] ��   �EndDateTime( �6 �FDateTimeSysAdminExpiry�, <FormGroupControl1@FieldsFieldGroupsA1.1F S ��  
 �   �   �" �.   � 
clicked�  � �0	btnSubmit@@D365FOAdminToolkit:Submit��  �" �0FormButtonControl2I  �5FormButtonGroupControl1@ L �0Dialog11.2: �   " showExpiryDate NoYesId	  �" requireReason NoYesId	  �" defaultExpiryHours  	  �" sal ADMSysAdminLog	 �
   � 
classDeclaration� ��� 
init�  � �ADMSysAdminReason�� � � 
 �%@D365FOAdminToolkit:AddRevokeSysAdmin   � 
 �   �   �" �.   � 
clicked�  � �0btnAssignSysAdmin@"@D365FOAdminToolkit:AssingSysAdmin��   �" �.   � 
clicked�  � �0btnRevokeSysAdmin@"@D365FOAdminToolkit:RevokeSysAdmin��   �" �.   � 
clicked�  � �0	btnCancel@@D365FOAdminToolkit:Cancel�, <FormGroupControl1F S ��  
 �   �  �" �0FormButtonControl1I  ��  �" �0FormButtonControl2I  �5FormButtonGroupControl1@ L �0Dialog11.2: �
   � 
classDeclaration� ��� 
init�  � �ADMSysAdminAssignment�� �    �        � 	Partition�� RecId�� TableId�� UserId�     � 
init�  � �� 
executeQuery�  � �� 
delete�  � �ADMExcludedUsersADMExcludedUsers��       I   � accountType�� autoInfo�� 
autoLogOff�� 
autoUpdate�� clientAccessLogLevel�� company�� compilerWarningLevel�� confirmDelete�� confirmUpdate�� credentialRecId�� debuggerPopup�� 	debugInfo�� defaultPartition�� DEL__unused1�� DEL__unused2�� DEL_defaultModelId�� DEL_osAccountName�� DEL_password�� DEL_startupMenu�� enable�� enabledOnce�� 
externalId�� externalIdType�� externalUser�� filterByGridOnByDefault�� formFontName�� formFontSize�� garbagecollectlimit�� generalInfo�� globalExcelExportFilePath�� globalExcelExportMode�� globalFormOpenMode�� globalListPageLinkMode�� helplanguage�� historyLimit�� homePageRefreshDuration�� id�� IdentityProvider�� infologLevel�� InteractiveLogon�� isMicrosoftAccount�� issuerRecId�� language�� messageLimit�� name�� networkAlias�� networkDomain�� notifyTimeZoneMismatch�� ObjectId�� 	Partition�� preferredCalendar�� PreferredLocale�� preferredTimeZone�� propertyFontName�� propertyFontSize�� querytimeLimit�� RecId�� reportBottomMargin�� reportFontName�� reportFontSize�� reportLeftMargin�� reportRightMargin�� reportTopMargin�� showAOTLayer�� showModelNameInAOT�� showStatusLine�� showToolbar�� sid�� startupProject�� statuslineInfo�� TableId�� toolbarInfo�� 	traceInfo�       � 
init�  � �� 
executeQuery�  � �UserInfoUserInfo�� 
 �!@D365FOAdminToolkit:ExcludedUsers   �    � 
 �   �  �" �.   � 
clicked�  � �0PopulateExcludedUsersBtn@)@D365FOAdminToolkit:PopulateExcludedUsers�5
FormBtnGrp�)ActionPaneCtrl�� 
 �   � 
 �
@SYS122526   �    �    � 
 �   �  �" �.   � 
clicked�  � �/ 0
BtnAddUser3 @
@SYS121192�5UserGridActionPaneBtbGrp�,UserGridActionPaneTab�UserInfo)UserGridActionPane3 ��  � �  	  �   �  �idUserInfo' �0@D365FOAdminToolkit:UserId6 �GUserId��  �nameUserInfo' �0@D365FOAdminToolkit:UserName6 �GUserName�UserInfo3UserGrid�0HeaderTablPage5ToolbarList61.2�0	HeaderTab�� 
 �<SplitterGroupF �� 
 �   � 
 �!@D365FOAdminToolkit:ExcludedUsers   �    �    � 
 �   �  �" �/ 0FormCommandButtonControl13 �ADMExcludedUsers5ExcludedUserGridActionBtnGrp�,ExcludedUserGridActionPaneTab�ADMExcludedUsers)ExcludedUserGridActionPane3 ��  � �	  �   �  �UserIdADMExcludedUsers' �0@D365FOAdminToolkit:UserId6 �GExcludedUserId��  �UserNameADMExcludedUsers' �0@D365FOAdminToolkit:UserName6 �GExcludedUserName�ADMExcludedUsers3ExcludedUsersGrid�ADMExcludedUsers0DetailsTabPage5ToolbarList61.2�0
DetailsTab�0TaskParentChild11.27  8  C �   " qry_adm Query�" 
qryRun_adm QueryRun�" ds_adm QueryBuildDataSource�" qry_user Query�" qryRun_user QueryRun�" ds_user QueryBuildDataSource�" qbr_user QueryBuildRange�
   � 
classDeclaration� ��ADMExcludedUsers�� �    �    � 
DataAreaId�� 	Partition�� Reason�� RecId�� TableId�� UserId_�   � 
init�  � �� 
executeQuery�  � �ADMUserDisableLogADMUserDisableLog�� 
 �%@D365FOAdminToolkit:UserDisableReport   � )FormActionPaneControl1��  
 �   � �    � targetControlName �� placeholderText �� defaultColumnName �QuickFilterControl�QuickFilterControl1��   �, �5@D365FOAdminToolkit:StartDate; �KStartDateControl��   �, �5@D365FOAdminToolkit:EndDate; �KEndDateControl�* <FormGroupControl1@CustomAndQuickFiltersA1.1F P S ��  � �   �   �  �CreatedDateTimeADMUserDisableLog( �0@D365FOAdminToolkit:DateTime6 �F'ADMDisableUserReportLog_CreatedDateTime��  �UserId_ADMUserDisableLog' �0@D365FOAdminToolkit:User6 �GADMDisableUserReportLog_User��  �ReasonADMUserDisableLog' �0@D365FOAdminToolkit:Reason6 �GADMDisableUserReportLog_Reason�3AdmDisableUserReportGrid�0ListPage1UX7 1.07  8  : C �   " qbr_date QueryBuildRange�" ds QueryBuildDataSource�" qry Query�" qryRun QueryRun�" config 
ADMConfigs�
   � 
classDeclaration� ��� 
init�  � �ADMDisableUserReport�� � � 
 �"@D365FOAdminToolkit:DisableUserJob   � 
 �   �     �) �2$@D365FOAdminToolkit:NumDaysLastLogin8 �GNumDaysLastLogin�, <FormGroupControl1F S ��  
 �   �  �" �.   � 
clicked�  � �0Submit@@D365FOAdminToolkit:Submit��  �" �.   � 
clicked�  � �0Cancel@@D365FOAdminToolkit:Cancel�5FormButtonGroupControl1@ L �0Dialog11.2: �   " config 
ADMConfigs�
   � 
classDeclaration� ��� 
init�  � �ADMDisableUserJob�� �    �    � EntraIdGroup�� name�� 	Partition�� RecId�� TableId�� User�       � 
init�  � �� 
executeQuery�  � �EntraIdGroupUserViewADMEntraIdGroupUserView��       E   � accountType�� autoInfo�� 
autoLogOff�� 
autoUpdate�� clientAccessLogLevel�� company�� compilerWarningLevel�� confirmDelete�� confirmUpdate�� credentialRecId�� 
DataAreaId�� debuggerPopup�� 	debugInfo�� defaultPartition�� DEL_defaultModelId�� DEL_osAccountName�� DEL_password�� DEL_startupMenu�� DEL__unused1�� DEL__unused2�� enable�� enabledOnce�� 
externalId�� externalIdType�� externalUser�� filterByGridOnByDefault�� formFontName�� formFontSize�� garbagecollectlimit�� generalInfo�� globalExcelExportFilePath�� globalExcelExportMode�� globalFormOpenMode�� globalListPageLinkMode�� helplanguage�� historyLimit�� homePageRefreshDuration�� id�� infologLevel�� issuerRecId�� language�� messageLimit�� name�� networkAlias�� networkDomain�� notifyTimeZoneMismatch�� 	Partition�� preferredCalendar�� preferredTimeZone�� propertyFontName�� propertyFontSize�� querytimeLimit�� RecId�� reportBottomMargin�� reportFontName�� reportFontSize�� reportLeftMargin�� reportRightMargin�� reportTopMargin�� showAOTLayer�� showModelNameInAOT�� showStatusLine�� showToolbar�� sid�� startupProject�� statuslineInfo�� TableId�� toolbarInfo�� 	traceInfo�  SelectedUserUserInfo��  
 �(@D365FOAdminToolkit:UsersForEntraIdGroup   �  � �    	  �   �    �UserEntraIdGroupUserView    ���?"%1' �*  6 �Gusers[����`  ��  �UserNameEntraIdGroupUserView    ���_"%1' �*  6 �Gnames[����`  �EntraIdGroupUserViewTUUU!%1*  2  3usersForEntraIdGroups;  = C����H   I �EntraIdGroupUserView   0FormPartFactboxGrid11.15  6  9 : C E    F �   " selectedUserId userId�" 	rangeUser QueryBuildRange�
   � 
classDeclaration� ��� 
init�  � �� 
run�  � �� 
updateSelection   � _userId userId��  � �ADMPartUsersForEntraIdGroup�� �    �    � 
BatchGroup�� BatchJobRecId�� CanMerge�� Caption�� 
DataAreaId�� 	Partition�� RecId�� TableId�ADMTmpBatchJobMergeADMTmpBatchJobMerge�� 
 �!@D365FOAdminToolkit:BatchJobMerge   � 
 �     �   �) �-0@D365FOAdminToolkit:MergeBatchJobDestinationHelp21@D365FOAdminToolkit:MergeBatchJobDestinationLabel8 �E F   � 
lookup�  � �� 
validate�  boolean� �� 
jumpRef�  � �GDestBatchJobCtrl�<ContentHeader@FieldsFieldGroupsA1.1F S �� 
 �2@D365FOAdminToolkit:MergeBatchJobSelectedBatchJobs   �  � � �   �  �CaptionADMTmpBatchJobMerge' �6 �GBatchMergeGrid_Caption��  �
BatchGroupADMTmpBatchJobMerge' �6 �GBatchMergeGrid_BatchGroup��  �CanMergeADMTmpBatchJobMerge �' �2BatchMergeGrid_CanMerge�GridADMTmpBatchJobMerge3BatchMergeGrid�, <Content@ToolbarListA1.2F S ��  
 �   �  �" �0OKCmdBtn��  �" �0CancelCmdBtn;  �5CommitContainer@ L � 0Dialog11.2: �   " admBatchJobMerge ADMBatchJobMerge�
   � 
classDeclaration� ��� 
init�  � �� 
closeOk�  � �ADMBatchJobMergeDialog�� �    �    � EntraIdGroup�� name�� 	Partition�� RecId�� TableId�� User�       � 
init�  � �� 
executeQuery�  � �EntraIdGroupUserViewADMEntraIdGroupUserView��       E   � accountType�� autoInfo�� 
autoLogOff�� 
autoUpdate�� clientAccessLogLevel�� company�� compilerWarningLevel�� confirmDelete�� confirmUpdate�� credentialRecId�� 
DataAreaId�� debuggerPopup�� 	debugInfo�� defaultPartition�� DEL_defaultModelId�� DEL_osAccountName�� DEL_password�� DEL_startupMenu�� DEL__unused1�� DEL__unused2�� enable�� enabledOnce�� 
externalId�� externalIdType�� externalUser�� filterByGridOnByDefault�� formFontName�� formFontSize�� garbagecollectlimit�� generalInfo�� globalExcelExportFilePath�� globalExcelExportMode�� globalFormOpenMode�� globalListPageLinkMode�� helplanguage�� historyLimit�� homePageRefreshDuration�� id�� infologLevel�� issuerRecId�� language�� messageLimit�� name�� networkAlias�� networkDomain�� notifyTimeZoneMismatch�� 	Partition�� preferredCalendar�� preferredTimeZone�� propertyFontName�� propertyFontSize�� querytimeLimit�� RecId�� reportBottomMargin�� reportFontName�� reportFontSize�� reportLeftMargin�� reportRightMargin�� reportTopMargin�� showAOTLayer�� showModelNameInAOT�� showStatusLine�� showToolbar�� sid�� startupProject�� statuslineInfo�� TableId�� toolbarInfo�� 	traceInfo�  SelectedUserUserInfo��  
 �(@D365FOAdminToolkit:EntraIdGroupsForUser   �  � �    	  �   �     �EntraIdGroupEntraIdGroupUserView���?"%1' �0 @SysSecLabels:GroupManagement_ID6 �E   � 
jumpRef�  � �Ggroups[����_   ��     �	GroupNameEntraIdGroupUserView���?"%1' �0Name6 �Gnames[����_   �EntraIdGroupUserViewTUUU!%1*  2  3entraIdGroupsForUser;  = C����H   I �EntraIdGroupUserView   0FormPartFactboxGrid11.15  6  9 : C E    F �   " selectedUserId userId�" 	rangeUser QueryBuildRange�
   � 
classDeclaration� ��� 
init�  � �� 
run�  � �� 
updateSelection   � _userId userId��  � �ADMPartEntraIdGroupsForUser�