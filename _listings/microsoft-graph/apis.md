---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Content
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Download The Contents Of A Drive Item
  x-api-slug: microsoft-graph
  description: Download the contents of a DriveItem Download the contents for a driveItem.
    Only driveItem with the file property can be downloaded.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{item-path}:/content
  tags: DownloadContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/microsoft-graph/medriverootitempathcontent-get-openapi.md
- name: Microsoft Graph Download The Contents Of A Drive Item
  x-api-slug: microsoft-graph
  description: Download the contents of a DriveItem Download the contents for a driveItem.
    Only driveItem with the file property can be downloaded.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{item-id}/content
  tags: DownloadContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/microsoft-graph/medriveitemsitemidcontent-get-openapi.md
- name: Microsoft Graph Download The Contents Of A Drive Item
  x-api-slug: microsoft-graph
  description: Download the contents of a DriveItem Download the contents for a driveItem.
    Only driveItem with the file property can be downloaded.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////drives/items/{item-id}/content
  tags: DownloadContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/microsoft-graph/drivesitemsitemidcontent-get-openapi.md
- name: Microsoft Graph Download The Contents Of A Drive Item
  x-api-slug: microsoft-graph
  description: Download the contents of a DriveItem Download the contents for a driveItem.
    Only driveItem with the file property can be downloaded.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{group-id}/drive/items/{item-id}/content
  tags: DownloadContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/microsoft-graph/groupsgroupiddriveitemsitemidcontent-get-openapi.md
- name: Microsoft Graph Upload Or Replace The Contents Of A Drive Item
  x-api-slug: microsoft-graph
  description: Upload or replace the contents of a driveItem The simple upload API
    allows you to provide the contents of a new file or update the contents of an
    existing file in a single API call. This method only supports files up to 4MB
    in size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{parent-id}:/{filename}:/content
  tags: Upload, Or, ReplaceContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/microsoft-graph/medriveitemsparentidfilenamecontent-put-openapi.md
- name: Microsoft Graph Upload Or Replace The Contents Of A Drive Item
  x-api-slug: microsoft-graph
  description: Upload or replace the contents of a driveItem The simple upload API
    allows you to provide the contents of a new file or update the contents of an
    existing file in a single API call. This method only supports files up to 4MB
    in size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/root:/{parent-path}/{filename}:/content
  tags: Upload, Or, ReplaceContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/microsoft-graph/medriverootparentpathfilenamecontent-put-openapi.md
- name: Microsoft Graph Upload Or Replace The Contents Of A Drive Item
  x-api-slug: microsoft-graph
  description: Upload or replace the contents of a driveItem The simple upload API
    allows you to provide the contents of a new file or update the contents of an
    existing file in a single API call. This method only supports files up to 4MB
    in size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/items/{parent-id}/children/{filename}/content
  tags: Upload, Or, ReplaceContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/microsoft-graph/medriveitemsparentidchildrenfilenamecontent-put-openapi.md
- name: Microsoft Graph Upload Or Replace The Contents Of A Drive Item
  x-api-slug: microsoft-graph
  description: Upload or replace the contents of a driveItem The simple upload API
    allows you to provide the contents of a new file or update the contents of an
    existing file in a single API call. This method only supports files up to 4MB
    in size.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/drive/items/{parent-id}/children/{filename}/content
  tags: Upload, Or, ReplaceContents, OfDrive, Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/microsoft-graph/groupsiddriveitemsparentidchildrenfilenamecontent-put-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Content
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---