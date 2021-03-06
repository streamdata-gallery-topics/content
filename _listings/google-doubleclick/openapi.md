---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 1
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/contentCategories:
    get:
      summary: Get Content Categories
      description: Retrieves a list of content categories, possibly filtered. This
        method supports paging.
      operationId: dfareporting.contentCategories.list
      x-api-path-slug: userprofilesprofileidcontentcategories-get
      parameters:
      - in: query
        name: ids
        description: Select only content categories with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for objects by name or ID
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Content Category
    patch:
      summary: Get Content Category
      description: Updates an existing content category. This method supports patch
        semantics.
      operationId: dfareporting.contentCategories.patch
      x-api-path-slug: userprofilesprofileidcontentcategories-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Content category ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Content Category
    post:
      summary: Create Content Category
      description: Inserts a new content category.
      operationId: dfareporting.contentCategories.insert
      x-api-path-slug: userprofilesprofileidcontentcategories-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Content Category
    put:
      summary: Update Content Category
      description: Updates an existing content category.
      operationId: dfareporting.contentCategories.update
      x-api-path-slug: userprofilesprofileidcontentcategories-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Content Category
  /userprofiles/{profileId}/contentCategories/{id}:
    delete:
      summary: Delete Content Category
      description: Deletes an existing content category.
      operationId: dfareporting.contentCategories.delete
      x-api-path-slug: userprofilesprofileidcontentcategoriesid-delete
      parameters:
      - in: path
        name: id
        description: Content category ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Content Category
    get:
      summary: Get Content Category
      description: Gets one content category by ID.
      operationId: dfareporting.contentCategories.get
      x-api-path-slug: userprofilesprofileidcontentcategoriesid-get
      parameters:
      - in: path
        name: id
        description: Content category ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Content Category
---