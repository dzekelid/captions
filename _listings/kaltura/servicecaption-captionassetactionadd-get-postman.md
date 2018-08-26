{
  "info": {
    "name": "Kaltura VPaaS Get Service Caption Captionasset Action Add",
    "_postman_id": "8d8bb699-c980-4235-8134-0e0071fa81b6",
    "description": "Add caption asset",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "0831f6e1-7d85-47f7-82e8-ec1f743fe2bf",
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
              "id": "633b373e-fb7b-4a07-b84e-37ce05cb0bb3"
            }
          ]
        },
        {
          "id": "87aa3f5b-1510-4f14-a881-66db26a1740d",
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
              "id": "f14201fb-952d-4f54-b28d-8193978dddf7"
            }
          ]
        },
        {
          "id": "14f91cc3-1d5d-423e-8057-e4d39b9b1f27",
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
              "id": "da84eb3a-8e93-427c-ab75-20924059e46d"
            }
          ]
        },
        {
          "id": "32648a9b-de94-4474-8c0c-3d679b243f9b",
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
              "id": "4f475ecc-214b-406e-a048-7854f3686b88"
            }
          ]
        },
        {
          "id": "2ee61519-f55e-4fb2-ac69-235032bf500b",
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
              "id": "e6d792eb-8cb1-43c8-8145-bacbc8789f1f"
            }
          ]
        },
        {
          "id": "d15351fa-4529-4ffa-b881-4d22caae610f",
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
              "id": "1210c575-0039-4e51-bdaf-5c6aaab63745"
            }
          ]
        },
        {
          "id": "9349ddb9-1aab-404e-8a32-2939bde42811",
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
              "id": "7085bcd4-4694-4873-9576-63be7d1763f3"
            }
          ]
        },
        {
          "id": "9311c02d-1bc2-4a41-8fec-b6db290efe4f",
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
              "id": "bcb89f62-8689-4d7e-acb2-fb3e51849314"
            }
          ]
        },
        {
          "id": "b2ab00a2-571d-40ab-a5e9-3937f91b82bc",
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
              "id": "9c944506-ed48-49ea-90ec-4da84375d914"
            }
          ]
        },
        {
          "id": "62d80714-345d-4f02-a38a-d6677411c9c5",
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
              "id": "a1ffc9a9-b8e5-4d83-84b3-1a697faf498e"
            }
          ]
        },
        {
          "id": "774820a7-2bf7-4d05-801d-dba30762b0aa",
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
              "id": "e4654c73-d9b6-4b66-955e-29fbd7ea8bd2"
            }
          ]
        },
        {
          "id": "c0f4441b-cde5-4f2c-9369-4ce045d4ab6d",
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
              "id": "ea3c19bd-fe00-42ac-875f-8d580e091976"
            }
          ]
        },
        {
          "id": "8c592718-a7c7-4912-8947-96be7eaa528d",
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
              "id": "e1c2f65f-f5e6-400b-b0a6-e6803e78f80e"
            }
          ]
        },
        {
          "id": "7af708e6-d46e-44ae-9097-e411affd19d4",
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
              "id": "26bbec42-e8d4-42a7-a545-07d155137de4"
            }
          ]
        },
        {
          "id": "31b24998-87b5-4d3f-8a4a-4d6309165b57",
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
              "id": "2676065b-ed59-4aef-9641-74ae16018c8f"
            }
          ]
        },
        {
          "id": "1b6773fe-a71e-4be8-8a6a-8f49943df701",
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
              "id": "851c41f1-5d2d-47e8-8c83-f12e97eda52f"
            }
          ]
        },
        {
          "id": "5acb0e02-c049-4eab-b85f-c3c12e6f7775",
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
              "id": "d0081ad3-c7d1-481b-b0dd-613fe5467235"
            }
          ]
        },
        {
          "id": "5d4c6d89-47f5-43e5-8fb7-6d412b1c55ee",
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
              "id": "939f2ddc-a094-4602-a217-8bc891716ac8"
            }
          ]
        },
        {
          "id": "897b0c98-140a-44a0-bb88-f2c7ab774d01",
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
              "id": "aa51ba9d-2d46-4b76-8a36-10ed1f707d62"
            }
          ]
        },
        {
          "id": "2b35270c-8bb0-4ba0-9c2d-015b9a1e8db8",
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
              "id": "0519deac-54db-4f74-a292-89844de6d426"
            }
          ]
        },
        {
          "id": "59944159-20b8-4864-b901-d73922457b95",
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
              "id": "0196ad2d-43c4-4a96-8c5d-b59ffffbaa2f"
            }
          ]
        },
        {
          "id": "d8915094-0cdb-4d93-8f2f-3e417f9f4a0c",
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
              "id": "af65d0dc-ef72-4a0c-b574-8edcdc23fd5b"
            }
          ]
        },
        {
          "id": "085cb1b8-f26f-4d6e-a1a4-a024d9f04914",
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
              "id": "6ac7ccb9-a7d0-4c99-9013-af86f8d6e70e"
            }
          ]
        },
        {
          "id": "dbf9b274-0333-48df-9843-a556e7294783",
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
              "id": "bc896fac-1722-4608-9fd7-64351ea49299"
            }
          ]
        },
        {
          "id": "c419c207-0f83-4c75-a6bf-c71dc0a0350c",
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
              "id": "6cef5d50-e046-4541-bd57-f46da768549c"
            }
          ]
        },
        {
          "id": "176da94a-65ed-4b80-9186-d7122c0106d2",
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
              "id": "1171d49b-e23a-4f52-9830-3d98d319235a"
            }
          ]
        },
        {
          "id": "b5389da4-edf0-442b-93ff-d82917ce26e8",
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
              "id": "61acaaee-22f8-4b77-9732-3b9698b5b63f"
            }
          ]
        },
        {
          "id": "446c93aa-2680-4e60-9034-f522b5516278",
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
              "id": "e8007abe-23b0-4e4b-b47a-cf5d2ed386dd"
            }
          ]
        },
        {
          "id": "957de98a-c294-4273-b6b8-35c671b48c2c",
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
              "id": "795e6063-ff0e-49f4-9e6f-ed7c0f9f40be"
            }
          ]
        },
        {
          "id": "d5809563-6b16-4b1b-92ad-2b52f41b478c",
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
              "id": "9e6704e2-268e-4622-897c-4e98464591b1"
            }
          ]
        },
        {
          "id": "7e50b5e9-1ecd-4cc5-8d70-d0a478407cfa",
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
              "id": "e58eff54-0028-4c54-898b-f8267e3d949a"
            }
          ]
        },
        {
          "id": "c70c4538-d219-4dea-8ae4-6d8328131049",
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
              "id": "92405b5e-7a35-4caf-ae14-11d58262560f"
            }
          ]
        },
        {
          "id": "11cfb324-cee5-4999-bf6e-f14e29a5bd35",
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
              "id": "2016f413-2067-4b49-9cf8-7884d2c864a8"
            }
          ]
        },
        {
          "id": "17f879fd-65ab-4d05-a363-0b5620f032ab",
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
              "id": "de377ba7-7f5f-404b-8082-c44c683bdb44"
            }
          ]
        },
        {
          "id": "66c8cb64-1704-4faf-80da-7d2f0fc8925b",
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
              "id": "fa07694a-9859-487f-9d0b-138c2b824222"
            }
          ]
        },
        {
          "id": "004341de-037a-4c46-95d8-06433b2165cc",
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
              "id": "e60e9517-5ece-44fb-a701-ea3ce2ddf017"
            }
          ]
        },
        {
          "id": "8a071171-fb31-4cf5-a199-5a1f5b4f46a6",
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
              "id": "bf3c3ed9-6204-4129-a17e-f6c7379f619a"
            }
          ]
        },
        {
          "id": "c60e7d65-15f9-43c4-9d20-6954ad486b5d",
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
              "id": "5e26e4d3-896b-4f82-97e1-a3c7133796f5"
            }
          ]
        },
        {
          "id": "a271a3c8-f778-4955-bea9-0de608fd44b3",
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
              "id": "42bac0a4-551b-43c6-a778-15b1bcf30e77"
            }
          ]
        },
        {
          "id": "21bdc2e8-2931-44b5-91d9-7cd065d197da",
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
              "id": "3c384b49-f6bc-468d-9099-a43b8b8ee5fd"
            }
          ]
        },
        {
          "id": "4af7dfc4-1351-4efb-9aa2-3a3f7c71fc4d",
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
              "id": "9524dbd8-4266-472e-ab1a-47e8094df0fb"
            }
          ]
        },
        {
          "id": "57101a97-1056-4b01-aff2-02fc1085a3d6",
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
              "id": "e21306b1-7ba4-4e97-bce1-991c0b45b21d"
            }
          ]
        },
        {
          "id": "078d72c3-25fe-4231-8704-564fe343cf63",
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
              "id": "f13b299c-e730-4f30-826e-99ca993cb568"
            }
          ]
        },
        {
          "id": "a62fe07e-b534-483c-b5aa-e29ad4415345",
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
              "id": "c0428dfb-c148-4688-b081-a90500bdcd86"
            }
          ]
        },
        {
          "id": "a71e502c-e134-4d42-9be8-2cda34515179",
          "name": "auditTrail.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/audit_audittrail/action/list?filter[actionEqual]=%7B%7D&filter[actionIn]=%7B%7D&filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[auditObjectTypeEqual]=%7B%7D&filter[auditObjectTypeIn]=%7B%7D&filter[clientTagEqual]=%7B%7D&filter[contextEqual]=%7B%7D&filter[contextIn]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLes