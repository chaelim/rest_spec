# Delete thumbnailSet

Delete thumbnailSet.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
DELETE /drive/root/thumbnails/<id>
DELETE /drive/items/<id>/thumbnails/<id>
DELETE /drives/<id>/root/thumbnails/<id>

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
Do not supply a request body for this method.


### Response
If successful, this method returns `204, No Content` response code. It does not return anything in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "delete_thumbnailset"
}-->
```http
DELETE https://graph.microsoft.com/v1.0/drive/root/thumbnails/<id>
```
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false
} -->
```http
HTTP/1.1 204 No Content
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Delete thumbnailSet",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->