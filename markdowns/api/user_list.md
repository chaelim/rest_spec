# List User

Retrieve a list of user objects.
### HTTP request
```http
GET /users
```
### Optional query parameters
You can use the [OData query parameters](odata-optional-query-parameters.md) to restrict the shape of the objects returned from this call.
### Request headers
| Name       | Type | Description|
|:-----------|:------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP headers used by the API could be displayed.|

### Request body
Do not supply a request body for this method.
### Response
If successful, this method returns a `200 OK` response code and collection of [User](../resources/user.md) objects in the response body.
### Example
##### Response
Here is an example of the response.
```json
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 2047
{
  "accountEnabled": true,
  "assignedLicenses": [
    {
    }
  ],
  "assignedPlans": [
    {
    }
  ],
  "city": "city-value",
  "country": "country-value",
  "department": "department-value",
  "dirSyncEnabled": true,
  "displayName": "displayName-value",
  "facsimileTelephoneNumber": "facsimileTelephoneNumber-value",
  "givenName": "givenName-value",
  "immutableId": "immutableId-value",
  "jobTitle": "jobTitle-value",
  "lastDirSyncTime": "datetime-value",
  "mail": "mail-value",
  "mailNickname": "mailNickname-value",
  "mobile": "mobile-value",
  "onPremisesSecurityIdentifier": "onPremisesSecurityIdentifier-value",
  "otherMails": [
    "otherMails-value"
  ],
  "passwordPolicies": "passwordPolicies-value",
  "passwordProfile": {
  },
  "physicalDeliveryOfficeName": "physicalDeliveryOfficeName-value",
  "postalCode": "postalCode-value",
  "preferredLanguage": "preferredLanguage-value",
  "provisionedPlans": [
    {
    }
  ],
  "provisioningErrors": [
    {
    }
  ],
  "proxyAddresses": [
    "proxyAddresses-value"
  ],
  "sipProxyAddress": "sipProxyAddress-value",
  "state": "state-value",
  "streetAddress": "streetAddress-value",
  "surname": "surname-value",
  "telephoneNumber": "telephoneNumber-value",
  "thumbnailPhoto": "thumbnailPhoto-value",
  "usageLocation": "usageLocation-value",
  "userPrincipalName": "userPrincipalName-value",
  "userType": "userType-value",
  "MailboxGuid": "MailboxGuid-value",
  "AboutMe": "AboutMe-value",
  "Alias": "Alias-value",
  "Birthday": "datetime-value",
  "HireDate": "datetime-value",
  "Interests": [
    "Interests-value"
  ],
  "MySite": "MySite-value",
  "PastProjects": [
    "PastProjects-value"
  ],
  "PreferredName": "PreferredName-value",
  "PrincipalName": "PrincipalName-value",
  "Responsibilities": [
    "Responsibilities-value"
  ],
  "Schools": [
    "Schools-value"
  ],
  "Skills": [
    "Skills-value"
  ],
  "Tags": [
    "Tags-value"
  ],
  "objectType": "objectType-value",
  "objectId": "objectId-value",
  "deletionTimestamp": "datetime-value"
}
```

<!-- uuid: 029c2987-1310-4ff9-882c-fdb57063122a
2015-10-09 18:31:38 UTC -->