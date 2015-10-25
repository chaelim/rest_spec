# Posts: Reply


### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
POST /groups/<objectId>/Threads/<Id>/Reply
POST /groups/<objectId>/Conversations/<Id>/Threads/<Id>/Reply
POST /users/<objectId>/JoinedGroups/<objectId>/Threads/<Id>/Reply

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
In the request body, provide a JSON object with the following parameters.

| Parameter	   | Type	|Description|
|:---------------|:--------|:----------|
|Post|Post||

### Response
If successful, this method returns `200, OK` response code. It does not return anything in the response body.

### Example
Here is an example of how to call this API.
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "posts_reply"
}-->
```http
POST /groups/<objectId>/Threads/<Id>/Reply
Content-type: application/json
Content-length: 1141

{
  "Post": {
    "Body": {
      "ContentType": "ContentType-value",
      "Content": "Content-value"
    },
    "ReceivedDateTime": "datetime-value",
    "HasAttachments": true,
    "From": {
      "EmailAddress": {
        "Name": "Name-value",
        "Address": "Address-value"
      }
    },
    "Sender": {
      "EmailAddress": {
        "Name": "Name-value",
        "Address": "Address-value"
      }
    },
    "ConversationThreadId": "ConversationThreadId-value",
    "ConversationId": "ConversationId-value",
    "NewParticipants": [
      {
        "EmailAddress": {
          "Name": "Name-value",
          "Address": "Address-value"
        }
      }
    ],
    "ChangeKey": "ChangeKey-value",
    "Categories": [
      "Categories-value"
    ],
    "CreatedDateTime": "datetime-value",
    "LastModifiedDateTime": "datetime-value",
    "Id": "Id-value",
    "Attachments": [
      {
        "Name": "Name-value",
        "ContentType": "ContentType-value",
        "Size": 99,
        "IsInline": true,
        "LastModifiedDateTime": "datetime-value",
        "Id": "Id-value"
      }
    ],
    "InReplyTo": {
    }
  }
}
```

##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "microsoft.graph.none"
} -->
```http
HTTP/1.1 200 OK
```

<!-- uuid: 93713206-fa02-48df-97bb-72304b6d766e
2015-10-25 12:56:09 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Posts: Reply",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->