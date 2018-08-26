{
  "info": {
    "name": "Kaltura VPaaS Get Service Caption Captionasset Action Delete",
    "_postman_id": "503a79b2-e3a3-44ff-9288-da85c11f878c",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "1a9b0e35-37f9-4b70-a043-6003d0c87514",
          "name": "accessControl.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/add?accessControl[description]=%7B%7D&accessControl[isDefault]=%7B%7D&accessControl[name]=%7B%7D&accessControl[restrictions]=%7B%7D&accessControl[systemName]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Access Control Profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4baa8d27-686d-4b98-b0b2-ce787533c4dc"
            }
          ]
        },
        {
          "id": "bbd21a8a-21d8-4807-b8aa-197e66145116",
          "name": "accessControl.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "838fd737-6cd8-4641-9459-1a49ae4f5d17"
            }
          ]
        },
        {
          "id": "436a3d1d-6ffe-44f8-a1eb-5e66bdbeeca4",
          "name": "accessControl.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33a9efed-75a3-4eac-8a53-17e21dcf1899"
            }
          ]
        },
        {
          "id": "f21a94c5-7ea1-44f5-8d5f-8a9ac8ef78ec",
          "name": "accessControl.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Access Control Profiles by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3cda6815-216a-421d-8e15-4564de1d7ee9"
            }
          ]
        },
        {
          "id": "2eb1f09d-e7dc-404a-9c94-6677fbc21342",
          "name": "accessControl.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/update?accessControl[description]=%7B%7D&accessControl[isDefault]=%7B%7D&accessControl[name]=%7B%7D&accessControl[restrictions]=%7B%7D&accessControl[systemName]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f56db6bb-a80a-4425-802f-01ffefb67d18"
            }
          ]
        },
        {
          "id": "9b2fa93a-628e-422d-b66c-1a06cbea2da2",
          "name": "accessControlProfile.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/add?accessControlProfile[description]=%7B%7D&accessControlProfile[isDefault]=%7B%7D&accessControlProfile[name]=%7B%7D&accessControlProfile[rules]=%7B%7D&accessControlProfile[systemName]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new access control profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23bf9161-ae56-42ed-97f6-a7e14c33e695"
            }
          ]
        },
        {
          "id": "f2d6f6fa-9d3f-45c9-ac32-dba2728489df",
          "name": "accessControlProfile.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete access control profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5174833b-3881-4dfb-aeac-4145b2959fbf"
            }
          ]
        },
        {
          "id": "09ed3a81-7502-4af3-8b08-e4e8fcd17045",
          "name": "accessControlProfile.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get access control profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e48e38d-2481-4941-9a01-8e22e2a55cfb"
            }
          ]
        },
        {
          "id": "4b03514a-12ee-415c-a9d5-5e043e0e9faa",
          "name": "accessControlProfile.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List access control profiles by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f8f6906-fc94-4c1c-9efc-aeb0bfca4fa0"
            }
          ]
        },
        {
          "id": "d6d027a9-a912-4dce-9473-c56689a95db1",
          "name": "accessControlProfile.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/update?accessControlProfile[description]=%7B%7D&accessControlProfile[isDefault]=%7B%7D&accessControlProfile[name]=%7B%7D&accessControlProfile[rules]=%7B%7D&accessControlProfile[systemName]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update access control profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43ec7af1-4a3d-4718-8b31-05bc95a94959"
            }
          ]
        },
        {
          "id": "e15d2dd1-d791-4185-8052-8241049f74cf",
          "name": "adminUser.login",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/login?email=%7B%7D&No Name=%7B%7D&partnerId=%7B%7D&password=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an admin session using admin email and password (Used for login to the KMC application)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5fe1ec1-8537-42de-86c2-099eb9d9eea5"
            }
          ]
        },
        {
          "id": "94f66d65-3523-4603-9708-0fc0435ccdf0",
          "name": "adminUser.resetPassword",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/resetPassword?email=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Reset admin user password and send it to the users email address"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c7991f8-0067-400b-8d7f-1ca99347494a"
            }
          ]
        },
        {
          "id": "2625d3b7-0d25-44da-baef-87e55a9908d9",
          "name": "adminUser.setInitialPassword",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/setInitialPassword?hashKey=%7B%7D&newPassword=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Set initial users password"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3bfecae6-0baf-4d7f-84bb-2af2a98c1580"
            }
          ]
        },
        {
          "id": "a61a5c34-f630-4c46-81d0-7df6f7e16eff",
          "name": "adminUser.updatePassword",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/updatePassword?email=%7B%7D&newEmail=%7B%7D&newPassword=%7B%7D&No Name=%7B%7D&password=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update admin user password and email"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fbd2fa57-83e8-460b-9c0e-5e65333b5ec5"
            }
          ]
        },
        {
          "id": "aeb85239-1c37-4709-9136-5dc0a73da6f5",
          "name": "analytics.query",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/analytics/action/query?filter[dimensions]=%7B%7D&filter[filters]=%7B%7D&filter[from_time]=%7B%7D&filter[metrics]=%7B%7D&filter[orderBy]=%7B%7D&filter[to_time]=%7B%7D&filter[utcOffset]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "report query action allows to get a analytics data for specific query dimensions, metrics and filters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fffcc7a1-a8e8-483e-9458-72feb8c4cf95"
            }
          ]
        },
        {
          "id": "4a4fa761-aa21-44dc-a38f-9610b2b1acc8",
          "name": "annotation.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/add?annotation[adType]=%7B%7D&annotation[answerKey]=%7B%7D&annotation[assetId]=%7B%7D&annotation[code]=%7B%7D&annotation[correctAnswerKeys]=%7B%7D&annotation[description]=%7B%7D&annotation[duration]=%7B%7D&annotation[endTime]=%7B%7D&annotation[entryId]=%7B%7D&annotation[eventType]=%7B%7D&annotation[explanation]=%7B%7D&annotation[forceStop]=%7B%7D&annotation[hint]=%7B%7D&annotation[isPublic]=%7B%7D&annotation[objectType]=%7B%7D&annotation[optionalAnswers]=%7B%7D&annotation[parentId]=%7B%7D&annotation[partnerData]=%7B%7D&annotation[partnerSortValue]=%7B%7D&annotation[protocolType]=%7B%7D&annotation[question]=%7B%7D&annotation[quizUserEntryId]=%7B%7D&annotation[searchableOnEntry]=%7B%7D&annotation[sourceUrl]=%7B%7D&annotation[startTime]=%7B%7D&annotation[subType]=%7B%7D&annotation[systemName]=%7B%7D&annotation[tags]=%7B%7D&annotation[text]=%7B%7D&annotation[thumbOffset]=%7B%7D&annotation[title]=%7B%7D&annotation[triggeredAt]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows you to add an annotation object associated with an entry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65491089-ebef-420e-a408-848faa21dfc4"
            }
          ]
        },
        {
          "id": "3a70446f-c5d3-460b-8231-882d1eb35e02",
          "name": "annotation.addFromBulk",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/addFromBulk?No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "fileData",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Allows you to add multiple cue points objects by uploading XML that contains multiple cue point definitions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "875a93f3-b4b2-45c0-86a2-07e23b0ba19c"
            }
          ]
        },
        {
          "id": "01a6593b-e6c1-43ac-b24e-9ae6d05f10c4",
          "name": "annotation.clone",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/clone?entryId=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Clone cuePoint with id to given entry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b12376e5-246d-4a46-bb45-5d758fc47015"
            }
          ]
        },
        {
          "id": "c5465fc8-14e0-4aca-8482-65bc9ef7531e",
          "name": "annotation.count",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/count?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[codeEqual]=%7B%7D&filter[codeIn]=%7B%7D&filter[codeLike]=%7B%7D&filter[codeMultiLikeAnd]=%7B%7D&filter[codeMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[cuePointTypeEqual]=%7B%7D&filter[cuePointTypeIn]=%7B%7D&filter[descriptionLike]=%7B%7D&filter[descriptionMultiLikeAnd]=%7B%7D&filter[descriptionMultiLikeOr]=%7B%7D&filter[durationGreaterThanOrEqual]=%7B%7D&filter[durationLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[eventTypeEqual]=%7B%7D&filter[eventTypeIn]=%7B%7D&filter[forceStopEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isPublicEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueEqual]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueIn]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[protocolTypeEqual]=%7B%7D&filter[protocolTypeIn]=%7B%7D&filter[questionLike]=%7B%7D&filter[questionMultiLikeAnd]=%7B%7D&filter[questionMultiLikeOr]=%7B%7D&filter[quizUserEntryIdEqual]=%7B%7D&filter[quizUserEntryIdIn]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[subTypeEqual]=%7B%7D&filter[subTypeIn]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[textLike]=%7B%7D&filter[textMultiLikeAnd]=%7B%7D&filter[textMultiLikeOr]=%7B%7D&filter[titleLike]=%7B%7D&filter[titleMultiLikeAnd]=%7B%7D&filter[titleMultiLikeOr]=%7B%7D&filter[triggeredAtGreaterThanOrEqual]=%7B%7D&filter[triggeredAtLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[userIdCurrent]=%7B%7D&filter[userIdEqualCurrent]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "count cue point objects by filter"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10ae11bf-fc2e-4008-a118-90a6c12d4397"
            }
          ]
        },
        {
          "id": "956134ad-b5f1-4970-987d-0aa99a313334",
          "name": "annotation.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "delete cue point by id, and delete all children cue points"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81195e0c-fdd9-4901-aa88-9604f6ee85fd"
            }
          ]
        },
        {
          "id": "08bd0552-0151-44dd-b564-7ae15f2e6715",
          "name": "annotation.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve an CuePoint object by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "67aad5b3-dffc-40e7-8edc-ed0abf16f47e"
            }
          ]
        },
        {
          "id": "0e7606e9-da79-410e-8eef-b411eb486f26",
          "name": "annotation.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[codeEqual]=%7B%7D&filter[codeIn]=%7B%7D&filter[codeLike]=%7B%7D&filter[codeMultiLikeAnd]=%7B%7D&filter[codeMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[cuePointTypeEqual]=%7B%7D&filter[cuePointTypeIn]=%7B%7D&filter[descriptionLike]=%7B%7D&filter[descriptionMultiLikeAnd]=%7B%7D&filter[descriptionMultiLikeOr]=%7B%7D&filter[durationGreaterThanOrEqual]=%7B%7D&filter[durationLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[eventTypeEqual]=%7B%7D&filter[eventTypeIn]=%7B%7D&filter[forceStopEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isPublicEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueEqual]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueIn]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[protocolTypeEqual]=%7B%7D&filter[protocolTypeIn]=%7B%7D&filter[questionLike]=%7B%7D&filter[questionMultiLikeAnd]=%7B%7D&filter[questionMultiLikeOr]=%7B%7D&filter[quizUserEntryIdEqual]=%7B%7D&filter[quizUserEntryIdIn]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[subTypeEqual]=%7B%7D&filter[subTypeIn]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[textLike]=%7B%7D&filter[textMultiLikeAnd]=%7B%7D&filter[textMultiLikeOr]=%7B%7D&filter[titleLike]=%7B%7D&filter[titleMultiLikeAnd]=%7B%7D&filter[titleMultiLikeOr]=%7B%7D&filter[triggeredAtGreaterThanOrEqual]=%7B%7D&filter[triggeredAtLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[userIdCurrent]=%7B%7D&filter[userIdEqualCurrent]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List annotation objects by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6dac8ca7-a98e-431d-8350-6864be434d3d"
            }
          ]
        },
        {
          "id": "37c14c5c-ad89-4d55-a5d4-ca9fab2c7b40",
          "name": "annotation.serveBulk",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/serveBulk?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[codeEqual]=%7B%7D&filter[codeIn]=%7B%7D&filter[codeLike]=%7B%7D&filter[codeMultiLikeAnd]=%7B%7D&filter[codeMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[cuePointTypeEqual]=%7B%7D&filter[cuePointTypeIn]=%7B%7D&filter[descriptionLike]=%7B%7D&filter[descriptionMultiLikeAnd]=%7B%7D&filter[descriptionMultiLikeOr]=%7B%7D&filter[durationGreaterThanOrEqual]=%7B%7D&filter[durationLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[eventTypeEqual]=%7B%7D&filter[eventTypeIn]=%7B%7D&filter[forceStopEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isPublicEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueEqual]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueIn]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[protocolTypeEqual]=%7B%7D&filter[protocolTypeIn]=%7B%7D&filter[questionLike]=%7B%7D&filter[questionMultiLikeAnd]=%7B%7D&filter[questionMultiLikeOr]=%7B%7D&filter[quizUserEntryIdEqual]=%7B%7D&filter[quizUserEntryIdIn]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[subTypeEqual]=%7B%7D&filter[subTypeIn]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[textLike]=%7B%7D&filter[textMultiLikeAnd]=%7B%7D&filter[textMultiLikeOr]=%7B%7D&filter[titleLike]=%7B%7D&filter[titleMultiLikeAnd]=%7B%7D&filter[titleMultiLikeOr]=%7B%7D&filter[triggeredAtGreaterThanOrEqual]=%7B%7D&filter[triggeredAtLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[userIdCurrent]=%7B%7D&filter[userIdEqualCurrent]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download multiple cue points objects as XML definitions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ce18071-ee42-4f6b-9a11-8b889bebe6cb"
            }
          ]
        },
        {
          "id": "f9ba3190-e3c9-4caa-b386-37f2a64be591",
          "name": "annotation.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/update?annotation[adType]=%7B%7D&annotation[answerKey]=%7B%7D&annotation[assetId]=%7B%7D&annotation[code]=%7B%7D&annotation[correctAnswerKeys]=%7B%7D&annotation[description]=%7B%7D&annotation[duration]=%7B%7D&annotation[endTime]=%7B%7D&annotation[entryId]=%7B%7D&annotation[eventType]=%7B%7D&annotation[explanation]=%7B%7D&annotation[forceStop]=%7B%7D&annotation[hint]=%7B%7D&annotation[isPublic]=%7B%7D&annotation[objectType]=%7B%7D&annotation[optionalAnswers]=%7B%7D&annotation[parentId]=%7B%7D&annotation[partnerData]=%7B%7D&annotation[partnerSortValue]=%7B%7D&annotation[protocolType]=%7B%7D&annotation[question]=%7B%7D&annotation[quizUserEntryId]=%7B%7D&annotation[searchableOnEntry]=%7B%7D&annotation[sourceUrl]=%7B%7D&annotation[startTime]=%7B%7D&annotation[subType]=%7B%7D&annotation[systemName]=%7B%7D&annotation[tags]=%7B%7D&annotation[text]=%7B%7D&annotation[thumbOffset]=%7B%7D&annotation[title]=%7B%7D&annotation[triggeredAt]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update annotation by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8561180e-e3f0-4cfb-ba32-0254d8096974"
            }
          ]
        },
        {
          "id": "6e7924d3-9822-4209-aa72-2411518b5acd",
          "name": "annotation.updateStatus",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/updateStatus?id=%7B%7D&No Name=%7B%7D&status=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update cuePoint status by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0de51cc-aec0-4b95-97bf-0eb64ecb585d"
            }
          ]
        },
        {
          "id": "885f941c-18ea-46f7-b0e9-b30653f0c902",
          "name": "appToken.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/add?appToken[expiry]=%7B%7D&appToken[hashType]=%7B%7D&appToken[sessionDuration]=%7B%7D&appToken[sessionPrivileges]=%7B%7D&appToken[sessionType]=%7B%7D&appToken[sessionUserId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new application authentication token"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32a8ab5a-3ad9-45b5-a5ab-d7fb960b18c0"
            }
          ]
        },
        {
          "id": "2cac7dce-9837-4c9e-bb9e-de6bc9e840e5",
          "name": "appToken.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete application authentication token by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "73748b4c-3094-4b79-9406-8300666644a0"
            }
          ]
        },
        {
          "id": "f5c342d7-8bb4-4bd7-94e1-69b0f29a6f2f",
          "name": "appToken.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get application authentication token by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea1a45c7-059d-42c6-abe0-f9e91a84a3b3"
            }
          ]
        },
        {
          "id": "8008b248-0d2c-46a2-b10e-817ff6ac7982",
          "name": "appToken.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List application authentication tokens by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb9b1855-0585-4fb9-97f0-c03f4e799a76"
            }
          ]
        },
        {
          "id": "44241b87-07cb-4578-99c4-9caf6f18cef8",
          "name": "appToken.startSession",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/startSession?expiry=%7B%7D&id=%7B%7D&No Name=%7B%7D&tokenHash=%7B%7D&type=%7B%7D&userId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts a new KS (kaltura Session) based on application authentication token id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e60b568d-927f-458c-b9d5-2d1ec3728ed9"
            }
          ]
        },
        {
          "id": "20fe2e24-388a-4aec-8d09-6b0381cc2fc1",
          "name": "appToken.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/update?appToken[expiry]=%7B%7D&appToken[hashType]=%7B%7D&appToken[sessionDuration]=%7B%7D&appToken[sessionPrivileges]=%7B%7D&appToken[sessionType]=%7B%7D&appToken[sessionUserId]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update application authentication token by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03cfd7a5-4e04-4bf9-a362-e9e7c6c757a0"
            }
          ]
        },
        {
          "id": "50e35d3a-1db1-4b32-95ad-8ced13a0ed23",
          "name": "aspera.getFaspUrl",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/aspera_aspera/action/getFaspUrl?flavorAssetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Aspera Aspera Action Getfaspurl"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03bb4f14-5b47-4467-98b2-8035e510d588"
            }
          ]
        },
        {
          "id": "f9b0d2b6-fad4-401b-8d56-b59f1aa1685d",
          "name": "attachmentAsset.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/add?attachmentAsset[accuracy]=%7B%7D&attachmentAsset[actualSourceAssetParamsIds]=%7B%7D&attachmentAsset[fileExt]=%7B%7D&attachmentAsset[filename]=%7B%7D&attachmentAsset[format]=%7B%7D&attachmentAsset[humanVerified]=%7B%7D&attachmentAsset[language]=%7B%7D&attachmentAsset[objectType]=%7B%7D&attachmentAsset[partnerData]=%7B%7D&attachmentAsset[partnerDescription]=%7B%7D&attachmentAsset[providerType]=%7B%7D&attachmentAsset[tags]=%7B%7D&attachmentAsset[title]=%7B%7D&entryId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5021424-a6d2-4422-b680-2f6d4d31950d"
            }
          ]
        },
        {
          "id": "0eb07bb8-9ee5-49e0-a31a-37bcbc712e13",
          "name": "attachmentAsset.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/delete?attachmentAssetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Attachment Attachmentasset Action Delete"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05b23df8-005a-4c37-a9be-42ac913a2f10"
            }
          ]
        },
        {
          "id": "de9634cd-8cbf-4262-8669-1ddfd915ee26",
          "name": "attachmentAsset.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/get?attachmentAssetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Attachment Attachmentasset Action Get"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "56439dc3-d3ab-46d0-bee1-a7974e2a92ba"
            }
          ]
        },
        {
          "id": "4ef7f2d1-fee6-4623-a4c8-6dd7ac5f42b6",
          "name": "attachmentAsset.getRemotePaths",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/getRemotePaths?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get remote storage existing paths for the asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b23dedf-44e6-43a9-af95-c5ad27cbba20"
            }
          ]
        },
        {
          "id": "7eb93afd-5ae8-41ff-b96e-7a1b49ee470b",
          "name": "attachmentAsset.getUrl",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/getUrl?id=%7B%7D&No Name=%7B%7D&storageId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get download URL for the asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68697a41-6038-4ce0-bcad-00b3456c8fb4"
            }
          ]
        },
        {
          "id": "667ec0e3-3717-4400-83f1-b9afb55d7edf",
          "name": "attachmentAsset.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[captionParamsIdEqual]=%7B%7D&filter[captionParamsIdIn]=%7B%7D&filter[contentLike]=%7B%7D&filter[contentMultiLikeAnd]=%7B%7D&filter[contentMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[deletedAtGreaterThanOrEqual]=%7B%7D&filter[deletedAtLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[flavorParamsIdEqual]=%7B%7D&filter[flavorParamsIdIn]=%7B%7D&filter[formatEqual]=%7B%7D&filter[formatIn]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[labelEqual]=%7B%7D&filter[labelIn]=%7B%7D&filter[languageEqual]=%7B%7D&filter[languageIn]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerDescriptionLike]=%7B%7D&filter[partnerDescriptionMultiLikeAnd]=%7B%7D&filter[partnerDescriptionMultiLikeOr]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[sizeGreaterThanOrEqual]=%7B%7D&filter[sizeLessThanOrEqual]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[statusNotIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[thumbParamsIdEqual]=%7B%7D&filter[thumbParamsIdIn]=%7B%7D&filter[typeIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List attachment Assets by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "940ca5c7-05d5-4219-aa94-55575d643535"
            }
          ]
        },
        {
          "id": "22812a1d-f0cb-4cc5-bb91-bd2463d7093a",
          "name": "attachmentAsset.serve",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/serve?attachmentAssetId=%7B%7D&No Name=%7B%7D&serveOptions[download]=%7B%7D&serveOptions[referrer]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Serves attachment by its id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "caf66962-bd26-4b56-b942-c965ae48817b"
            }
          ]
        },
        {
          "id": "c63c9333-7130-4984-8e5e-5bb27b267828",
          "name": "attachmentAsset.setContent",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/setContent?contentResource[assetId]=%7B%7D&contentResource[content]=%7B%7D&contentResource[dropFolderFileId]=%7B%7D&contentResource[entryId]=%7B%7D&contentResource[fileSyncObjectType]=%7B%7D&contentResource[flavorParamsId]=%7B%7D&contentResource[forceAsyncDownload]=%7B%7D&contentResource[keepOriginalFile]=%7B%7D&contentResource[keyPassphrase]=%7B%7D&contentResource[localFilePath]=%7B%7D&contentResource[objectId]=%7B%7D&contentResource[objectSubType]=%7B%7D&contentResource[objectType]=%7B%7D&contentResource[privateKey]=%7B%7D&contentResource[publicKey]=%7B%7D&contentResource[resources]=%7B%7D&contentResource[resource][assetId]=%7B%7D&contentResource[resource][content]=%7B%7D&contentResource[resource][dropFolderFileId]=%7B%7D&contentResource[resource][entryId]=%7B%7D&contentResource[resource][fileSyncObjectType]=%7B%7D&contentResource[resource][flavorParamsId]=%7B%7D&contentResource[resource][forceAsyncDownload]=%7B%7D&contentResource[resource][keepOriginalFile]=%7B%7D&contentResource[resource][keyPassphrase]=%7B%7D&contentResource[resource][localFilePath]=%7B%7D&contentResource[resource][objectId]=%7B%7D&contentResource[resource][objectSubType]=%7B%7D&contentResource[resource][objectType]=%7B%7D&contentResource[resource][privateKey]=%7B%7D&contentResource[resource][publicKey]=%7B%7D&contentResource[resource][resources]=%7B%7D&contentResource[resource][resource][assetId]=%7B%7D&contentResource[resource][resource][content]=%7B%7D&contentResource[resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][entryId]=%7B%7D&contentResource[resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][objectId]=%7B%7D&contentResource[resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][objectType]=%7B%7D&contentResource[resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][assetId]=%7B%7D&contentResource[resource][resource][resource][content]=%7B%7D&contentResource[resource][resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][resource][entryId]=%7B%7D&contentResource[resource][resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][resource][objectId]=%7B%7D&contentResource[resource][resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][resource][objectType]=%7B%7D&contentResource[resource][resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][resource][token]=%7B%7D&contentResource[resource][resource][resource][url]=%7B%7D&contentResource[resource][resource][resource][version]=%7B%7D&contentResource[resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][token]=%7B%7D&contentResource[resource][resource][url]=%7B%7D&contentResource[resource][resource][version]=%7B%7D&contentResource[resource][storageProfileId]=%7B%7D&contentResource[resource][token]=%7B%7D&contentResource[resource][url]=%7B%7D&contentResource[resource][version]=%7B%7D&contentResource[storageProfileId]=%7B%7D&contentResource[token]=%7B%7D&contentResource[url]=%7B%7D&contentResource[version]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "contentResource[fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                }
              ]
            },
            "description": "Update content of attachment asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb6db545-8470-4f11-b639-e361d0d59cd3"
            }
          ]
        },
        {
          "id": "9e419e88-bbab-4425-b1c2-5a6eed3f42d8",
          "name": "attachmentAsset.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/update?attachmentAsset[accuracy]=%7B%7D&attachmentAsset[actualSourceAssetParamsIds]=%7B%7D&attachmentAsset[fileExt]=%7B%7D&attachmentAsset[filename]=%7B%7D&attachmentAsset[format]=%7B%7D&attachmentAsset[humanVerified]=%7B%7D&attachmentAsset[language]=%7B%7D&attachmentAsset[objectType]=%7B%7D&attachmentAsset[partnerData]=%7B%7D&attachmentAsset[partnerDescription]=%7B%7D&attachmentAsset[providerType]=%7B%7D&attachmentAsset[tags]=%7B%7D&attachmentAsset[title]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update attachment asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ffe76fab-808c-4f44-bbcf-e2a1f92615b4"
            }
          ]
        },
        {
          "id": "6fd5dc67-84b4-4e6b-b060-440e90f1188e",
          "name": "attUverse.getFeed",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attuversedistribution_attuverse/action/getFeed?distributionProfileId=%7B%7D&hash=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Attuversedistribution Attuverse Action Getfeed"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2f3b1ad-5f93-4932-9e1c-3f7369b5f16f"
            }
          ]
        },
        {
          "id": "7ed640fe-5917-4ac3-bd8c-c9ca612d363a",
          "name": "auditTrail.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/audit_audittrail/action/add?auditTrail[action]=%7B%7D&auditTrail[auditObjectType]=%7B%7D&auditTrail[data][changedItems]=%7B%7D&auditTrail[data][dc]=%7B%7D&auditTrail[data][fileType]=%7B%7D&auditTrail[data][info]=%7B%7D&auditTrail[data][objectSubType]=%7B%7D&auditTrail[data][objectType]=%7B%7D&auditTrail[data][original]=%7B%7D&auditTrail[data][version]=%7B%7D&auditTrail[entryId]=%7B%7D&auditTrail[objectId]=%7B%7D&auditTrail[relatedObjectId]=%7B%7D&auditTrail[relatedObjectType]=%7B%7D&auditTrail[userId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows you to add an audit trail object and audit trail content associated with Kaltura object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9c845b44-3184-4d1c-a0e1-162e29d1ceee"
            }
          ]
        },
        {
          "id": "1da01ece-bdcf-42c6-9323-b7b504729025",
          "name": "auditTrail.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/audit_audittrail/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve an audit trail object by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "599b74ff-4275-4a01-bca2-fe3316351a64"
            }
          ]
        },
        {
          "id": "3d23e179-11cf-4bdf-901a-3992ff9f79ab",
          "name": "auditTrail.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/audit_audittrail/action/list?filter[actionEqual]=%7B%7D&filter[actionIn]=%7B%7D&filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[auditObjectTypeEqual]=%7B%7D&filter[auditObjectTypeIn]=%7B%7D&filter[clientTagEqual]=%7B%7D&filter[contextEqual]=%7B%7D&filter[contextIn]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=