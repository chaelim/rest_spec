# Get MailFolder

Retrieve the properties and relationships of mailfolder object.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
GET /users/<objectId>/MailFolders/<Id>
GET /drive/root/createdByUser/MailFolders/<Id>
GET /drive/root/lastModifiedByUser/MailFolders/<Id>
```
### Optional query parameters
|Name|Value|Description|
|:---------------|:--------|:-------|
|$count|none|The count of related entities can be requested by specifying the $count query option.|
|$expand|string|Comma-separated list of relationships to expand and include in the response. See relationships table of [MailFolder](../resources/mailfolder.md) object for supported names. |
|$select|string|Comma-separated list of properties to include in the response.|

### Request headers
| Name       | Type | Description|
|:-----------|:------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
Do not supply a request body for this method.
### Response
If successful, this method returns a `200 OK` response code and [MailFolder](../resources/mailfolder.md) object in the response body.
### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "get_mailfolder"
}-->
```http
GET /users/<objectId>/MailFolders/<Id>
```
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "microsoft.graph.mailfolder"
} -->
```http
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 130

{
  "ParentFolderId": "ParentFolderId-value",
  "DisplayName": "DisplayName-value",
  "ChildFolderCount": 99,
  "Id": "Id-value"
}
```

<!-- uuid: 7b985f1a-e3d9-4a53-962f-8cb3eb5ec020
2015-10-25 14:25:33 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Get MailFolder",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->