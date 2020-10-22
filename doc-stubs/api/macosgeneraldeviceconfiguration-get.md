---
title: "Get macOSGeneralDeviceConfiguration"
description: "Read the properties and relationships of a macOSGeneralDeviceConfiguration object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get macOSGeneralDeviceConfiguration
Namespace: microsoft.graph

Read the properties and relationships of a [macOSGeneralDeviceConfiguration](../resources/macosgeneraldeviceconfiguration.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from most to least privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET ** Entity URI for microsoft.graph.macOSGeneralDeviceConfiguration not found
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a [macOSGeneralDeviceConfiguration](../resources/macosgeneraldeviceconfiguration.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_macosgeneraldeviceconfiguration"
}
-->
``` http
GET https://graph.microsoft.com/beta** Entity URI for microsoft.graph.macOSGeneralDeviceConfiguration not found
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.macOSGeneralDeviceConfiguration"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": {
    "@odata.type": "#microsoft.graph.macOSGeneralDeviceConfiguration",
    "id": "b2963dd3-3dd3-b296-d33d-96b2d33d96b2",
    "lastModifiedDateTime": "String (timestamp)",
    "roleScopeTagIds": [
      "String"
    ],
    "supportsScopeTags": "Boolean",
    "deviceManagementApplicabilityRuleOsEdition": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsEdition"
    },
    "deviceManagementApplicabilityRuleOsVersion": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsVersion"
    },
    "deviceManagementApplicabilityRuleDeviceMode": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleDeviceMode"
    },
    "createdDateTime": "String (timestamp)",
    "description": "String",
    "displayName": "String",
    "version": "Integer",
    "compliantAppsList": [
      {
        "@odata.type": "microsoft.graph.appListItem"
      }
    ],
    "compliantAppListType": "String",
    "emailInDomainSuffixes": [
      "String"
    ],
    "passwordBlockSimple": "Boolean",
    "passwordExpirationDays": "Integer",
    "passwordMinimumCharacterSetCount": "Integer",
    "passwordMinimumLength": "Integer",
    "passwordMinutesOfInactivityBeforeLock": "Integer",
    "passwordMinutesOfInactivityBeforeScreenTimeout": "Integer",
    "passwordPreviousPasswordBlockCount": "Integer",
    "passwordRequiredType": "String",
    "passwordRequired": "Boolean",
    "passwordMaximumAttemptCount": "Integer",
    "passwordMinutesUntilFailedLoginReset": "Integer",
    "keychainBlockCloudSync": "Boolean",
    "airPrintBlocked": "Boolean",
    "airPrintForceTrustedTLS": "Boolean",
    "airPrintBlockiBeaconDiscovery": "Boolean",
    "safariBlockAutofill": "Boolean",
    "cameraBlocked": "Boolean",
    "iTunesBlockMusicService": "Boolean",
    "spotlightBlockInternetResults": "Boolean",
    "keyboardBlockDictation": "Boolean",
    "definitionLookupBlocked": "Boolean",
    "appleWatchBlockAutoUnlock": "Boolean",
    "iTunesBlockFileSharing": "Boolean",
    "iCloudBlockDocumentSync": "Boolean",
    "iCloudBlockMail": "Boolean",
    "iCloudBlockAddressBook": "Boolean",
    "iCloudBlockCalendar": "Boolean",
    "iCloudBlockReminders": "Boolean",
    "iCloudBlockBookmarks": "Boolean",
    "iCloudBlockNotes": "Boolean",
    "airDropBlocked": "Boolean",
    "passwordBlockModification": "Boolean",
    "passwordBlockFingerprintUnlock": "Boolean",
    "passwordBlockAutoFill": "Boolean",
    "passwordBlockProximityRequests": "Boolean",
    "passwordBlockAirDropSharing": "Boolean",
    "softwareUpdatesEnforcedDelayInDays": "Integer",
    "softwareUpdatesForceDelayed": "Boolean",
    "updateDelayPolicy": "String",
    "contentCachingBlocked": "Boolean",
    "iCloudBlockPhotoLibrary": "Boolean",
    "screenCaptureBlocked": "Boolean",
    "classroomAppBlockRemoteScreenObservation": "Boolean",
    "classroomAppForceUnpromptedScreenObservation": "Boolean",
    "classroomForceAutomaticallyJoinClasses": "Boolean",
    "classroomForceRequestPermissionToLeaveClasses": "Boolean",
    "classroomForceUnpromptedAppAndDeviceLock": "Boolean",
    "iCloudBlockActivityContinuation": "Boolean",
    "privacyAccessControls": [
      {
        "@odata.type": "microsoft.graph.macOSPrivacyAccessControlItem"
      }
    ]
  }
}
```
