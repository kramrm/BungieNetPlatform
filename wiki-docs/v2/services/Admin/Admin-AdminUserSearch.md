<span class="wiki-builder">This page was generated with Wiki Builder. Do not change the format!</span>

## Info


* **URI:** [[/Admin/Member/Search/|https://www.bungie.net/Platform/Admin/Member/Search/]]
* **Basepath:** https://www.bungie.net/Platform
* **Method:** GET
* **Service:** [[Admin|Endpoints#Admin]]
* **Permissions:** None
* **Officially Supported:** No

## Parameters
### Path Parameters
None

### Query String Parameters
Name | Schema | Required | Description
---- | ------ | -------- | -----------
q | string | No | 

## Example
### Request
GET https://www.bungie.net/Platform/Admin/Member/Search/

### Response
PlatformErrorCode: 200
```javascript
{
    // Type: [#/components/schemas/Admin.AdminUserSearch]
    "Response": null,
    // Type: [[PlatformErrorCodes|Exceptions-PlatformErrorCodes]]:Enum
    "ErrorCode": 0,
    // Type: integer:int32
    "ThrottleSeconds": 0,
    // Type: string
    "ErrorStatus": "",
    // Type: string
    "Message": "",
    // Type: Dictionary&lt;string,string&gt;
    "MessageData": {
        "{string}": ""
    },
    // Type: object
}

```

## References
