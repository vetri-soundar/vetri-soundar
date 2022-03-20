End point:
https://restapijira.atlassian.net/rest/api/2/search?jql=project=AP

![image](https://user-images.githubusercontent.com/88602407/159144465-d726ee5e-e873-4acd-96dc-23c8542e334e.png)


Json Response:
{
    "expand": "schema,names",
    "startAt": 0,
    "maxResults": 50,
    "total": 121,
    "issues": [
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10126",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10126",
            "key": "AP-127",
            "fields": {
                "statuscategorychangedate": "2022-03-20T06:21:50.520+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-127/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-20T06:21:50.295+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000qn:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-20T06:21:50.295+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": null,
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "sad",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-127/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10123",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10123",
            "key": "AP-124",
            "fields": {
                "statuscategorychangedate": "2022-03-19T22:16:13.761+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-124/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-19T22:16:13.382+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000qf:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T22:16:13.382+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "QA API Training Arun Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "API Training create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-124/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10121",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10121",
            "key": "AP-122",
            "fields": {
                "statuscategorychangedate": "2022-03-19T22:09:21.133+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-122/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-19T22:09:20.822+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000q7:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T22:09:20.822+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "QA API Training Arun Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "API Training create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-122/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10120",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10120",
            "key": "AP-121",
            "fields": {
                "statuscategorychangedate": "2022-03-19T22:08:25.979+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-121/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-19T22:08:25.616+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000pz:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T22:08:25.616+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "QA API Training Arun Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "API Training create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-121/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10119",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10119",
            "key": "AP-120",
            "fields": {
                "statuscategorychangedate": "2022-03-19T22:08:14.636+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-120/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-19T22:08:14.349+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000pr:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T22:08:14.349+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "QA API Training Arun Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "API Training create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-120/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10118",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10118",
            "key": "AP-119",
            "fields": {
                "statuscategorychangedate": "2022-03-19T22:07:54.527+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-119/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-19T22:07:54.278+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000pj:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T22:07:54.278+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "QA API Training Arun Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "API Training create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-119/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10117",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10117",
            "key": "AP-118",
            "fields": {
                "statuscategorychangedate": "2022-03-19T22:05:15.869+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-118/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-19T22:05:15.577+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000pb:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T22:05:15.577+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "QA API Training Arun Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "API Training create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-118/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10116",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10116",
            "key": "AP-117",
            "fields": {
                "statuscategorychangedate": "2022-03-19T22:04:13.588+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-117/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-19T22:04:13.318+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000p3:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T22:04:13.318+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "QA API Training Arun Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "API Training create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-117/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10115",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10115",
            "key": "AP-116",
            "fields": {
                "statuscategorychangedate": "2022-03-19T22:03:05.843+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-116/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-19T22:03:05.484+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000ov:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T22:03:05.484+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "QA API Training Arun Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "API Training create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-116/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10114",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10114",
            "key": "AP-115",
            "fields": {
                "statuscategorychangedate": "2022-03-19T22:02:20.518+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-115/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-19T22:02:20.203+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000on:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T22:02:20.203+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "QA API Training Arun Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "API Training create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-115/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10113",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10113",
            "key": "AP-114",
            "fields": {
                "statuscategorychangedate": "2022-03-19T21:55:39.560+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-114/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-19T21:55:39.219+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000of:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T21:55:39.219+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "QA API Training Arun Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "API Training create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-114/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10110",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10110",
            "key": "AP-111",
            "fields": {
                "statuscategorychangedate": "2022-03-19T20:11:10.200+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-111/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-19T20:11:09.825+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000o7:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T20:11:09.825+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-111/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10109",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10109",
            "key": "AP-110",
            "fields": {
                "statuscategorychangedate": "2022-03-19T20:09:44.702+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-110/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-19T20:09:44.329+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000nz:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T20:09:44.329+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-110/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10108",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10108",
            "key": "AP-109",
            "fields": {
                "statuscategorychangedate": "2022-03-19T20:00:39.752+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-109/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-19T20:00:39.453+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000nr:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T20:00:39.453+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RA project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-109/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10107",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10107",
            "key": "AP-108",
            "fields": {
                "statuscategorychangedate": "2022-03-19T19:11:10.136+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": "2022-03-19T19:37:47.206+0530",
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-108/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-19T19:11:09.620+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000nj:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T19:37:23.650+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RA project - MAR 19",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-108/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10106",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10106",
            "key": "AP-107",
            "fields": {
                "statuscategorychangedate": "2022-03-19T00:36:00.434+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-107/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": "2022-03-19T19:07:49.497+0530",
                "created": "2022-03-19T00:36:00.105+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000nb:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-19T00:36:00.105+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": null,
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS Project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-107/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10105",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10105",
            "key": "AP-106",
            "fields": {
                "statuscategorychangedate": "2022-03-17T20:50:01.060+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-106/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": "2022-03-19T00:36:21.196+0530",
                "created": "2022-03-17T20:50:00.683+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000n3:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-17T20:50:00.683+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RA Project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-106/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10104",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10104",
            "key": "AP-105",
            "fields": {
                "statuscategorychangedate": "2022-03-16T01:06:04.133+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": "2022-03-19T00:40:09.605+0530",
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-105/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-16T01:06:03.786+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000mv:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-16T01:06:03.786+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-105/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10102",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10102",
            "key": "AP-103",
            "fields": {
                "statuscategorychangedate": "2022-03-13T21:02:55.201+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-103/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": "2022-03-17T18:46:13.033+0530",
                "created": "2022-03-13T21:02:54.879+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000mn:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T21:09:28.710+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Updation of Issue using the REST Assured on March 13 2021-- first time",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RA Project",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-103/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10101",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10101",
            "key": "AP-102",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:57:47.319+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": "2022-03-15T22:32:33.273+0530",
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-102/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:57:46.931+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000mf:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:57:46.931+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-102/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10100",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10100",
            "key": "AP-101",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:19.838+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": "2022-03-14T17:54:33.721+0530",
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-101/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:19.522+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000m7:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:19.522+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-101/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10099",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10099",
            "key": "AP-100",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:19.210+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-100/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:18.940+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000lz:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:18.940+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-100/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10098",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10098",
            "key": "AP-99",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:18.654+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-99/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:18.448+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000lr:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:18.448+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-99/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10097",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10097",
            "key": "AP-98",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:18.159+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-98/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:17.833+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000lj:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:17.833+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-98/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10096",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10096",
            "key": "AP-97",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:17.499+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-97/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:17.271+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000lb:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:17.271+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-97/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10095",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10095",
            "key": "AP-96",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:17.038+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-96/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:16.747+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000l3:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:16.747+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-96/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10094",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10094",
            "key": "AP-95",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:16.456+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-95/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:16.108+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000kv:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:16.108+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-95/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10093",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10093",
            "key": "AP-94",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:15.777+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-94/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:15.539+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000kn:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:15.539+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-94/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10092",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10092",
            "key": "AP-93",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:15.294+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-93/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:15.018+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000kf:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:15.018+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-93/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10091",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10091",
            "key": "AP-92",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:14.743+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-92/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:14.490+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000k7:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:14.490+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-92/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10090",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10090",
            "key": "AP-91",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:14.224+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-91/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:14.024+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000jz:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:14.024+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-91/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10089",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10089",
            "key": "AP-90",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:13.778+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-90/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:13.442+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000jr:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:13.442+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-90/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10088",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10088",
            "key": "AP-89",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:13.160+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-89/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:12.954+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000jj:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:12.954+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-89/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10087",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10087",
            "key": "AP-88",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:12.763+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-88/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:12.538+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000jb:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:12.538+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-88/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10086",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10086",
            "key": "AP-87",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:12.290+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": "2022-03-16T17:00:24.732+0530",
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-87/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:12.009+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000j3:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:12.009+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-87/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10085",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10085",
            "key": "AP-86",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:11.749+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-86/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:11.447+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000iv:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:11.447+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-86/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10084",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10084",
            "key": "AP-85",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:11.145+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-85/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:10.924+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000in:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:10.924+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-85/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10083",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10083",
            "key": "AP-84",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:10.662+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-84/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:10.359+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000if:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:10.359+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-84/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10082",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10082",
            "key": "AP-83",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:10.056+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": "2022-03-18T17:46:55.442+0530",
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-83/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:09.744+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000i7:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:09.744+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-83/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10081",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10081",
            "key": "AP-82",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:09.433+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-82/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:09.119+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000hz:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:09.119+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-82/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10080",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10080",
            "key": "AP-81",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:08.840+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-81/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:08.469+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000hr:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:08.469+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-81/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10079",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10079",
            "key": "AP-80",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:08.147+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-80/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:07.855+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000hj:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:07.855+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-80/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10078",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10078",
            "key": "AP-79",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:07.547+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-79/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:07.158+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000hb:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:07.158+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-79/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10077",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10077",
            "key": "AP-78",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:06.827+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-78/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:06.477+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000h3:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:06.477+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-78/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10076",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10076",
            "key": "AP-77",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:06.184+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-77/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:05.930+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000gv:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:05.930+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-77/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10075",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10075",
            "key": "AP-76",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:05.628+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-76/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:05.261+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000gn:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:05.261+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-76/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10074",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10074",
            "key": "AP-75",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:04.942+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-75/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:04.642+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000gf:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:04.642+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-75/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10073",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10073",
            "key": "AP-74",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:04.332+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "customfield_10033": null,
                "fixVersions": [],
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-74/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": "2022-03-16T15:46:24.308+0530",
                "created": "2022-03-13T13:55:04.038+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000g7:",
                "aggregatetimeoriginalestimate": null,
                "timeestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:04.038+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-74/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10072",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10072",
            "key": "AP-73",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:03.760+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "customfield_10031": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "lastViewed": null,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-73/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "created": "2022-03-13T13:55:03.472+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "customfield_10023": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000fz:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:03.472+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "customfield_10007": null,
                "security": null,
                "customfield_10008": null,
                "customfield_10009": null,
                "aggregatetimeestimate": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10000": "{}",
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-73/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        },
        {
            "expand": "operations,versionedRepresentations,editmeta,changelog,customfield_10010.requestTypePractice,renderedFields",
            "id": "10071",
            "self": "https://restapijira.atlassian.net/rest/api/2/issue/10071",
            "key": "AP-72",
            "fields": {
                "statuscategorychangedate": "2022-03-13T13:55:03.155+0530",
                "issuetype": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issuetype/10004",
                    "id": "10004",
                    "description": "A problem or error.",
                    "iconUrl": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/issuetype/avatar/10303?size=medium",
                    "name": "Bug",
                    "subtask": false,
                    "avatarId": 10303,
                    "hierarchyLevel": 0
                },
                "timespent": null,
                "customfield_10030": null,
                "project": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/project/10000",
                    "id": "10000",
                    "key": "AP",
                    "name": "APIMAR",
                    "projectTypeKey": "software",
                    "simplified": false,
                    "avatarUrls": {
                        "48x48": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405",
                        "24x24": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=small",
                        "16x16": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=xsmall",
                        "32x32": "https://restapijira.atlassian.net/rest/api/2/universal_avatar/view/type/project/avatar/10405?size=medium"
                    }
                },
                "customfield_10031": null,
                "customfield_10032": null,
                "fixVersions": [],
                "customfield_10033": null,
                "aggregatetimespent": null,
                "resolution": null,
                "customfield_10029": [],
                "resolutiondate": null,
                "workratio": -1,
                "watches": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-72/watchers",
                    "watchCount": 1,
                    "isWatching": true
                },
                "lastViewed": null,
                "created": "2022-03-13T13:55:02.857+0530",
                "customfield_10020": null,
                "customfield_10021": null,
                "customfield_10022": null,
                "priority": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/priority/3",
                    "iconUrl": "https://restapijira.atlassian.net/images/icons/priorities/medium.svg",
                    "name": "Medium",
                    "id": "3"
                },
                "customfield_10023": null,
                "customfield_10024": null,
                "customfield_10025": null,
                "labels": [],
                "customfield_10016": null,
                "customfield_10017": null,
                "customfield_10018": {
                    "hasEpicLinkFieldDependency": false,
                    "showField": false,
                    "nonEditableReason": {
                        "reason": "PLUGIN_LICENSE_ERROR",
                        "message": "The Parent Link is only available to Jira Premium users."
                    }
                },
                "customfield_10019": "0|i000fr:",
                "timeestimate": null,
                "aggregatetimeoriginalestimate": null,
                "versions": [],
                "issuelinks": [],
                "assignee": null,
                "updated": "2022-03-13T13:55:02.857+0530",
                "status": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/status/10000",
                    "description": "",
                    "iconUrl": "https://restapijira.atlassian.net/",
                    "name": "To Do",
                    "id": "10000",
                    "statusCategory": {
                        "self": "https://restapijira.atlassian.net/rest/api/2/statuscategory/2",
                        "id": 2,
                        "key": "new",
                        "colorName": "blue-gray",
                        "name": "To Do"
                    }
                },
                "components": [],
                "timeoriginalestimate": null,
                "description": "Creating of an issue using project keys and issue type names using the REST API",
                "customfield_10010": null,
                "customfield_10014": null,
                "customfield_10015": null,
                "customfield_10005": null,
                "customfield_10006": null,
                "security": null,
                "customfield_10007": null,
                "customfield_10008": null,
                "aggregatetimeestimate": null,
                "customfield_10009": null,
                "summary": "create issue in RS project --Feb 2022",
                "creator": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "subtasks": [],
                "reporter": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/user?accountId=622da2ff1dcf800070e7a411",
                    "accountId": "622da2ff1dcf800070e7a411",
                    "emailAddress": "restapijira@gmail.com",
                    "avatarUrls": {
                        "48x48": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "24x24": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "16x16": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png",
                        "32x32": "https://secure.gravatar.com/avatar/c307347d2625b37fd7225d8e8296aed7?d=https%3A%2F%2Favatar-management--avatars.us-west-2.prod.public.atl-paas.net%2Finitials%2FR-3.png"
                    },
                    "displayName": "RestAPIJira",
                    "active": true,
                    "timeZone": "Asia/Calcutta",
                    "accountType": "atlassian"
                },
                "customfield_10000": "{}",
                "aggregateprogress": {
                    "progress": 0,
                    "total": 0
                },
                "customfield_10001": null,
                "customfield_10002": null,
                "customfield_10003": null,
                "customfield_10004": null,
                "environment": null,
                "duedate": null,
                "progress": {
                    "progress": 0,
                    "total": 0
                },
                "votes": {
                    "self": "https://restapijira.atlassian.net/rest/api/2/issue/AP-72/votes",
                    "votes": 0,
                    "hasVoted": false
                }
            }
        }
    ]
}
