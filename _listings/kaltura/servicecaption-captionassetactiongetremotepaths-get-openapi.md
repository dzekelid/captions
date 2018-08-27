---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Caption Captionasset Action Getremotepaths
  description: Get remote storage existing paths for the asset
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/caption_captionasset/action/add:
    get:
      summary: Get Service Caption Captionasset Action Add
      description: Add caption asset
      operationId: captionAsset.add
      x-api-path-slug: servicecaption-captionassetactionadd-get
      parameters:
      - in: query
        name: captionAsset[accuracy]
        description: The Accuracy of the caption content
      - in: query
        name: captionAsset[actualSourceAssetParamsIds]
        description: Comma separated list of source flavor params ids
      - in: query
        name: captionAsset[captionParamsId]
        description: '`insertOnly`The Caption Params used to create this Caption Asset'
      - in: query
        name: captionAsset[fileExt]
        description: '`insertOnly`The file extension'
      - in: query
        name: captionAsset[format]
        description: '`insertOnly`Enum Type: `KalturaCaptionType`The caption format'
      - in: query
        name: captionAsset[isDefault]
        description: 'Enum Type: `KalturaNullableBoolean`Is default caption asset
          of the entry'
      - in: query
        name: captionAsset[label]
        description: Friendly label
      - in: query
        name: captionAsset[language]
        description: 'Enum Type: `KalturaLanguage`The language of the caption asset
          content'
      - in: query
        name: captionAsset[parentId]
        description: '`insertOnly`The parent id of the asset'
      - in: query
        name: captionAsset[partnerData]
        description: Partner private data
      - in: query
        name: captionAsset[partnerDescription]
        description: Partner friendly description
      - in: query
        name: captionAsset[tags]
        description: Tags used to identify the Flavor Asset in various scenarios
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - Add
  /service/caption_captionasset/action/delete:
    get:
      summary: Get Service Caption Captionasset Action Delete
      description: ""
      operationId: captionAsset.delete
      x-api-path-slug: servicecaption-captionassetactiondelete-get
      parameters:
      - in: query
        name: captionAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - Delete
  /service/caption_captionasset/action/get:
    get:
      summary: Get Service Caption Captionasset Action Get
      description: ""
      operationId: captionAsset.get
      x-api-path-slug: servicecaption-captionassetactionget-get
      parameters:
      - in: query
        name: captionAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - Get
  /service/caption_captionasset/action/getRemotePaths:
    get:
      summary: Get Service Caption Captionasset Action Getremotepaths
      description: Get remote storage existing paths for the asset
      operationId: captionAsset.getRemotePaths
      x-api-path-slug: servicecaption-captionassetactiongetremotepaths-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - GetRemotePaths
  /service/caption_captionasset/action/getUrl:
    get:
      summary: Get Service Caption Captionasset Action Geturl
      description: Get download URL for the asset
      operationId: captionAsset.getUrl
      x-api-path-slug: servicecaption-captionassetactiongeturl-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      - in: query
        name: storageId
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - GetUrl
  /service/caption_captionasset/action/list:
    get:
      summary: Get Service Caption Captionasset Action List
      description: List caption Assets by filter and pager
      operationId: captionAsset.list
      x-api-path-slug: servicecaption-captionassetactionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[captionParamsIdEqual]
      - in: query
        name: filter[captionParamsIdIn]
      - in: query
        name: filter[contentLike]
      - in: query
        name: filter[contentMultiLikeAnd]
      - in: query
        name: filter[contentMultiLikeOr]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[deletedAtGreaterThanOrEqual]
      - in: query
        name: filter[deletedAtLessThanOrEqual]
      - in: query
        name: filter[endTimeGreaterThanOrEqual]
      - in: query
        name: filter[endTimeLessThanOrEqual]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[entryIdIn]
      - in: query
        name: filter[flavorParamsIdEqual]
      - in: query
        name: filter[flavorParamsIdIn]
      - in: query
        name: filter[formatEqual]
        description: 'Enum Type: `KalturaAttachmentType`'
      - in: query
        name: filter[formatIn]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[labelEqual]
      - in: query
        name: filter[labelIn]
      - in: query
        name: filter[languageEqual]
        description: 'Enum Type: `KalturaLanguage`'
      - in: query
        name: filter[languageIn]
      - in: query
        name: filter[objectType]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[partnerDescriptionLike]
      - in: query
        name: filter[partnerDescriptionMultiLikeAnd]
      - in: query
        name: filter[partnerDescriptionMultiLikeOr]
      - in: query
        name: filter[partnerIdEqual]
      - in: query
        name: filter[partnerIdIn]
      - in: query
        name: filter[sizeGreaterThanOrEqual]
      - in: query
        name: filter[sizeLessThanOrEqual]
      - in: query
        name: filter[startTimeGreaterThanOrEqual]
      - in: query
        name: filter[startTimeLessThanOrEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaAttachmentAssetStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[statusNotIn]
      - in: query
        name: filter[tagsLike]
      - in: query
        name: filter[tagsMultiLikeAnd]
      - in: query
        name: filter[tagsMultiLikeOr]
      - in: query
        name: filter[thumbParamsIdEqual]
      - in: query
        name: filter[thumbParamsIdIn]
      - in: query
        name: filter[typeIn]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - List
  /service/caption_captionasset/action/serve:
    get:
      summary: Get Service Caption Captionasset Action Serve
      description: Serves caption by its id
      operationId: captionAsset.serve
      x-api-path-slug: servicecaption-captionassetactionserve-get
      parameters:
      - in: query
        name: captionAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - Serve
  /service/caption_captionasset/action/serveByEntryId:
    get:
      summary: Get Service Caption Captionasset Action Servebyentryid
      description: Serves caption by entry id and thumnail params id
      operationId: captionAsset.serveByEntryId
      x-api-path-slug: servicecaption-captionassetactionservebyentryid-get
      parameters:
      - in: query
        name: captionParamId
        description: if not set, default caption will be used
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - ServeByEntryId
  /service/caption_captionasset/action/serveWebVTT:
    get:
      summary: Get Service Caption Captionasset Action Servewebvtt
      description: Serves caption by its id converting it to segmented WebVTT
      operationId: captionAsset.serveWebVTT
      x-api-path-slug: servicecaption-captionassetactionservewebvtt-get
      parameters:
      - in: query
        name: captionAssetId
      - in: query
        name: localTimestamp
      - in: query
        name: No Name
      - in: query
        name: segmentDuration
      - in: query
        name: segmentIndex
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - ServeWebVTT
  /service/caption_captionasset/action/setAsDefault:
    get:
      summary: Get Service Caption Captionasset Action Setasdefault
      description: Markss the caption as default and removes that mark from all other
        caption assets of the entry.
      operationId: captionAsset.setAsDefault
      x-api-path-slug: servicecaption-captionassetactionsetasdefault-get
      parameters:
      - in: query
        name: captionAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - SetAsDefault
  /service/caption_captionasset/action/setContent:
    post:
      summary: Post Service Caption Captionasset Action Setcontent
      description: Update content of caption asset
      operationId: captionAsset.setContent
      x-api-path-slug: servicecaption-captionassetactionsetcontent-post
      parameters:
      - in: query
        name: contentResource[assetId]
        description: ID of the source asset
      - in: query
        name: contentResource[content]
        description: Textual content
      - in: query
        name: contentResource[dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: contentResource[entryId]
        description: ID of the source entry
      - in: formData
        name: contentResource[fileData]
        description: Represents the $_FILE
      - in: query
        name: contentResource[fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: contentResource[flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: contentResource[forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: contentResource[keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: contentResource[keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: contentResource[localFilePath]
        description: Full path to the local file
      - in: query
        name: contentResource[objectId]
        description: The object id of the file sync object
      - in: query
        name: contentResource[objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: contentResource[objectType]
      - in: query
        name: contentResource[privateKey]
        description: SSH private key
      - in: query
        name: contentResource[publicKey]
        description: SSH public key
      - in: query
        name: contentResource[resources]
      - in: query
        name: contentResource[resource][assetId]
        description: ID of the source asset
      - in: query
        name: contentResource[resource][content]
        description: Textual content
      - in: query
        name: contentResource[resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: contentResource[resource][entryId]
        description: ID of the source entry
      - in: formData
        name: contentResource[resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: contentResource[resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: contentResource[resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: contentResource[resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: contentResource[resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: contentResource[resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: contentResource[resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: contentResource[resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: contentResource[resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: contentResource[resource][objectType]
      - in: query
        name: contentResource[resource][privateKey]
        description: SSH private key
      - in: query
        name: contentResource[resource][publicKey]
        description: SSH public key
      - in: query
        name: contentResource[resource][resources]
      - in: query
        name: contentResource[resource][resource][assetId]
        description: ID of the source asset
      - in: query
        name: contentResource[resource][resource][content]
        description: Textual content
      - in: query
        name: contentResource[resource][resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: contentResource[resource][resource][entryId]
        description: ID of the source entry
      - in: formData
        name: contentResource[resource][resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: contentResource[resource][resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: contentResource[resource][resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: contentResource[resource][resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: contentResource[resource][resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: contentResource[resource][resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: contentResource[resource][resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: contentResource[resource][resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: contentResource[resource][resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: contentResource[resource][resource][objectType]
      - in: query
        name: contentResource[resource][resource][privateKey]
        description: SSH private key
      - in: query
        name: contentResource[resource][resource][publicKey]
        description: SSH public key
      - in: query
        name: contentResource[resource][resource][resources]
      - in: query
        name: contentResource[resource][resource][resource][assetId]
        description: ID of the source asset
      - in: query
        name: contentResource[resource][resource][resource][content]
        description: Textual content
      - in: query
        name: contentResource[resource][resource][resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: contentResource[resource][resource][resource][entryId]
        description: ID of the source entry
      - in: formData
        name: contentResource[resource][resource][resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: contentResource[resource][resource][resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: contentResource[resource][resource][resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: contentResource[resource][resource][resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: contentResource[resource][resource][resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: contentResource[resource][resource][resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: contentResource[resource][resource][resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: contentResource[resource][resource][resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: contentResource[resource][resource][resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: contentResource[resource][resource][resource][objectType]
      - in: query
        name: contentResource[resource][resource][resource][privateKey]
        description: SSH private key
      - in: query
        name: contentResource[resource][resource][resource][publicKey]
        description: SSH public key
      - in: query
        name: contentResource[resource][resource][resource][resources]
      - in: query
        name: contentResource[resource][resource][resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: contentResource[resource][resource][resource][token]
        description: Token that returned from upload
      - in: query
        name: contentResource[resource][resource][resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: contentResource[resource][resource][resource][version]
        description: The version of the file sync object
      - in: query
        name: contentResource[resource][resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: contentResource[resource][resource][token]
        description: Token that returned from upload
      - in: query
        name: contentResource[resource][resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: contentResource[resource][resource][version]
        description: The version of the file sync object
      - in: query
        name: contentResource[resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: contentResource[resource][token]
        description: Token that returned from upload
      - in: query
        name: contentResource[resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: contentResource[resource][version]
        description: The version of the file sync object
      - in: query
        name: contentResource[storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: contentResource[token]
        description: Token that returned from upload
      - in: query
        name: contentResource[url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: contentResource[version]
        description: The version of the file sync object
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - SetContent
  /service/caption_captionasset/action/update:
    get:
      summary: Get Service Caption Captionasset Action Update
      description: Update caption asset
      operationId: captionAsset.update
      x-api-path-slug: servicecaption-captionassetactionupdate-get
      parameters:
      - in: query
        name: captionAsset[accuracy]
        description: The Accuracy of the caption content
      - in: query
        name: captionAsset[actualSourceAssetParamsIds]
        description: Comma separated list of source flavor params ids
      - in: query
        name: captionAsset[captionParamsId]
        description: '`insertOnly`The Caption Params used to create this Caption Asset'
      - in: query
        name: captionAsset[fileExt]
        description: '`insertOnly`The file extension'
      - in: query
        name: captionAsset[format]
        description: '`insertOnly`Enum Type: `KalturaCaptionType`The caption format'
      - in: query
        name: captionAsset[isDefault]
        description: 'Enum Type: `KalturaNullableBoolean`Is default caption asset
          of the entry'
      - in: query
        name: captionAsset[label]
        description: Friendly label
      - in: query
        name: captionAsset[language]
        description: 'Enum Type: `KalturaLanguage`The language of the caption asset
          content'
      - in: query
        name: captionAsset[parentId]
        description: '`insertOnly`The parent id of the asset'
      - in: query
        name: captionAsset[partnerData]
        description: Partner private data
      - in: query
        name: captionAsset[partnerDescription]
        description: Partner friendly description
      - in: query
        name: captionAsset[tags]
        description: Tags used to identify the Flavor Asset in various scenarios
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionasset
      - Action
      - Update
  /service/caption_captionparams/action/add:
    get:
      summary: Get Service Caption Captionparams Action Add
      description: Add new Caption Params
      operationId: captionParams.add
      x-api-path-slug: servicecaption-captionparamsactionadd-get
      parameters:
      - in: query
        name: captionParams[description]
        description: The description of the Flavor Params
      - in: query
        name: captionParams[format]
        description: '`insertOnly`Enum Type: `KalturaCaptionType`The caption format'
      - in: query
        name: captionParams[isDefault]
        description: 'Enum Type: `KalturaNullableBoolean`Is default caption asset
          of the entry'
      - in: query
        name: captionParams[label]
        description: Friendly label
      - in: query
        name: captionParams[language]
        description: '`insertOnly`Enum Type: `KalturaLanguage`The language of the
          caption content'
      - in: query
        name: captionParams[mediaParserType]
        description: 'Enum Type: `KalturaMediaParserType`Media parser type to be used
          for post-conversion validation'
      - in: query
        name: captionParams[name]
        description: The name of the Flavor Params
      - in: query
        name: captionParams[partnerId]
      - in: query
        name: captionParams[remoteStorageProfileIds]
        description: Comma seperated ids of remote storage profiles that the flavor
          distributed to, the distribution done by the conversion engine
      - in: query
        name: captionParams[requiredPermissions]
      - in: query
        name: captionParams[sourceAssetParamsIds]
        description: Comma seperated ids of source flavor params this flavor is created
          from
      - in: query
        name: captionParams[sourceParamsId]
        description: Id of the caption params or the flavor params to be used as source
          for the caption creation
      - in: query
        name: captionParams[sourceRemoteStorageProfileId]
        description: Id of remote storage profile that used to get the source, zero
          indicates Kaltura data center
      - in: query
        name: captionParams[systemName]
        description: System name of the Flavor Params
      - in: query
        name: captionParams[tags]
        description: The Flavor Params tags are used to identify the flavor for different
          usage (e
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionparams
      - Action
      - Add
  /service/caption_captionparams/action/delete:
    get:
      summary: Get Service Caption Captionparams Action Delete
      description: Delete Caption Params by ID
      operationId: captionParams.delete
      x-api-path-slug: servicecaption-captionparamsactiondelete-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionparams
      - Action
      - Delete
  /service/caption_captionparams/action/get:
    get:
      summary: Get Service Caption Captionparams Action Get
      description: Get Caption Params by ID
      operationId: captionParams.get
      x-api-path-slug: servicecaption-captionparamsactionget-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionparams
      - Action
      - Get
  /service/caption_captionparams/action/list:
    get:
      summary: Get Service Caption Captionparams Action List
      description: List Caption Params by filter with paging support (By default -
        all system default params will be listed too)
      operationId: captionParams.list
      x-api-path-slug: servicecaption-captionparamsactionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[formatEqual]
        description: 'Enum Type: `KalturaCaptionType`'
      - in: query
        name: filter[formatIn]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[isSystemDefaultEqual]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[systemNameEqual]
      - in: query
        name: filter[systemNameIn]
      - in: query
        name: filter[tagsEqual]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionparams
      - Action
      - List
  /service/caption_captionparams/action/update:
    get:
      summary: Get Service Caption Captionparams Action Update
      description: Update Caption Params by ID
      operationId: captionParams.update
      x-api-path-slug: servicecaption-captionparamsactionupdate-get
      parameters:
      - in: query
        name: captionParams[description]
        description: The description of the Flavor Params
      - in: query
        name: captionParams[format]
        description: '`insertOnly`Enum Type: `KalturaCaptionType`The caption format'
      - in: query
        name: captionParams[isDefault]
        description: 'Enum Type: `KalturaNullableBoolean`Is default caption asset
          of the entry'
      - in: query
        name: captionParams[label]
        description: Friendly label
      - in: query
        name: captionParams[language]
        description: '`insertOnly`Enum Type: `KalturaLanguage`The language of the
          caption content'
      - in: query
        name: captionParams[mediaParserType]
        description: 'Enum Type: `KalturaMediaParserType`Media parser type to be used
          for post-conversion validation'
      - in: query
        name: captionParams[name]
        description: The name of the Flavor Params
      - in: query
        name: captionParams[partnerId]
      - in: query
        name: captionParams[remoteStorageProfileIds]
        description: Comma seperated ids of remote storage profiles that the flavor
          distributed to, the distribution done by the conversion engine
      - in: query
        name: captionParams[requiredPermissions]
      - in: query
        name: captionParams[sourceAssetParamsIds]
        description: Comma seperated ids of source flavor params this flavor is created
          from
      - in: query
        name: captionParams[sourceParamsId]
        description: Id of the caption params or the flavor params to be used as source
          for the caption creation
      - in: query
        name: captionParams[sourceRemoteStorageProfileId]
        description: Id of remote storage profile that used to get the source, zero
          indicates Kaltura data center
      - in: query
        name: captionParams[systemName]
        description: System name of the Flavor Params
      - in: query
        name: captionParams[tags]
        description: The Flavor Params tags are used to identify the flavor for different
          usage (e
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Caption
      - Captionparams
      - Action
      - Update
  /service/captionsearch_captionassetitem/action/parse:
    get:
      summary: Get Service Captionsearch Captionassetitem Action Parse
      description: Parse content of caption asset and index it
      operationId: captionAssetItem.parse
      x-api-path-slug: servicecaptionsearch-captionassetitemactionparse-get
      parameters:
      - in: query
        name: captionAssetId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Captionsearch
      - Captionassetitem
      - Action
      - Parse
  /service/captionsearch_captionassetitem/action/search:
    get:
      summary: Get Service Captionsearch Captionassetitem Action Search
      description: Search caption asset items by filter, pager and free text
      operationId: captionAssetItem.search
      x-api-path-slug: servicecaptionsearch-captionassetitemactionsearch-get
      parameters:
      - in: query
        name: captionAssetItemFilter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][categoriesMatchOr]
      - in: query
        name: captionAssetItemFilter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][categoryIdEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][contentLike]
      - in: query
        name: captionAssetItemFilter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: captionAssetItemFilter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: captionAssetItemFilter[advancedSearch][cuePointsFreeText]
      - in: query
        name: captionAssetItemFilter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][cuePointTypeIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][distributionProfileId]
      - in: query
        name: captionAssetItemFilter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: captionAssetItemFilter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][extendedStatusIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][field]
      - in: query
        name: captionAssetItemFilter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: captionAssetItemFilter[advancedSearch][idEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][idIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: captionAssetItemFilter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][items]
      - in: query
        name: captionAssetItemFilter[advancedSearch][memberIdEq]
      - in: query
        name: captionAssetItemFilter[advancedSearch][memberIdIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: captionAssetItemFilter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: captionAssetItemFilter[advancedSearch][metadataProfileId]
      - in: query
        name: captionAssetItemFilter[advancedSearch][noDistributionProfiles]
      - in: query
        name: captionAssetItemFilter[advancedSearch][not]
      - in: query
        name: captionAssetItemFilter[advancedSearch][objectType]
      - in: query
        name: captionAssetItemFilter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][userIdEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][userIdIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][value]
      - in: query
        name: captionAssetItemFilter[advancedSearch][watermarkId]
      - in: query
        name: captionAssetItemFilter[captionParamsIdEqual]
      - in: query
        name: captionAssetItemFilter[captionParamsIdIn]
      - in: query
        name: captionAssetItemFilter[contentLike]
      - in: query
        name: captionAssetItemFilter[contentMultiLikeAnd]
      - in: query
        name: captionAssetItemFilter[contentMultiLikeOr]
      - in: query
        name: captionAssetItemFilter[createdAtGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[createdAtLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[deletedAtGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[deletedAtLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[endTimeGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[endTimeLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[entryIdEqual]
      - in: query
        name: captionAssetItemFilter[entryIdIn]
      - in: query
        name: captionAssetItemFilter[formatEqual]
        description: 'Enum Type: `KalturaCaptionType`'
      - in: query
        name: captionAssetItemFilter[formatIn]
      - in: query
        name: captionAssetItemFilter[idEqual]
      - in: query
        name: captionAssetItemFilter[idIn]
      - in: query
        name: captionAssetItemFilter[labelEqual]
      - in: query
        name: captionAssetItemFilter[labelIn]
      - in: query
        name: captionAssetItemFilter[languageEqual]
        description: 'Enum Type: `KalturaLanguage`'
      - in: query
        name: captionAssetItemFilter[languageIn]
      - in: query
        name: captionAssetItemFilter[orderBy]
      - in: query
        name: captionAssetItemFilter[partnerDescriptionLike]
      - in: query
        name: captionAssetItemFilter[partnerDescriptionMultiLikeAnd]
      - in: query
        name: captionAssetItemFilter[partnerDescriptionMultiLikeOr]
      - in: query
        name: captionAssetItemFilter[partnerIdEqual]
      - in: query
        name: captionAssetItemFilter[partnerIdIn]
      - in: query
        name: captionAssetItemFilter[sizeGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[sizeLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[startTimeGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[startTimeLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[statusEqual]
        description: 'Enum Type: `KalturaCaptionAssetStatus`'
      - in: query
        name: captionAssetItemFilter[statusIn]
      - in: query
        name: captionAssetItemFilter[statusNotIn]
      - in: query
        name: captionAssetItemFilter[tagsLike]
      - in: query
        name: captionAssetItemFilter[tagsMultiLikeAnd]
      - in: query
        name: captionAssetItemFilter[tagsMultiLikeOr]
      - in: query
        name: captionAssetItemFilter[typeIn]
      - in: query
        name: captionAssetItemFilter[updatedAtGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[updatedAtLessThanOrEqual]
      - in: query
        name: captionAssetItemPager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: captionAssetItemPager[pageSize]
        description: The number of objects to retrieve
      - in: query
        name: entryFilter[accessControlIdEqual]
      - in: query
        name: entryFilter[accessControlIdIn]
      - in: query
        name: entryFilter[adminTagsLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[adminTagsMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[adminTagsMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: entryFilter[advancedSearch][categoriesMatchOr]
      - in: query
        name: entryFilter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: entryFilter[advancedSearch][categoryIdEqual]
      - in: query
        name: entryFilter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: entryFilter[advancedSearch][contentLike]
      - in: query
        name: entryFilter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: entryFilter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: entryFilter[advancedSearch][cuePointsFreeText]
      - in: query
        name: entryFilter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: entryFilter[advancedSearch][cuePointTypeIn]
      - in: query
        name: entryFilter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: entryFilter[advancedSearch][distributionProfileId]
      - in: query
        name: entryFilter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: entryFilter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: entryFilter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: entryFilter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: entryFilter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: entryFilter[advancedSearch][extendedStatusIn]
      - in: query
        name: entryFilter[advancedSearch][field]
      - in: query
        name: entryFilter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: entryFilter[advancedSearch][idEqual]
      - in: query
        name: entryFilter[advancedSearch][idIn]
      - in: query
        name: entryFilter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: entryFilter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: entryFilter[advancedSearch][items]
      - in: query
        name: entryFilter[advancedSearch][memberIdEq]
      - in: query
        name: entryFilter[advancedSearch][memberIdIn]
      - in: query
        name: entryFilter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: entryFilter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: entryFilter[advancedSearch][metadataProfileId]
      - in: query
        name: entryFilter[advancedSearch][noDistributionProfiles]
      - in: query
        name: entryFilter[advancedSearch][not]
      - in: query
        name: entryFilter[advancedSearch][objectType]
      - in: query
        name: entryFilter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: entryFilter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: entryFilter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: entryFilter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: entryFilter[advancedSearch][userIdEqual]
      - in: query
        name: entryFilter[advancedSearch][userIdIn]
      - in: query
        name: entryFilter[advancedSearch][value]
      - in: query
        name: entryFilter[advancedSearch][watermarkId]
      - in: query
        name: entryFilter[assetParamsIdsMatchAnd]
      - in: query
        name: entryFilter[assetParamsIdsMatchOr]
      - in: query
        name: entryFilter[categoriesFullNameIn]
      - in: query
        name: entryFilter[categoriesIdsEmpty]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: entryFilter[categoriesIdsMatchAnd]
      - in: query
        name: entryFilter[categoriesIdsMatchOr]
        description: All entries of the categories, excluding their child categories
      - in: query
        name: entryFilter[categoriesIdsNotContains]
      - in: query
        name: entryFilter[categoriesMatchAnd]
      - in: query
        name: entryFilter[categoriesMatchOr]
        description: All entries within these categories or their child categories
      - in: query
        name: entryFilter[categoriesNotContains]
      - in: query
        name: entryFilter[categoryAncestorIdIn]
        description: All entries within this categoy or in child categories
      - in: query
        name: entryFilter[createdAtGreaterThanOrEqual]
        description: This filter parameter should be in use for retrieving only entries
          which were created at Kaltura system after a specific time/date (standard
          timestamp format)
      - in: query
        name: entryFilter[createdAtLessThanOrEqual]
        description: This filter parameter should be in use for retrieving only entries
          which were created at Kaltura system before a specific time/date (standard
          timestamp format)
      - in: query
        name: entryFilter[creatorIdEqual]
      - in: query
        name: entryFilter[documentTypeEqual]
        description: 'Enum Type: `KalturaDocumentType`'
      - in: query
        name: entryFilter[documentTypeIn]
      - in: query
        name: entryFilter[durationGreaterThanOrEqual]
      - in: query
        name: entryFilter[durationGreaterThan]
      - in: query
        name: entryFilter[durationLessThanOrEqual]
      - in: query
        name: entryFilter[durationLessThan]
      - in: query
        name: entryFilter[durationTypeMatchOr]
      - in: query
        name: entryFilter[endDateGreaterThanOrEqualOrNull]
      - in: query
        name: entryFilter[endDateGreaterThanOrEqual]
      - in: query
        name: entryFilter[endDateLessThanOrEqualOrNull]
      - in: query
        name: entryFilter[endDateLessThanOrEqual]
      - in: query
        name: entryFilter[entitledUsersEditMatchAnd]
      - in: query
        name: entryFilter[entitledUsersEditMatchOr]
      - in: query
        name: entryFilter[entitledUsersPublishMatchAnd]
      - in: query
        name: entryFilter[entitledUsersPublishMatchOr]
      - in: query
        name: entryFilter[externalSourceTypeEqual]
        description: 'Enum Type: `KalturaExternalMediaSourceType`'
      - in: query
        name: entryFilter[externalSourceTypeIn]
      - in: query
        name: entryFilter[flavorParamsIdsMatchAnd]
      - in: query
        name: entryFilter[flavorParamsIdsMatchOr]
      - in: query
        name: entryFilter[freeText]
      - in: query
        name: entryFilter[groupIdEqual]
      - in: query
        name: entryFilter[hasMediaServerHostname]
      - in: query
        name: entryFilter[idEqual]
        description: This filter should be in use for retrieving only a specific entry
          (identified by its entryId)
      - in: query
        name: entryFilter[idIn]
        description: This filter should be in use for retrieving few specific entries
          (string should include comma separated list of entryId strings)
      - in: query
        name: entryFilter[idNotIn]
      - in: query
        name: entryFilter[isLive]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: entryFilter[isRecordedEntryIdEmpty]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: entryFilter[isRoot]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: entryFilter[lastPlayedAtGreaterThanOrEqual]
      - in: query
        name: entryFilter[lastPlayedAtLessThanOrEqual]
      - in: query
        name: entryFilter[limit]
      - in: query
        name: entryFilter[mediaDateGreaterThanOrEqual]
      - in: query
        name: entryFilter[mediaDateLessThanOrEqual]
      - in: query
        name: entryFilter[mediaTypeEqual]
        description: 'Enum Type: `KalturaMediaType`'
      - in: query
        name: entryFilter[mediaTypeIn]
      - in: query
        name: entryFilter[moderationStatusEqual]
        description: 'Enum Type: `KalturaEntryModerationStatus`'
      - in: query
        name: entryFilter[moderationStatusIn]
      - in: query
        name: entryFilter[moderationStatusNotEqual]
        description: 'Enum Type: `KalturaEntryModerationStatus`'
      - in: query
        name: entryFilter[moderationStatusNotIn]
      - in: query
        name: entryFilter[nameEqual]
        description: This filter should be in use for retrieving entries with a specific
          name
      - in: query
        name: entryFilter[nameLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[nameMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[nameMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[objectType]
      - in: query
        name: entryFilter[orderBy]
      - in: query
        name: entryFilter[parentEntryIdEqual]
      - in: query
        name: entryFilter[partnerIdEqual]
        description: This filter should be in use for retrieving only entries which
          were uploaded by/assigned to users of a specific Kaltura Partner (identified
          by Partner ID)
      - in: query
        name: entryFilter[partnerIdIn]
        description: This filter should be in use for retrieving only entries within
          Kaltura network which were uploaded by/assigned to users of few Kaltura
          Partners  (string should include comma separated list of PartnerIDs)
      - in: query
        name: entryFilter[partnerSortValueGreaterThanOrEqual]
      - in: query
        name: entryFilter[partnerSortValueLessThanOrEqual]
      - in: query
        name: entryFilter[redirectFromEntryId]
        description: The id of the original entry
      - in: query
        name: entryFilter[referenceIdEqual]
      - in: query
        name: entryFilter[referenceIdIn]
      - in: query
        name: entryFilter[replacedEntryIdEqual]
      - in: query
        name: entryFilter[replacedEntryIdIn]
      - in: query
        name: entryFilter[replacementStatusEqual]
        description: 'Enum Type: `KalturaEntryReplacementStatus`'
      - in: query
        name: entryFilter[replacementStatusIn]
      - in: query
        name: entryFilter[replacingEntryIdEqual]
      - in: query
        name: entryFilter[replacingEntryIdIn]
      - in: query
        name: entryFilter[rootEntryIdEqual]
      - in: query
        name: entryFilter[rootEntryIdIn]
      - in: query
        name: entryFilter[searchTextMatchAnd]
        description: 'This filter should be in use for retrieving specific entries
          while search match the input string within all of the following metadata
          attributes: name, description, tags, adminTags'
      - in: query
        name: entryFilter[searchTextMatchOr]
        description: 'This filter should be in use for retrieving specific entries
          while search match the input string within at least one of the following
          metadata attributes: name, description, tags, adminTags'
      - in: query
        name: entryFilter[sourceTypeEqual]
        description: 'Enum Type: `KalturaSourceType`'
      - in: query
        name: entryFilter[sourceTypeIn]
      - in: query
        name: entryFilter[sourceTypeNotEqual]
        description: 'Enum Type: `KalturaSourceType`'
      - in: query
        name: entryFilter[sourceTypeNotIn]
      - in: query
        name: entryFilter[startDateGreaterThanOrEqualOrNull]
      - in: query
        name: entryFilter[startDateGreaterThanOrEqual]
      - in: query
        name: entryFilter[startDateLessThanOrEqualOrNull]
      - in: query
        name: entryFilter[startDateLessThanOrEqual]
      - in: query
        name: entryFilter[statusEqual]
        description: 'Enum Type: `KalturaEntryStatus`This filter should be in use
          for retrieving only entries, at a specific {'
      - in: query
        name: entryFilter[statusIn]
        description: This filter should be in use for retrieving only entries, at
          few specific {
      - in: query
        name: entryFilter[statusNotEqual]
        description: 'Enum Type: `KalturaEntryStatus`This filter should be in use
          for retrieving only entries, not at a specific {'
      - in: query
        name: entryFilter[statusNotIn]
        description: This filter should be in use for retrieving only entries, not
          at few specific {
      - in: query
        name: entryFilter[tagsAdminTagsMultiLikeAnd]
      - in: query
        name: entryFilter[tagsAdminTagsMultiLikeOr]
      - in: query
        name: entryFilter[tagsAdminTagsNameMultiLikeAnd]
      - in: query
        name: entryFilter[tagsAdminTagsNameMultiLikeOr]
      - in: query
        name: entryFilter[tagsLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[tagsMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[tagsMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[tagsNameMultiLikeAnd]
      - in: query
        name: entryFilter[tagsNameMultiLikeOr]
      - in: query
        name: entryFilter[totalRankGreaterThanOrEqual]
      - in: query
        name: entryFilter[totalRankLessThanOrEqual]
      - in: query
        name: entryFilter[typeEqual]
        description: 'Enum Type: `KalturaEntryType`'
      - in: query
        name: entryFilter[typeIn]
        description: This filter should be in use for retrieving entries of few {
      - in: query
        name: entryFilter[updatedAtGreaterThanOrEqual]
      - in: query
        name: entryFilter[updatedAtLessThanOrEqual]
      - in: query
        name: entryFilter[userIdEqual]
        description: This filter parameter should be in use for retrieving only entries,
          uploaded by/assigned to a specific user (identified by user Id)
      - in: query
        name: entryFilter[userIdIn]
      - in: query
        name: entryFilter[userIdNotIn]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Captionsearch
      - Captionassetitem
      - Action
      - Search
  /service/captionsearch_captionassetitem/action/searchEntries:
    get:
      summary: Get Service Captionsearch Captionassetitem Action Searchentries
      description: Search caption asset items by filter, pager and free text
      operationId: captionAssetItem.searchEntries
      x-api-path-slug: servicecaptionsearch-captionassetitemactionsearchentries-get
      parameters:
      - in: query
        name: captionAssetItemFilter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][categoriesMatchOr]
      - in: query
        name: captionAssetItemFilter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][categoryIdEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][contentLike]
      - in: query
        name: captionAssetItemFilter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: captionAssetItemFilter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: captionAssetItemFilter[advancedSearch][cuePointsFreeText]
      - in: query
        name: captionAssetItemFilter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][cuePointTypeIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][distributionProfileId]
      - in: query
        name: captionAssetItemFilter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: captionAssetItemFilter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][extendedStatusIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][field]
      - in: query
        name: captionAssetItemFilter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: captionAssetItemFilter[advancedSearch][idEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][idIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: captionAssetItemFilter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][items]
      - in: query
        name: captionAssetItemFilter[advancedSearch][memberIdEq]
      - in: query
        name: captionAssetItemFilter[advancedSearch][memberIdIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: captionAssetItemFilter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: captionAssetItemFilter[advancedSearch][metadataProfileId]
      - in: query
        name: captionAssetItemFilter[advancedSearch][noDistributionProfiles]
      - in: query
        name: captionAssetItemFilter[advancedSearch][not]
      - in: query
        name: captionAssetItemFilter[advancedSearch][objectType]
      - in: query
        name: captionAssetItemFilter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: captionAssetItemFilter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][userIdEqual]
      - in: query
        name: captionAssetItemFilter[advancedSearch][userIdIn]
      - in: query
        name: captionAssetItemFilter[advancedSearch][value]
      - in: query
        name: captionAssetItemFilter[advancedSearch][watermarkId]
      - in: query
        name: captionAssetItemFilter[captionParamsIdEqual]
      - in: query
        name: captionAssetItemFilter[captionParamsIdIn]
      - in: query
        name: captionAssetItemFilter[contentLike]
      - in: query
        name: captionAssetItemFilter[contentMultiLikeAnd]
      - in: query
        name: captionAssetItemFilter[contentMultiLikeOr]
      - in: query
        name: captionAssetItemFilter[createdAtGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[createdAtLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[deletedAtGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[deletedAtLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[endTimeGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[endTimeLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[entryIdEqual]
      - in: query
        name: captionAssetItemFilter[entryIdIn]
      - in: query
        name: captionAssetItemFilter[formatEqual]
        description: 'Enum Type: `KalturaCaptionType`'
      - in: query
        name: captionAssetItemFilter[formatIn]
      - in: query
        name: captionAssetItemFilter[idEqual]
      - in: query
        name: captionAssetItemFilter[idIn]
      - in: query
        name: captionAssetItemFilter[labelEqual]
      - in: query
        name: captionAssetItemFilter[labelIn]
      - in: query
        name: captionAssetItemFilter[languageEqual]
        description: 'Enum Type: `KalturaLanguage`'
      - in: query
        name: captionAssetItemFilter[languageIn]
      - in: query
        name: captionAssetItemFilter[orderBy]
      - in: query
        name: captionAssetItemFilter[partnerDescriptionLike]
      - in: query
        name: captionAssetItemFilter[partnerDescriptionMultiLikeAnd]
      - in: query
        name: captionAssetItemFilter[partnerDescriptionMultiLikeOr]
      - in: query
        name: captionAssetItemFilter[partnerIdEqual]
      - in: query
        name: captionAssetItemFilter[partnerIdIn]
      - in: query
        name: captionAssetItemFilter[sizeGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[sizeLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[startTimeGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[startTimeLessThanOrEqual]
      - in: query
        name: captionAssetItemFilter[statusEqual]
        description: 'Enum Type: `KalturaCaptionAssetStatus`'
      - in: query
        name: captionAssetItemFilter[statusIn]
      - in: query
        name: captionAssetItemFilter[statusNotIn]
      - in: query
        name: captionAssetItemFilter[tagsLike]
      - in: query
        name: captionAssetItemFilter[tagsMultiLikeAnd]
      - in: query
        name: captionAssetItemFilter[tagsMultiLikeOr]
      - in: query
        name: captionAssetItemFilter[typeIn]
      - in: query
        name: captionAssetItemFilter[updatedAtGreaterThanOrEqual]
      - in: query
        name: captionAssetItemFilter[updatedAtLessThanOrEqual]
      - in: query
        name: captionAssetItemPager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: captionAssetItemPager[pageSize]
        description: The number of objects to retrieve
      - in: query
        name: entryFilter[accessControlIdEqual]
      - in: query
        name: entryFilter[accessControlIdIn]
      - in: query
        name: entryFilter[adminTagsLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[adminTagsMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[adminTagsMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: entryFilter[advancedSearch][categoriesMatchOr]
      - in: query
        name: entryFilter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: entryFilter[advancedSearch][categoryIdEqual]
      - in: query
        name: entryFilter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: entryFilter[advancedSearch][contentLike]
      - in: query
        name: entryFilter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: entryFilter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: entryFilter[advancedSearch][cuePointsFreeText]
      - in: query
        name: entryFilter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: entryFilter[advancedSearch][cuePointTypeIn]
      - in: query
        name: entryFilter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: entryFilter[advancedSearch][distributionProfileId]
      - in: query
        name: entryFilter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: entryFilter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: entryFilter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: entryFilter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: entryFilter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: entryFilter[advancedSearch][extendedStatusIn]
      - in: query
        name: entryFilter[advancedSearch][field]
      - in: query
        name: entryFilter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: entryFilter[advancedSearch][idEqual]
      - in: query
        name: entryFilter[advancedSearch][idIn]
      - in: query
        name: entryFilter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: entryFilter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: entryFilter[advancedSearch][items]
      - in: query
        name: entryFilter[advancedSearch][memberIdEq]
      - in: query
        name: entryFilter[advancedSearch][memberIdIn]
      - in: query
        name: entryFilter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: entryFilter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: entryFilter[advancedSearch][metadataProfileId]
      - in: query
        name: entryFilter[advancedSearch][noDistributionProfiles]
      - in: query
        name: entryFilter[advancedSearch][not]
      - in: query
        name: entryFilter[advancedSearch][objectType]
      - in: query
        name: entryFilter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: entryFilter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: entryFilter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: entryFilter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: entryFilter[advancedSearch][userIdEqual]
      - in: query
        name: entryFilter[advancedSearch][userIdIn]
      - in: query
        name: entryFilter[advancedSearch][value]
      - in: query
        name: entryFilter[advancedSearch][watermarkId]
      - in: query
        name: entryFilter[assetParamsIdsMatchAnd]
      - in: query
        name: entryFilter[assetParamsIdsMatchOr]
      - in: query
        name: entryFilter[categoriesFullNameIn]
      - in: query
        name: entryFilter[categoriesIdsEmpty]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: entryFilter[categoriesIdsMatchAnd]
      - in: query
        name: entryFilter[categoriesIdsMatchOr]
        description: All entries of the categories, excluding their child categories
      - in: query
        name: entryFilter[categoriesIdsNotContains]
      - in: query
        name: entryFilter[categoriesMatchAnd]
      - in: query
        name: entryFilter[categoriesMatchOr]
        description: All entries within these categories or their child categories
      - in: query
        name: entryFilter[categoriesNotContains]
      - in: query
        name: entryFilter[categoryAncestorIdIn]
        description: All entries within this categoy or in child categories
      - in: query
        name: entryFilter[createdAtGreaterThanOrEqual]
        description: This filter parameter should be in use for retrieving only entries
          which were created at Kaltura system after a specific time/date (standard
          timestamp format)
      - in: query
        name: entryFilter[createdAtLessThanOrEqual]
        description: This filter parameter should be in use for retrieving only entries
          which were created at Kaltura system before a specific time/date (standard
          timestamp format)
      - in: query
        name: entryFilter[creatorIdEqual]
      - in: query
        name: entryFilter[documentTypeEqual]
        description: 'Enum Type: `KalturaDocumentType`'
      - in: query
        name: entryFilter[documentTypeIn]
      - in: query
        name: entryFilter[durationGreaterThanOrEqual]
      - in: query
        name: entryFilter[durationGreaterThan]
      - in: query
        name: entryFilter[durationLessThanOrEqual]
      - in: query
        name: entryFilter[durationLessThan]
      - in: query
        name: entryFilter[durationTypeMatchOr]
      - in: query
        name: entryFilter[endDateGreaterThanOrEqualOrNull]
      - in: query
        name: entryFilter[endDateGreaterThanOrEqual]
      - in: query
        name: entryFilter[endDateLessThanOrEqualOrNull]
      - in: query
        name: entryFilter[endDateLessThanOrEqual]
      - in: query
        name: entryFilter[entitledUsersEditMatchAnd]
      - in: query
        name: entryFilter[entitledUsersEditMatchOr]
      - in: query
        name: entryFilter[entitledUsersPublishMatchAnd]
      - in: query
        name: entryFilter[entitledUsersPublishMatchOr]
      - in: query
        name: entryFilter[externalSourceTypeEqual]
        description: 'Enum Type: `KalturaExternalMediaSourceType`'
      - in: query
        name: entryFilter[externalSourceTypeIn]
      - in: query
        name: entryFilter[flavorParamsIdsMatchAnd]
      - in: query
        name: entryFilter[flavorParamsIdsMatchOr]
      - in: query
        name: entryFilter[freeText]
      - in: query
        name: entryFilter[groupIdEqual]
      - in: query
        name: entryFilter[hasMediaServerHostname]
      - in: query
        name: entryFilter[idEqual]
        description: This filter should be in use for retrieving only a specific entry
          (identified by its entryId)
      - in: query
        name: entryFilter[idIn]
        description: This filter should be in use for retrieving few specific entries
          (string should include comma separated list of entryId strings)
      - in: query
        name: entryFilter[idNotIn]
      - in: query
        name: entryFilter[isLive]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: entryFilter[isRecordedEntryIdEmpty]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: entryFilter[isRoot]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: entryFilter[lastPlayedAtGreaterThanOrEqual]
      - in: query
        name: entryFilter[lastPlayedAtLessThanOrEqual]
      - in: query
        name: entryFilter[limit]
      - in: query
        name: entryFilter[mediaDateGreaterThanOrEqual]
      - in: query
        name: entryFilter[mediaDateLessThanOrEqual]
      - in: query
        name: entryFilter[mediaTypeEqual]
        description: 'Enum Type: `KalturaMediaType`'
      - in: query
        name: entryFilter[mediaTypeIn]
      - in: query
        name: entryFilter[moderationStatusEqual]
        description: 'Enum Type: `KalturaEntryModerationStatus`'
      - in: query
        name: entryFilter[moderationStatusIn]
      - in: query
        name: entryFilter[moderationStatusNotEqual]
        description: 'Enum Type: `KalturaEntryModerationStatus`'
      - in: query
        name: entryFilter[moderationStatusNotIn]
      - in: query
        name: entryFilter[nameEqual]
        description: This filter should be in use for retrieving entries with a specific
          name
      - in: query
        name: entryFilter[nameLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[nameMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[nameMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[objectType]
      - in: query
        name: entryFilter[orderBy]
      - in: query
        name: entryFilter[parentEntryIdEqual]
      - in: query
        name: entryFilter[partnerIdEqual]
        description: This filter should be in use for retrieving only entries which
          were uploaded by/assigned to users of a specific Kaltura Partner (identified
          by Partner ID)
      - in: query
        name: entryFilter[partnerIdIn]
        description: This filter should be in use for retrieving only entries within
          Kaltura network which were uploaded by/assigned to users of few Kaltura
          Partners  (string should include comma separated list of PartnerIDs)
      - in: query
        name: entryFilter[partnerSortValueGreaterThanOrEqual]
      - in: query
        name: entryFilter[partnerSortValueLessThanOrEqual]
      - in: query
        name: entryFilter[redirectFromEntryId]
        description: The id of the original entry
      - in: query
        name: entryFilter[referenceIdEqual]
      - in: query
        name: entryFilter[referenceIdIn]
      - in: query
        name: entryFilter[replacedEntryIdEqual]
      - in: query
        name: entryFilter[replacedEntryIdIn]
      - in: query
        name: entryFilter[replacementStatusEqual]
        description: 'Enum Type: `KalturaEntryReplacementStatus`'
      - in: query
        name: entryFilter[replacementStatusIn]
      - in: query
        name: entryFilter[replacingEntryIdEqual]
      - in: query
        name: entryFilter[replacingEntryIdIn]
      - in: query
        name: entryFilter[rootEntryIdEqual]
      - in: query
        name: entryFilter[rootEntryIdIn]
      - in: query
        name: entryFilter[searchTextMatchAnd]
        description: 'This filter should be in use for retrieving specific entries
          while search match the input string within all of the following metadata
          attributes: name, description, tags, adminTags'
      - in: query
        name: entryFilter[searchTextMatchOr]
        description: 'This filter should be in use for retrieving specific entries
          while search match the input string within at least one of the following
          metadata attributes: name, description, tags, adminTags'
      - in: query
        name: entryFilter[sourceTypeEqual]
        description: 'Enum Type: `KalturaSourceType`'
      - in: query
        name: entryFilter[sourceTypeIn]
      - in: query
        name: entryFilter[sourceTypeNotEqual]
        description: 'Enum Type: `KalturaSourceType`'
      - in: query
        name: entryFilter[sourceTypeNotIn]
      - in: query
        name: entryFilter[startDateGreaterThanOrEqualOrNull]
      - in: query
        name: entryFilter[startDateGreaterThanOrEqual]
      - in: query
        name: entryFilter[startDateLessThanOrEqualOrNull]
      - in: query
        name: entryFilter[startDateLessThanOrEqual]
      - in: query
        name: entryFilter[statusEqual]
        description: 'Enum Type: `KalturaEntryStatus`This filter should be in use
          for retrieving only entries, at a specific {'
      - in: query
        name: entryFilter[statusIn]
        description: This filter should be in use for retrieving only entries, at
          few specific {
      - in: query
        name: entryFilter[statusNotEqual]
        description: 'Enum Type: `KalturaEntryStatus`This filter should be in use
          for retrieving only entries, not at a specific {'
      - in: query
        name: entryFilter[statusNotIn]
        description: This filter should be in use for retrieving only entries, not
          at few specific {
      - in: query
        name: entryFilter[tagsAdminTagsMultiLikeAnd]
      - in: query
        name: entryFilter[tagsAdminTagsMultiLikeOr]
      - in: query
        name: entryFilter[tagsAdminTagsNameMultiLikeAnd]
      - in: query
        name: entryFilter[tagsAdminTagsNameMultiLikeOr]
      - in: query
        name: entryFilter[tagsLike]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[tagsMultiLikeAnd]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[tagsMultiLikeOr]
        description: This filter should be in use for retrieving specific entries
      - in: query
        name: entryFilter[tagsNameMultiLikeAnd]
      - in: query
        name: entryFilter[tagsNameMultiLikeOr]
      - in: query
        name: entryFilter[totalRankGreaterThanOrEqual]
      - in: query
        name: entryFilter[totalRankLessThanOrEqual]
      - in: query
        name: entryFilter[typeEqual]
        description: 'Enum Type: `KalturaEntryType`'
      - in: query
        name: entryFilter[typeIn]
        description: This filter should be in use for retrieving entries of few {
      - in: query
        name: entryFilter[updatedAtGreaterThanOrEqual]
      - in: query
        name: entryFilter[updatedAtLessThanOrEqual]
      - in: query
        name: entryFilter[userIdEqual]
        description: This filter parameter should be in use for retrieving only entries,
          uploaded by/assigned to a specific user (identified by user Id)
      - in: query
        name: entryFilter[userIdIn]
      - in: query
        name: entryFilter[userIdNotIn]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Captionsearch
      - Captionassetitem
      - Action
      - SearchEntries
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---