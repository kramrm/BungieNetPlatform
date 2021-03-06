<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

This listing is based on [platform library](https://www.bungie.net/sharedbundle/platformlib) file used by [Bungie.net](https://www.bungie.net).

## <a name="JSONPService"></a>JSONPService (1 Endpoint)
Method | Name | Endpoint
------ | ---- | --------
GET | [[GetCurrentUser|GetCurrentUser]] | /JSONP/GetBungieNetUser/

## <a name="ApplicationService"></a>ApplicationService (14 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
POST | [[ApplicationSearch|ApplicationSearch]] | /App/Search/
POST | [[ChangeApiKeyStatus|ChangeApiKeyStatus]] | /App/ChangeApiKeyState/{param1}/{param2}/
POST | [[CreateApiKey|CreateApiKey]] | /App/CreateApiKey/{param1}/
POST | [[CreateApplication|CreateApplication]] | /App/CreateApplication/
POST | [[EditApplication|EditApplication]] | /App/EditApplication/{param1}/
POST | [[GetAccessTokensFromCode|GetAccessTokensFromCode]] | /App/GetAccessTokensFromCode/
POST | [[GetAccessTokensFromRefreshToken|GetAccessTokensFromRefreshToken]] | /App/GetAccessTokensFromRefreshToken/
GET | [[GetApplication|GetApplication]] | /App/Application/{param1}/
GET | [[GetApplicationApiKeys|GetApplicationApiKeys]] | /App/ApplicationApiKeys/{param1}/
GET | [[GetAuthorizationForUserAndApplication|GetAuthorizationForUserAndApplication]] | /App/Authorization/{param1}/{param2}/
GET | [[GetAuthorizations|GetAuthorizations]] | /App/Authorizations/{param1}/
POST | [[GetOAuthTokens|GetOAuthTokens]] | /App/oauth/token/
POST | [[PrivateApplicationSearch|PrivateApplicationSearch]] | /App/PrivateSearch/
POST | [[RevokeAuthorization|RevokeAuthorization]] | /App/RevokeAuthorization/{param1}/{param2}/

## <a name="UserService"></a>UserService (35 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
POST | [[CreateUser|CreateUser]] | /User/CreateUser/
POST | [[EditSuccessMessageFlags|EditSuccessMessageFlags]] | /User/MessageFlags/Success/Update/{param1}/
GET | [[GetAvailableAvatars|GetAvailableAvatars]] | /User/GetAvailableAvatars/
GET | [[GetAvailableAvatarsAdmin|GetAvailableAvatarsAdmin]] | /User/GetAvailableAvatarsAdmin/{param1}/
GET | [[GetAvailableThemes|GetAvailableThemes]] | /User/GetAvailableThemes/
GET | [[GetBungieAccount|GetBungieAccount]] | /User/GetBungieAccount/{membershipId}/{membershipType}/
GET | [[GetBungieNetUserById|GetBungieNetUserById]] | /User/GetBungieNetUserById/{membershipId}/
GET | [[GetCountsForCurrentUser|GetCountsForCurrentUser]] | /User/GetCounts/
GET | [[GetCredentialTypesForAccount|GetCredentialTypesForAccount]] | /User/GetCredentialTypesForAccount/
GET | [[GetCurrentBungieAccount|GetCurrentBungieAccount]] | /User/GetCurrentBungieAccount/
GET | [[GetCurrentBungieNetUser|GetCurrentBungieNetUser]] | /User/GetCurrentBungieNetUser/
GET | [[GetCurrentUser (User)|GetCurrentUser-(User)]] | /User/GetBungieNetUser/
GET | [[GetMembershipDataById|GetMembershipDataById]] | /User/GetMembershipsById/{membershipId}/{membershipType}/
GET | [[GetMembershipDataForCurrentUser|GetMembershipDataForCurrentUser]] | /User/GetMembershipsForCurrentUser/
GET | [[GetMobileAppPairings|GetMobileAppPairings]] | /User/GetMobileAppPairings/
GET | [[GetMobileAppPairingsUncached|GetMobileAppPairingsUncached]] | /User/GetMobileAppPairingsUncached/
GET | [[GetNotificationSettings|GetNotificationSettings]] | /User/GetNotificationSettings/
GET | [[GetPartnerships|GetPartnerships]] | /User/{membershipId}/Partnerships/
GET | [[GetPlatformApiKeysForUser|GetPlatformApiKeysForUser]] | /User/GetPlatformApiKeysForUser/
GET | [[GetSignOutUrl|GetSignOutUrl]] | /User/GetSignOutUrl/
GET | [[GetUserAliases|GetUserAliases]] | /User/GetUserAliases/{membershipId}/
GET | [[GetUserMembershipIds|GetUserMembershipIds]] | /User/GetMembershipIds/
POST | [[LinkOverride|LinkOverride]] | /User/LinkOverride/
POST | [[RegisterMobileAppPair|RegisterMobileAppPair]] | /User/RegisterMobileAppPair/
POST | [[RemovePartnership|RemovePartnership]] | /User/Partnerships/{param1}/Remove/
GET | [[SearchUsers|SearchUsers]] | /User/SearchUsers/
GET | [[SearchUsersPaged|SearchUsersPaged]] | /User/SearchUsersPaged/{searchTerm}/{page}/
GET | [[SearchUsersPagedV2|SearchUsersPagedV2]] | /User/SearchUsersPaged/{searchTerm}/{page}/{param3}/
POST | [[SetAcknowledged|SetAcknowledged]] | /User/Acknowledged/{ackId}/
POST | [[UnregisterMobileAppPair|UnregisterMobileAppPair]] | /User/UnregisterMobileAppPair/{param1}/
POST | [[UpdateDestinyEmblemAvatar|UpdateDestinyEmblemAvatar]] | /User/UpdateDestinyEmblemAvatar/
POST | [[UpdateNotificationSetting|UpdateNotificationSetting]] | /User/Notification/Update/
POST | [[UpdateStateInfoForMobileAppPair|UpdateStateInfoForMobileAppPair]] | /User/UpdateStateInfoForMobileAppPair/
POST | [[UpdateUser|UpdateUser]] | /User/UpdateUser/
POST | [[UpdateUserAdmin|UpdateUserAdmin]] | /User/UpdateUserAdmin/{param1}/

## <a name="MessageService"></a>MessageService (32 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
POST | [[CreateConversation|CreateConversation]] | /Message/CreateConversation/
POST | [[CreateConversationV2|CreateConversationV2]] | /Message/CreateConversationV2/
GET | [[GetAllianceInvitedToJoinInvitations|GetAllianceInvitedToJoinInvitations]] | /Message/AllianceInvitations/InvitationsToJoinAnotherGroup/{param1}/{param2}/
GET | [[GetAllianceJoinInvitations|GetAllianceJoinInvitations]] | /Message/AllianceInvitations/RequestsToJoinYourGroup/{param1}/{param2}/
GET | [[GetConversationById|GetConversationById]] | /Message/GetConversationById/{conversationId}/
GET | [[GetConversationByIdV2|GetConversationByIdV2]] | /Message/GetConversationByIdV2/{param1}/
GET | [[GetConversationsV2|GetConversationsV2]] | /Message/GetConversationsV2/{param1}/{param2}/
GET | [[GetConversationsV3|GetConversationsV3]] | /Message/GetConversationsV3/{param1}/{param2}/
GET | [[GetConversationsV4|GetConversationsV4]] | /Message/GetConversationsV4/{param1}/
GET | [[GetConversationsV5|GetConversationsV5]] | /Message/GetConversationsV5/{currentPage}/
GET | [[GetConversationThreadV2|GetConversationThreadV2]] | /Message/GetConversationThreadV2/{param1}/{param2}/{param3}/
GET | [[GetConversationThreadV3|GetConversationThreadV3]] | /Message/GetConversationThreadV3/{param1}/{param2}/
GET | [[GetConversationWithMemberId|GetConversationWithMemberId]] | /Message/GetConversationWithMember/{memberId}/
GET | [[GetConversationWithMemberIdV2|GetConversationWithMemberIdV2]] | /Message/GetConversationWithMemberV2/{param1}/
GET | [[GetGroupConversations|GetGroupConversations]] | /Message/GetGroupConversations/{param1}/
GET | [[GetInvitationDetails|GetInvitationDetails]] | /Message/Invitations/{param1}/Details/
GET | [[GetTotalConversationCount|GetTotalConversationCount]] | /Message/GetTotalConversationCount/
GET | [[GetUnreadConversationCountV2|GetUnreadConversationCountV2]] | /Message/GetUnreadPrivateConversationCount/
GET | [[GetUnreadConversationCountV3|GetUnreadConversationCountV3]] | /Message/GetUnreadConversationCountV3/
GET | [[GetUnreadConversationCountV4|GetUnreadConversationCountV4]] | /Message/GetUnreadConversationCountV4/
GET | [[GetUnreadGroupConversationCount|GetUnreadGroupConversationCount]] | /Message/GetUnreadGroupConversationCount/
GET | [[LeaveConversation|LeaveConversation]] | /Message/LeaveConversation/{param1}/
POST | [[ModerateGroupWall|ModerateGroupWall]] | /Message/ModerateGroupWall/{param1}/{param2}/
POST | [[ReviewAllInvitations|ReviewAllInvitations]] | /Message/Invitations/ReviewAllDirect/{param1}/{param2}/
POST | [[ReviewInvitation|ReviewInvitation]] | /Message/Invitations/{param1}/{param2}/{param3}/
POST | [[ReviewInvitationDirect|ReviewInvitationDirect]] | /Message/Invitations/ReviewDirect/{invitationId}/{invitationResponseState}/
POST | [[ReviewInvitations|ReviewInvitations]] | /Message/Invitations/ReviewListDirect/{param1}/
POST | [[SaveMessageV2|SaveMessageV2]] | /Message/SaveMessageV2/
POST | [[SaveMessageV3|SaveMessageV3]] | /Message/SaveMessageV3/
POST | [[SaveMessageV4|SaveMessageV4]] | /Message/SaveMessageV4/
POST | [[UpdateConversationLastViewedTimestamp|UpdateConversationLastViewedTimestamp]] | /Message/Conversations/UpdateLastViewedTimestamp/
POST | [[UserIsTyping|UserIsTyping]] | /Message/UserIsTyping/

## <a name="NotificationService"></a>NotificationService (4 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
GET | [[GetRealTimeEvents|GetRealTimeEvents]] | /Notification/Events/{param1}/{param2}/
GET | [[GetRecentNotificationCount|GetRecentNotificationCount]] | /Notification/GetCount/
GET | [[GetRecentNotifications|GetRecentNotifications]] | /Notification/GetRecent/
GET | [[ResetNotification|ResetNotification]] | /Notification/Reset/

## <a name="ContentService"></a>ContentService (18 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
GET | [[GetCareer|GetCareer]] | /Content/Careers/{param1}/
GET | [[GetCareers|GetCareers]] | /Content/Careers/
GET | [[GetContentById|GetContentById]] | /Content/GetContentById/{param1}/{param2}/
GET | [[GetContentByTagAndType|GetContentByTagAndType]] | /Content/GetContentByTagAndType/{param1}/{param2}/{param3}/
GET | [[GetContentType|GetContentType]] | /Content/GetContentType/{param1}/
GET | [[GetDestinyContent|GetDestinyContent]] | /Content/Site/Destiny/{param1}/
GET | [[GetDestinyContentV2|GetDestinyContentV2]] | /Content/Site/Destiny/V2/{param1}/
GET | [[GetFeaturedArticle|GetFeaturedArticle]] | /Content/Site/Featured/
GET | [[GetHomepageContent|GetHomepageContent]] | /Content/Site/Homepage/{param1}/
GET | [[GetHomepageContentV2|GetHomepageContentV2]] | /Content/Site/Homepage/V2/
GET | [[GetJobs|GetJobs]] | /Content/Site/Jobs/{param1}/
GET | [[GetNews|GetNews]] | /Content/Site/News/{param1}/{param2}/
GET | [[GetPromoWidget|GetPromoWidget]] | /Content/Site/Destiny/Promo/
GET | [[GetPublications|GetPublications]] | /Content/Site/Publications/{param1}/
GET | [[SearchCareers|SearchCareers]] | /Content/Careers/Search/
GET | [[SearchContentByTagAndType|SearchContentByTagAndType]] | /Content/SearchContentByTagAndType/{param1}/{param2}/{param3}/
POST | [[SearchContentEx|SearchContentEx]] | /Content/SearchEx/{param1}/
GET | [[SearchContentWithText|SearchContentWithText]] | /Content/Search/{param1}/

## <a name="ExternalSocialService"></a>ExternalSocialService (1 Endpoint)
Method | Name | Endpoint
------ | ---- | --------
GET | [[GetAggregatedSocialFeed|GetAggregatedSocialFeed]] | /ExternalSocial/GetAggregatedSocialFeed/{param1}/

## <a name="SurveyService"></a>SurveyService (1 Endpoint)
Method | Name | Endpoint
------ | ---- | --------
GET | [[GetSurvey|GetSurvey]] | /Survey/GetSurvey/

## <a name="ForumService"></a>ForumService (29 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
POST | [[ApproveFireteamThread|ApproveFireteamThread]] | /Forum/Recruit/Approve/{param1}/
POST | [[ChangeLockState|ChangeLockState]] | /Forum/ChangeLockState/{param1}/{param2}/
POST | [[ChangePinState|ChangePinState]] | /Forum/ChangePinState/{param1}/{param2}/
POST | [[CreateContentComment|CreateContentComment]] | /Forum/CreateContentComment/
POST | [[CreatePost|CreatePost]] | /Forum/CreatePost/
POST | [[DeletePost|DeletePost]] | /Forum/DeletePost/{param1}/
POST | [[EditPost|EditPost]] | /Forum/EditPost/{param1}/
GET | [[GetCoreTopicsPaged|GetCoreTopicsPaged]] | /Forum/GetCoreTopicsPaged/{param1}/{param2}/{param3}/{param4}/
GET | [[GetForumTagCountEstimate|GetForumTagCountEstimate]] | /Forum/GetForumTagCountEstimate/{param1}/
GET | [[GetForumTagSuggestions|GetForumTagSuggestions]] | /Forum/GetForumTagSuggestions/
GET | [[GetPoll|GetPoll]] | /Forum/Poll/{param1}/
GET | [[GetPopularTags|GetPopularTags]] | /Forum/GetPopularTags/
GET | [[GetPostAndParent|GetPostAndParent]] | /Forum/GetPostAndParent/{childPostId}/
GET | [[GetPostAndParentAwaitingApproval|GetPostAndParentAwaitingApproval]] | /Forum/GetPostAndParentAwaitingApproval/{childPostId}/
GET | [[GetPostsThreadedPaged|GetPostsThreadedPaged]] | /Forum/GetPostsThreadedPaged/{parentPostId}/{page}/{pageSize}/{replySize}/{getParentPost}/{rootThreadMode}/{sortMode}/
GET | [[GetPostsThreadedPagedFromChild|GetPostsThreadedPagedFromChild]] | /Forum/GetPostsThreadedPagedFromChild/{childPostId}/{page}/{pageSize}/{replySize}/{rootThreadMode}/{sortMode}/
POST | [[GetRecruitmentThreadSummaries|GetRecruitmentThreadSummaries]] | /Forum/Recruit/Summaries/
GET | [[GetTopicForContent|GetTopicForContent]] | /Forum/GetTopicForContent/{contentId}/
GET | [[GetTopicsPaged|GetTopicsPaged]] | /Forum/GetTopicsPaged/{page}/{pageSize}/{group}/{sort}/{quickDate}/{categoryFilter}/
POST | [[JoinFireteamThread|JoinFireteamThread]] | /Forum/Recruit/Join/{param1}/
POST | [[KickBanFireteamApplicant|KickBanFireteamApplicant]] | /Forum/Recruit/KickBan/{param1}/{param2}/
POST | [[LeaveFireteamThread|LeaveFireteamThread]] | /Forum/Recruit/Leave/{param1}/
POST | [[MarkReplyAsAnswer|MarkReplyAsAnswer]] | /Forum/MarkReplyAsAnswer/{param1}/{param2}/
POST | [[ModerateGroupPost|ModerateGroupPost]] | /Forum/Post/{param1}/GroupModerate/
POST | [[ModeratePost|ModeratePost]] | /Forum/Post/{param1}/Moderate/
POST | [[ModerateTag|ModerateTag]] | /Forum/Tags/{param1}/Moderate/
POST | [[PollVote|PollVote]] | /Forum/Poll/Vote/{param1}/{param2}/
POST | [[RatePost|RatePost]] | /Forum/RatePost/{param1}/{param2}/
POST | [[UnmarkReplyAsAnswer|UnmarkReplyAsAnswer]] | /Forum/UnmarkReplyAsAnswer/{param1}/

## <a name="ActivityService"></a>ActivityService (24 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
POST | [[FollowTag|FollowTag]] | /Activity/Tag/Follow/
POST | [[FollowUser|FollowUser]] | /Activity/User/{param1}/Follow/
GET | [[GetApplicationActivityForUser|GetApplicationActivityForUser]] | /Activity/User/{param1}/Activities/Application/{param2}/
GET | [[GetEntitiesFollowedByCurrentUser|GetEntitiesFollowedByCurrentUser]] | /Activity/Following/
GET | [[GetEntitiesFollowedByCurrentUserV2|GetEntitiesFollowedByCurrentUserV2]] | /Activity/Following/V2/{param1}/{param2}/
GET | [[GetEntitiesFollowedByUser|GetEntitiesFollowedByUser]] | /Activity/User/{param1}/Following/
GET | [[GetEntitiesFollowedByUserV2|GetEntitiesFollowedByUserV2]] | /Activity/User/{param1}/Following/V2/{param2}/{param3}/
GET | [[GetFollowersOfTag|GetFollowersOfTag]] | /Activity/Tag/Followers/
GET | [[GetFollowersOfUser|GetFollowersOfUser]] | /Activity/User/{profileId}/Followers/
GET | [[GetForumActivityForUser|GetForumActivityForUser]] | /Activity/User/{param1}/Activities/Forums/
GET | [[GetForumActivityForUserV2|GetForumActivityForUserV2]] | /Activity/User/{param1}/Activities/ForumsV2/
GET | [[GetFriends|GetFriends]] | /Activity/Friends/
GET | [[GetFriendsAllNoPresence|GetFriendsAllNoPresence]] | /Activity/Friends/AllNoPresence/{param1}/
GET | [[GetFriendsPaged|GetFriendsPaged]] | /Activity/Friends/Paged/{membershipType}/{currentPage}/
GET | [[GetGroupsFollowedByCurrentUser|GetGroupsFollowedByCurrentUser]] | /Activity/Following/Groups/
GET | [[GetGroupsFollowedByUser|GetGroupsFollowedByUser]] | /Activity/User/{param1}/Following/Groups/
GET | [[GetGroupsFollowedPagedByCurrentUser|GetGroupsFollowedPagedByCurrentUser]] | /Activity/Following/Groups/{param1}/
GET | [[GetGroupsFollowedPagedByUser|GetGroupsFollowedPagedByUser]] | /Activity/User/{param1}/Following/Groups/Paged/{param2}/
GET | [[GetLikeAndShareActivityForUser|GetLikeAndShareActivityForUser]] | /Activity/User/{param1}/Activities/LikesAndShares/
GET | [[GetLikeAndShareActivityForUserV2|GetLikeAndShareActivityForUserV2]] | /Activity/User/{param1}/Activities/LikesAndSharesV2/
GET | [[GetLikeShareAndForumActivityForUser|GetLikeShareAndForumActivityForUser]] | /Activity/User/{param1}/Activities/LikeShareAndForum/
GET | [[GetUsersFollowedByCurrentUser|GetUsersFollowedByCurrentUser]] | /Activity/Following/Users/
POST | [[UnfollowTag|UnfollowTag]] | /Activity/Tag/Unfollow/
POST | [[UnfollowUser|UnfollowUser]] | /Activity/User/{param1}/Unfollow/

## <a name="GroupService"></a>GroupService (81 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
POST | [[ApproveAllPending|ApproveAllPending]] | /Group/{groupId}/Members/ApproveAll/
POST | [[ApproveGroupMembership|ApproveGroupMembership]] | /Group/{groupId}/Members/{membershipId}/Approve/
POST | [[ApproveGroupMembershipV2|ApproveGroupMembershipV2]] | /Group/{groupId}/Members/{membershipId}/ApproveV2/
POST | [[ApprovePendingForList|ApprovePendingForList]] | /Group/{groupId}/Members/ApproveList/
POST | [[BanMember|BanMember]] | /Group/{groupId}/Members/{membershipId}/Ban/
POST | [[BreakAlliance|BreakAlliance]] | /Group/{groupId}/Relationship/{allyGroupId}/BreakAlliance/
POST | [[BreakAlliances|BreakAlliances]] | /Group/{groupId}/BreakAlliances/
POST | [[CreateGroup|CreateGroup]] | /Group/Create/
POST | [[CreateGroupV2|CreateGroupV2]] | /Group/Create/V2/
POST | [[CreateMinimalGroup|CreateMinimalGroup]] | /Group/Create/Minimal/
POST | [[DenyAllPending|DenyAllPending]] | /Group/{groupId}/Members/DenyAll/
POST | [[DenyGroupMembership|DenyGroupMembership]] | /Group/{groupId}/Members/{membershipId}/Deny/
POST | [[DenyGroupMembershipV2|DenyGroupMembershipV2]] | /Group/{groupId}/Members/{membershipId}/DenyV2/
POST | [[DenyPendingForList|DenyPendingForList]] | /Group/{groupId}/Members/DenyList/
POST | [[DesignateClanFounder|DesignateClanFounder]] | /Group/{param1}/DesignateClanFounder/{param2}/{param3}/
POST | [[DisableClanForGroup|DisableClanForGroup]] | /Group/{groupId}/Clans/Disable/{clanMembershipType}/
POST | [[DisbandAlliance|DisbandAlliance]] | /Group/{groupId}/BreakAllAlliances/
POST | [[EditGroup|EditGroup]] | /Group/{groupId}/Edit/
POST | [[EditGroupMembership|EditGroupMembership]] | /Group/{groupId}/Members/{membershipId}/SetMembershipType/{groupMembershipType}/
POST | [[EditGroupV2|EditGroupV2]] | /Group/{groupId}/EditV2/
POST | [[EnableClanForGroup|EnableClanForGroup]] | /Group/{groupId}/Clans/Enable/{clanMembershipType}/
POST | [[FollowGroupsWithGroup|FollowGroupsWithGroup]] | /Group/{groupId}/FollowList/
POST | [[FollowGroupWithGroup|FollowGroupWithGroup]] | /Group/{groupId}/Follow/{followGroupId}/
GET | [[GetAdminsOfGroup|GetAdminsOfGroup]] | /Group/{groupId}/Admins/
GET | [[GetAdminsOfGroupV2|GetAdminsOfGroupV2]] | /Group/{groupId}/AdminsV2/
GET | [[GetAllFoundedGroupsForMember|GetAllFoundedGroupsForMember]] | /Group/User/{param1}/Founded/All/
GET | [[GetAllGroupsForCurrentMember|GetAllGroupsForCurrentMember]] | /Group/MyGroups/All/
GET | [[GetAllGroupsForMember|GetAllGroupsForMember]] | /Group/User/{membershipId}/All/
GET | [[GetAlliedGroups|GetAlliedGroups]] | /Group/{groupId}/Allies/
GET | [[GetAvailableAvatars (Group)|GetAvailableAvatars-(Group)]] | /Group/GetAvailableAvatars/
GET | [[GetAvailableThemes (Group)|GetAvailableThemes-(Group)]] | /Group/GetAvailableThemes/
GET | [[GetBannedMembersOfGroup|GetBannedMembersOfGroup]] | /Group/{groupId}/Banned/
GET | [[GetBannedMembersOfGroupV2|GetBannedMembersOfGroupV2]] | /Group/{groupId}/BannedV2/
GET | [[GetClanAttributeDefinitions|GetClanAttributeDefinitions]] | /Group/GetClanAttributeDefinitions/
GET | [[GetDeletedGroupsForCurrentMember|GetDeletedGroupsForCurrentMember]] | /Group/MyGroups/Deleted/
GET | [[GetFoundedGroupsForMember|GetFoundedGroupsForMember]] | /Group/User/{membershipId}/Founded/{currentPage}/
GET | [[GetGroup|GetGroup]] | /Group/{groupId}/
GET | [[GetGroupByName|GetGroupByName]] | /Group/Name/{groupName}/
GET | [[GetGroupsFollowedByGroup|GetGroupsFollowedByGroup]] | /Group/{groupId}/Following/{currentPage}/
GET | [[GetGroupsFollowingGroup|GetGroupsFollowingGroup]] | /Group/{groupId}/FollowedBy/{currentPage}/
GET | [[GetGroupTagSuggestions|GetGroupTagSuggestions]] | /Group/GetGroupTagSuggestions/
GET | [[GetJoinedGroupsForCurrentMember|GetJoinedGroupsForCurrentMember]] | /Group/MyGroups/
GET | [[GetJoinedGroupsForCurrentMemberV2|GetJoinedGroupsForCurrentMemberV2]] | /Group/MyGroups/V2/{currentPage}/
GET | [[GetJoinedGroupsForMember|GetJoinedGroupsForMember]] | /Group/User/{membershipId}/
GET | [[GetJoinedGroupsForMemberV2|GetJoinedGroupsForMemberV2]] | /Group/User/{membershipId}/Joined/{currentPage}/
GET | [[GetJoinedGroupsForMemberV3|GetJoinedGroupsForMemberV3]] | /Group/User/{membershipId}/JoinedV3/{currentPage}/
GET | [[GetMembersOfClan|GetMembersOfClan]] | /Group/{groupId}/ClanMembers/
GET | [[GetMembersOfGroup|GetMembersOfGroup]] | /Group/{groupId}/Members/
GET | [[GetMembersOfGroupV2|GetMembersOfGroupV2]] | /Group/{groupId}/MembersV2/
GET | [[GetMembersOfGroupV3|GetMembersOfGroupV3]] | /Group/{groupId}/MembersV3/
GET | [[GetMyClanMemberships|GetMyClanMemberships]] | /Group/MyClans/
GET | [[GetPendingClanMemberships|GetPendingClanMemberships]] | /Group/{groupId}/Clan/{clanMembershipType}/Pending/{currentPage}/
GET | [[GetPendingGroupsForCurrentMember|GetPendingGroupsForCurrentMember]] | /Group/MyPendingGroups/
GET | [[GetPendingGroupsForCurrentMemberV2|GetPendingGroupsForCurrentMemberV2]] | /Group/MyPendingGroups/V2/{currentPage}/
GET | [[GetPendingGroupsForMember|GetPendingGroupsForMember]] | /Group/User/{membershipId}/Pending/
GET | [[GetPendingGroupsForMemberV2|GetPendingGroupsForMemberV2]] | /Group/User/{membershipId}/PendingV2/{currentPage}/
GET | [[GetPendingMemberships|GetPendingMemberships]] | /Group/{groupId}/Members/Pending/
GET | [[GetPendingMembershipsV2|GetPendingMembershipsV2]] | /Group/{groupId}/Members/PendingV2/
POST | [[GetRecommendedGroups|GetRecommendedGroups]] | /Group/Recommended/
POST | [[GroupSearch|GroupSearch]] | /Group/Search/
POST | [[InviteClanMember|InviteClanMember]] | /Group/{groupId}/InviteToClan/{membershipId}/{clanMembershipType}/
POST | [[InviteGroupMember|InviteGroupMember]] | /Group/{groupId}/Invite/{membershipId}/
POST | [[InviteManyToJoinAlliance|InviteManyToJoinAlliance]] | /Group/{groupId}/Allies/InviteMany/
POST | [[InviteToJoinAlliance|InviteToJoinAlliance]] | /Group/{groupId}/Allies/Invite/{allyGroupId}/
POST | [[JoinClanForGroup|JoinClanForGroup]] | /Group/{groupId}/Clans/Join/{clanMembershipType}/
POST | [[KickMember|KickMember]] | /Group/{groupId}/Members/{membershipId}/Kick/
POST | [[LeaveClanForGroup|LeaveClanForGroup]] | /Group/{groupId}/Clans/Leave/{clanMembershipType}/
POST | [[OverrideFounderAdmin|OverrideFounderAdmin]] | /Group/{groupId}/Admin/FounderOverride/{membershipType}/
POST | [[RefreshClanSettingsInDestiny|RefreshClanSettingsInDestiny]] | /Group/MyClans/Refresh/{clanMembershipType}/
POST | [[RequestGroupMembership|RequestGroupMembership]] | /Group/{groupId}/Members/Apply/
POST | [[RequestGroupMembershipV2|RequestGroupMembershipV2]] | /Group/{groupId}/Members/ApplyV2/
POST | [[RequestToJoinAlliance|RequestToJoinAlliance]] | /Group/{groupId}/Allies/RequestToJoin/{allyGroupId}/
POST | [[RescindGroupMembership|RescindGroupMembership]] | /Group/{groupId}/Members/Rescind/
POST | [[SaveMigrationSelection|SaveMigrationSelection]] | /Group/{param1}/MigrationSelection/{param2}/{param3}/
POST | [[SetGroupAsAlliance|SetGroupAsAlliance]] | /Group/{groupId}/SetAsAlliance/
POST | [[SetPrivacy|SetPrivacy]] | /Group/{groupId}/Privacy/{param2}/
POST | [[UnbanMember|UnbanMember]] | /Group/{groupId}/Members/{membershipId}/Unban/
POST | [[UndeleteGroup|UndeleteGroup]] | /Group/{groupId}/Undelete/
POST | [[UnfollowAllGroupsWithGroup|UnfollowAllGroupsWithGroup]] | /Group/{groupId}/UnfollowAll/
POST | [[UnfollowGroupsWithGroup|UnfollowGroupsWithGroup]] | /Group/{groupId}/UnfollowList/
POST | [[UnfollowGroupWithGroup|UnfollowGroupWithGroup]] | /Group/{groupId}/Unfollow/{followGroupId}/

## <a name="IgnoreService"></a>IgnoreService (8 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
POST | [[FlagItem|FlagItem]] | /Ignore/Flag/
POST | [[GetIgnoresForUser|GetIgnoresForUser]] | /Ignore/MyIgnores/
GET | [[GetIgnoreStatusForPost|GetIgnoreStatusForPost]] | /Ignore/MyIgnores/Posts/{param1}/
GET | [[GetIgnoreStatusForUser|GetIgnoreStatusForUser]] | /Ignore/MyIgnores/Users/{param1}/
GET | [[GetReportContext|GetReportContext]] | /Ignore/ReportContext/{param1}/
POST | [[IgnoreItem|IgnoreItem]] | /Ignore/Ignore/
GET | [[MyLastReport|MyLastReport]] | /Ignore/MyLastReport/
POST | [[UnignoreItem|UnignoreItem]] | /Ignore/Unignore/

## <a name="GameService"></a>GameService (2 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
GET | [[GetPlayerGamesById|GetPlayerGamesById]] | /Game/GetPlayerGamesById/{param1}/
POST | [[ReachModelSneakerNet|ReachModelSneakerNet]] | /Game/ReachModelSneakerNet/{param1}/

## <a name="AdminService"></a>AdminService (18 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
GET | [[AdminUserSearch|AdminUserSearch]] | /Admin/Member/Search/
POST | [[BulkEditPost|BulkEditPost]] | /Admin/BulkEditPost/
GET | [[GetAdminHistory|GetAdminHistory]] | /Admin/GlobalHistory/{param1}/{param2}/
POST | [[GetAssignedReports|GetAssignedReports]] | /Admin/Assigned/
POST | [[GetDisciplinedReportsForMember|GetDisciplinedReportsForMember]] | /Admin/Member/{param1}/Reports/
GET | [[GetRecentDisciplineAndFlagHistoryForMember|GetRecentDisciplineAndFlagHistoryForMember]] | /Admin/Member/{param1}/RecentIncludingFlags/{param2}
POST | [[GetResolvedReports|GetResolvedReports]] | /Admin/Reports/
GET | [[GetUserBanState|GetUserBanState]] | /Admin/Member/{param1}/GetBanState/
GET | [[GetUserPostHistory|GetUserPostHistory]] | /Admin/Member/{param1}/PostHistory/{param2}/
GET | [[GetUserWebClientIpHistory|GetUserWebClientIpHistory]] | /Admin/Member/{param1}/GetWebClientIpHistory/
POST | [[GloballyIgnoreItem|GloballyIgnoreItem]] | /Admin/Ignores/GloballyIgnore/
POST | [[OverrideBanOnUser|OverrideBanOnUser]] | /Admin/Member/{param1}/SetBan/
POST | [[OverrideGlobalIgnore|OverrideGlobalIgnore]] | /Admin/Ignores/OverrideGlobalIgnore/
POST | [[OverrideGroupWallBanOnUser|OverrideGroupWallBanOnUser]] | /Admin/Member/{param1}/SetGroupWallBan/
POST | [[OverrideMsgBanOnUser|OverrideMsgBanOnUser]] | /Admin/Member/{param1}/SetMsgBan/
POST | [[OverturnReport|OverturnReport]] | /Admin/Reports/Overturn/
POST | [[ResolveReport|ResolveReport]] | /Admin/Assigned/Resolve/
POST | [[ReturnAssignedReports|ReturnAssignedReports]] | /Admin/Assigned/ReturnAll

## <a name="TrendingService"></a>TrendingService (3 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
GET | [[GetTrendingCategories|GetTrendingCategories]] | /Trending/Categories/
GET | [[GetTrendingCategory|GetTrendingCategory]] | /Trending/Categories/{param1}/{param2}/
GET | [[GetTrendingEntryDetail|GetTrendingEntryDetail]] | /Trending/Details/{param1}/{param2}/

## <a name="TokensService"></a>TokensService (14 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
POST | [[ApplyOfferToCurrentDestinyMembership|ApplyOfferToCurrentDestinyMembership]] | /Tokens/ApplyOfferToCurrentDestinyMembership/{param1}/{param2}/
POST | [[BreakBond|BreakBond]] | /Tokens/RAF/BreakBond/
POST | [[ClaimAndApplyOnToken|ClaimAndApplyOnToken]] | /Tokens/ClaimAndApplyToken/{tokenType}/
POST | [[ClaimToken|ClaimToken]] | /Tokens/Claim/
POST | [[ConsumeMarketplacePlatformCodeOffer|ConsumeMarketplacePlatformCodeOffer]] | /Tokens/ConsumeMarketplacePlatformCodeOffer/{param1}/{param2}/{param3}/
GET | [[GetCurrentUserOfferHistory|GetCurrentUserOfferHistory]] | /Tokens/OfferHistory/
GET | [[GetCurrentUserThrottleState|GetCurrentUserThrottleState]] | /Tokens/ThrottleState/
GET | [[GetRAFEligibility|GetRAFEligibility]] | /Tokens/RAF/GetEligibility/
GET | [[MarketplacePlatformCodeOfferHistory|MarketplacePlatformCodeOfferHistory]] | /Tokens/MarketplacePlatformCodeOfferHistory/
POST | [[RAFClaim|RAFClaim]] | /Tokens/RAF/Claim/
POST | [[RAFGenerateReferralCode|RAFGenerateReferralCode]] | /Tokens/RAF/GenerateReferralCode/{param1}/
GET | [[RAFGetNewPlayerBondDetails|RAFGetNewPlayerBondDetails]] | /Tokens/RAF/GetNewPlayerBondDetails/
GET | [[RAFGetVeteranBondDetails|RAFGetVeteranBondDetails]] | /Tokens/RAF/GetVeteranBondDetails/
POST | [[VerifyAge|VerifyAge]] | /Tokens/VerifyAge/

## <a name="DestinyService"></a>DestinyService (60 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
POST | [[EquipItem|EquipItem]] | /Destiny/EquipItem/
POST | [[EquipItems|EquipItems]] | /Destiny/EquipItems/
GET | [[GetAccount|GetAccount]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/
GET | [[GetAccountSummary|GetAccountSummary]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Summary/
GET | [[GetActivityBlob|GetActivityBlob]] | /Destiny/Stats/ActivityBlob/{e}/
GET | [[GetActivityHistory|GetActivityHistory]] | /Destiny/Stats/ActivityHistory/{membershipType}/{destinyMembershipId}/{characterId}/
GET | [[GetAdvisorsForAccount|GetAdvisorsForAccount]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Advisors/
GET | [[GetAdvisorsForCharacter|GetAdvisorsForCharacter]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Character/{characterId}/Advisors/
GET | [[GetAdvisorsForCharacterV2|GetAdvisorsForCharacterV2]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Character/{characterId}/Advisors/V2/
GET | [[GetAdvisorsForCurrentCharacter|GetAdvisorsForCurrentCharacter]] | /Destiny/{membershipType}/MyAccount/Character/{characterId}/Advisors/
GET | [[GetAllItemsSummary|GetAllItemsSummary]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Items/
GET | [[GetAllVendorsForCurrentCharacter|GetAllVendorsForCurrentCharacter]] | /Destiny/{membershipType}/MyAccount/Character/{characterId}/Vendors/
GET | [[GetBondAdvisors|GetBondAdvisors]] | /Destiny/{membershipType}/MyAccount/Advisors/Bonds/
GET | [[GetCharacter|GetCharacter]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Character/{characterId}/Complete/
GET | [[GetCharacterActivities|GetCharacterActivities]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Character/{characterId}/Activities/
GET | [[GetCharacterInventory|GetCharacterInventory]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Character/{characterId}/Inventory/
GET | [[GetCharacterInventorySummary|GetCharacterInventorySummary]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Character/{characterId}/Inventory/Summary/
GET | [[GetCharacterProgression|GetCharacterProgression]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Character/{characterId}/Progression/
GET | [[GetCharacterSummary|GetCharacterSummary]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Character/{characterId}/
GET | [[GetClanLeaderboards|GetClanLeaderboards]] | /Destiny/Stats/ClanLeaderboards/{param1}/
GET | [[GetDestinyAggregateActivityStats|GetDestinyAggregateActivityStats]] | /Destiny/Stats/AggregateActivityStats/{membershipType}/{destinyMembershipId}/{characterId}/
GET | [[GetDestinyExplorerItems|GetDestinyExplorerItems]] | /Destiny/Explorer/Items/
GET | [[GetDestinyExplorerTalentNodeSteps|GetDestinyExplorerTalentNodeSteps]] | /Destiny/Explorer/TalentNodeSteps/
GET | [[GetDestinyLiveTileContentItems|GetDestinyLiveTileContentItems]] | /Destiny/LiveTiles/
GET | [[GetDestinyManifest|GetDestinyManifest]] | /Destiny/Manifest/
GET | [[GetDestinySingleDefinition|GetDestinySingleDefinition]] | /Destiny/Manifest/{definitionType}/{definitionId}/
GET | [[GetExcellenceBadges|GetExcellenceBadges]] | /Destiny/Stats/GetExcellenceBadges/{membershipType}/{destinyMembershipId}/
GET | [[GetGrimoireByMembership|GetGrimoireByMembership]] | /Destiny/Vanguard/Grimoire/{membershipType}/{destinyMembershipId}/
GET | [[GetGrimoireDefinition|GetGrimoireDefinition]] | /Destiny/Vanguard/Grimoire/Definition/
GET | [[GetHistoricalStats|GetHistoricalStats]] | /Destiny/Stats/{membershipType}/{destinyMembershipId}/{characterId}/
GET | [[GetHistoricalStatsDefinition|GetHistoricalStatsDefinition]] | /Destiny/Stats/Definition/
GET | [[GetHistoricalStatsForAccount|GetHistoricalStatsForAccount]] | /Destiny/Stats/Account/{membershipType}/{destinyMembershipId}/
GET | [[GetItemDetail|GetItemDetail]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Character/{characterId}/Inventory/{itemInstanceId}/
GET | [[GetItemReferenceDetail|GetItemReferenceDetail]] | /Destiny/{param1}/Account/{param2}/Character/{param3}/ItemReference/{param4}/
GET | [[GetLeaderboards|GetLeaderboards]] | /Destiny/Stats/Leaderboards/{membershipType}/{destinyMembershipId}/
GET | [[GetLeaderboardsForCharacter|GetLeaderboardsForCharacter]] | /Destiny/Stats/Leaderboards/{membershipType}/{destinyMembershipId}/{characterId}/
GET | [[GetLeaderboardsForPsn|GetLeaderboardsForPsn]] | /Destiny/Stats/LeaderboardsForPsn/
GET | [[GetMembershipIdByDisplayName|GetMembershipIdByDisplayName]] | /Destiny/{membershipType}/Stats/GetMembershipIdByDisplayName/{displayName}/
GET | [[GetMyGrimoire|GetMyGrimoire]] | /Destiny/Vanguard/Grimoire/{membershipType}/
GET | [[GetPostGameCarnageReport|GetPostGameCarnageReport]] | /Destiny/Stats/PostGameCarnageReport/{activityInstanceId}/
GET | [[GetPublicAdvisors|GetPublicAdvisors]] | /Destiny/Advisors/
GET | [[GetPublicAdvisorsV2|GetPublicAdvisorsV2]] | /Destiny/Advisors/V2/
GET | [[GetPublicVendor|GetPublicVendor]] | /Destiny/Vendors/{vendorId}/
GET | [[GetPublicVendorWithMetadata|GetPublicVendorWithMetadata]] | /Destiny/Vendors/{vendorId}/Metadata/
GET | [[GetPublicXurVendor|GetPublicXurVendor]] | /Destiny/Advisors/Xur/
GET | [[GetRecordBookCompletionStatus|GetRecordBookCompletionStatus]] | /Destiny/{membershipType}/MyAccount/RecordBooks/{recordBookHash}/Completion/
GET | [[GetSpecialEventAdvisors|GetSpecialEventAdvisors]] | /Destiny/Events/
GET | [[GetTriumphs|GetTriumphs]] | /Destiny/{membershipType}/Account/{destinyMembershipId}/Triumphs/
GET | [[GetUniqueWeaponHistory|GetUniqueWeaponHistory]] | /Destiny/Stats/UniqueWeapons/{membershipType}/{destinyMembershipId}/{characterId}/
GET | [[GetVault|GetVault]] | /Destiny/{membershipType}/MyAccount/Vault/
GET | [[GetVaultSummary|GetVaultSummary]] | /Destiny/{membershipType}/MyAccount/Vault/Summary/
GET | [[GetVendorForCurrentCharacter|GetVendorForCurrentCharacter]] | /Destiny/{membershipType}/MyAccount/Character/{characterId}/Vendor/{vendorId}/
GET | [[GetVendorForCurrentCharacterWithMetadata|GetVendorForCurrentCharacterWithMetadata]] | /Destiny/{membershipType}/MyAccount/Character/{characterId}/Vendor/{vendorId}/Metadata/
GET | [[GetVendorItemDetailForCurrentCharacter|GetVendorItemDetailForCurrentCharacter]] | /Destiny/{membershipType}/MyAccount/Character/{characterId}/Vendor/{vendorId}/Item/{itemId}/
GET | [[GetVendorItemDetailForCurrentCharacterWithMetadata|GetVendorItemDetailForCurrentCharacterWithMetadata]] | /Destiny/{membershipType}/MyAccount/Character/{characterId}/Vendor/{vendorId}/Item/{itemId}/Metadata/
GET | [[GetVendorSummariesForCurrentCharacter|GetVendorSummariesForCurrentCharacter]] | /Destiny/{membershipType}/MyAccount/Character/{characterId}/Vendors/Summaries/
GET | [[SearchDestinyPlayer|SearchDestinyPlayer]] | /Destiny/SearchDestinyPlayer/{membershipType}/{displayName}/
POST | [[SetItemLockState|SetItemLockState]] | /Destiny/SetLockState/
POST | [[SetQuestTrackedState|SetQuestTrackedState]] | /Destiny/SetQuestTrackedState/
POST | [[TransferItem|TransferItem]] | /Destiny/TransferItem/

## <a name="CommunitycontentService"></a>CommunitycontentService (14 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
POST | [[AdminSetCommunityLiveMemberBanStatus|AdminSetCommunityLiveMemberBanStatus]] | /CommunityContent/Live/Partnerships/{param1}/{param2}/Ban/{param3}/
POST | [[AdminSetCommunityLiveMemberFeatureStatus|AdminSetCommunityLiveMemberFeatureStatus]] | /CommunityContent/Live/Partnerships/{param1}/{param2}/Feature/{param3}/
POST | [[AlterApprovalState|AlterApprovalState]] | /CommunityContent/AlterApprovalState/{param1}/
POST | [[EditContent|EditContent]] | /CommunityContent/Edit/{param1}/
GET | [[GetAdminCommunityLiveStatuses|GetAdminCommunityLiveStatuses]] | /CommunityContent/Live/Admin/{param1}/{param2}/{param3}/
GET | [[GetApprovalQueue|GetApprovalQueue]] | /CommunityContent/Queue/{param1}/{param2}/{param3}/
GET | [[GetCommunityContent|GetCommunityContent]] | /CommunityContent/Get/{param1}/{param2}/{param3}/
GET | [[GetCommunityFeaturedActivityModes|GetCommunityFeaturedActivityModes]] | /CommunityContent/Live/ActivityModes/Featured/
GET | [[GetCommunityLiveStatuses|GetCommunityLiveStatuses]] | /CommunityContent/Live/All/{partnershipType}/{communityStatusSort}/{page}/
GET | [[GetCommunityLiveStatusesForClanmates|GetCommunityLiveStatusesForClanmates]] | /CommunityContent/Live/Clan/{partnershipType}/{communityStatusSort}/{page}/
GET | [[GetCommunityLiveStatusesForFriends|GetCommunityLiveStatusesForFriends]] | /CommunityContent/Live/Friends/{partnershipType}/{communityStatusSort}/{page}/
GET | [[GetFeaturedCommunityLiveStatuses|GetFeaturedCommunityLiveStatuses]] | /CommunityContent/Live/Featured/{partnershipType}/{communityStatusSort}/{page}/
GET | [[GetStreamingStatusForMember|GetStreamingStatusForMember]] | /CommunityContent/Live/Users/{partnershipType}/{membershipType}/{membershipId}/
POST | [[SubmitContent|SubmitContent]] | /CommunityContent/Submit/

## <a name="CoreService"></a>CoreService (5 Endpoints)
Method | Name | Endpoint
------ | ---- | --------
GET | [[GetAvailableLocales|GetAvailableLocales]] | //GetAvailableLocales/
GET | [[GetCommonSettings|GetCommonSettings]] | //Settings/
GET | [[GetGlobalAlerts|GetGlobalAlerts]] | //GlobalAlerts/
GET | [[GetSystemStatus|GetSystemStatus]] | //Status/{param1}/
GET | [[HelloWorld|HelloWorld]] | //HelloWorld/

