---
name: Kentico Cloud
x-slug: kentico-cloud
description: 'Kentico Cloud is the #1 CMS that enables digital teams to collaborate
  quickly to create engaging personalized experiences across any device. Free 30-day
  trial!'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
x-kinRank: "7"
x-alexaRank: "369033"
tags: Content
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/apis.md
specificationVersion: "0.14"
apis:
- name: Kentico Cloud - View a content item by ID
  x-api-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5-get
  description: Retrieve metadata information about a content item specified by its
    internal ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/items3120ec15a4a247ec8ccdc85ac8ac5ba5-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/items3120ec15a4a247ec8ccdc85ac8ac5ba5-get-openapi.md
- name: Kentico Cloud - Update a content item by ID
  x-api-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5-put
  description: Update an existing content item specified by its internal ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/items3120ec15a4a247ec8ccdc85ac8ac5ba5-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/items3120ec15a4a247ec8ccdc85ac8ac5ba5-put-openapi.md
- name: Kentico Cloud - Delete a content item by ID
  x-api-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5-delete
  description: Delete a content item specified by its internal ID. Note that deleting
    a content item deletes all of its language variants as well.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/items3120ec15a4a247ec8ccdc85ac8ac5ba5-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/items3120ec15a4a247ec8ccdc85ac8ac5ba5-delete-openapi.md
- name: Kentico Cloud - View a content item by codename
  x-api-slug: itemscodenameon-roasts-get
  description: Retrieve metadata information about a content item specified by its
    codename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemscodenameon-roasts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemscodenameon-roasts-get-openapi.md
- name: Kentico Cloud - Update a content item by codename
  x-api-slug: itemscodenameon-roasts-put
  description: Update an existing content item specified by its codename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemscodenameon-roasts-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemscodenameon-roasts-put-openapi.md
- name: Kentico Cloud - Delete a content item by codename
  x-api-slug: itemscodenameon-roasts-delete
  description: |-
    Delete a content item specified by its codename.

    Note that deleting a content item deletes all of its language variants as well.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemscodenameon-roasts-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemscodenameon-roasts-delete-openapi.md
- name: Kentico Cloud - Adding localized content
  x-api-slug: itemsexternalidextcafebrno59713variantscodenameenus-put
  description: "Add content in a specific language to your new content item by performing
    an upsert.\r\n\r\n* In the request URL, you need to specify the content item you
    are importing to (for example, `/items/external-id/ext-cafe-brno-59713`) and the
    language of the variant (for example, `/variants/codename/en-US`).\r\n* The request
    body must contain the `elements` object in which you specify only the content
    elements you want to update. Omitted elements will remain unchanged.\r\n\r\nSee
    <https://developer.kenticocloud.com/docs/importing-to-kentico-cloud#section-2-adding-localized-content>
    for more details."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemsexternalidextcafebrno59713variantscodenameenus-put-openapi.md
- name: Kentico Cloud - Creating a content item
  x-api-slug: itemsexternalidextcafebrno59713-put
  description: "One of the ways to import content to your project is to send a PUT
    request to the `<cmApiUrl>/items/external-id/<your item ID>` endpoint.\r\n\r\nIn
    the body of the request, specify these properties:\r\n\r\n* `name` \u2013 string
    with a display name of the new content item.\r\n* `type` \u2013 reference to a
    content type.\r\n* (Optional) `sitemap_locations` \u2013 array of references to
    sitemap locations.\r\n\r\nSee <https://developer.kenticocloud.com/docs/importing-to-kentico-cloud#section-1-creating-a-content-item>
    for more details."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemsexternalidextcafebrno59713-put-openapi.md
- name: Kentico Cloud - Displaying the right content
  x-api-slug: 8d15591466744f1781043b1c5c2b37e4itemspartner-promotion-get
  description: |-
    Retrieve one personalization variant you want to display. To learn more about retrieving content, consult the [Delivery API reference](https://developer.kenticocloud.com/reference#delivery-api).

    See <https://developer.kenticocloud.com/docs/personalizing-content#section-displaying-the-right-content> for more examples.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/8d15591466744f1781043b1c5c2b37e4itemspartner-promotion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/8d15591466744f1781043b1c5c2b37e4itemspartner-promotion-get-openapi.md
- name: Kentico Cloud - Getting localized content items
  x-api-slug: 975bf280fd91488c994c2f04416e5ee3itemson-roasts-get
  description: |-
    Get a content item in a specific language variant by using the `language` parameter.

    See [Getting localized content items](https://developer.kenticocloud.com/docs/localization#section-getting-localized-content-items) for more details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/975bf280fd91488c994c2f04416e5ee3itemson-roasts-get-openapi.md
- name: Kentico Cloud - View a content Item by external ID
  x-api-slug: itemsexternalid59713-get
  description: Retrieve metadata information about a content item specified by its
    external ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemsexternalid59713-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemsexternalid59713-get-openapi.md
- name: Kentico Cloud - Update a content item by external ID
  x-api-slug: itemsexternalid59713-put
  description: "Add a new content item or update an existing content item specified
    by its external ID.\r\n\r\n**Note:** If no content item with the specified external
    ID exists in the project, the system will try to create one. For existing content
    items, the API updates the content item's name and sitemap locations.\r\nYou can
    also specify the external ID when [adding content items](https://developer.kenticocloud.com/v1/reference#content-management-api-add-item)
    via the POST method."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/itemsexternalid59713-put-openapi.md
- name: Kentico Cloud - View a content type
  x-api-slug: 975bf280fd91488c994c2f04416e5ee3typescoffee-get
  description: |-
    Retrieve a specific content type from your project by specifying its codename.

    See <https://developer.kenticocloud.com/v1/reference#view-a-content-type> for more details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/975bf280fd91488c994c2f04416e5ee3typescoffee-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/975bf280fd91488c994c2f04416e5ee3typescoffee-get-openapi.md
- name: Kentico Cloud - List content items
  x-api-slug: items-get
  description: Retrieve a dynamically paginated list of content items.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/items-get-openapi.md
- name: Kentico Cloud - Add a content item
  x-api-slug: items-post
  description: |-
    Create a new content item based on a specific content type. Content items do NOT contain any content themselves, but serve as wrappers for individual language variants.

    See <https://developer.kenticocloud.com/v1/reference#content-management-api-add-item> for details about adding content to a specific language variant.

    If you are importing content from a different system and want to use the same identifiers for your content as in the previous system, you can use the `external_id` body attribute to set a custom identifier for the new content item.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/items-post-openapi.md
- name: Kentico Cloud - List content types
  x-api-slug: 975bf280fd91488c994c2f04416e5ee3types-get
  description: |-
    Retrieve a list of content types in your project.

    See <https://developer.kenticocloud.com/v1/reference#list-content-types> for more details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/975bf280fd91488c994c2f04416e5ee3types-get-openapi.md
- name: Kentico Cloud - Validate project content
  x-api-slug: validate-post
  description: "Check your project's content items for issues, such as:\r\n\r\n* Content
    elements are [referencing](https://developer.kenticocloud.com/v1/reference#content-management-api-reference-object)
    non-existing objects.\r\n* Values of certain content elements do not meet the
    limitations set in content types.\r\n\r\nUse the endpoint after successfully importing
    content to your project."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/validate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/validate-post-openapi.md
- name: Kentico Cloud - View a content type element
  x-api-slug: 975bf280fd91488c994c2f04416e5ee3typescoffeeelementsprocessing-get
  description: |-
    Retrieve a specific content type element by specifying its codename and its parent content type.

    See <https://developer.kenticocloud.com/v1/reference#view-a-content-type-element> for more details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/975bf280fd91488c994c2f04416e5ee3typescoffeeelementsprocessing-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kentico-cloud/975bf280fd91488c994c2f04416e5ee3typescoffeeelementsprocessing-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://kenticocloud.com/rss
- type: x-github
  url: https://github.com/kentico
- type: x-postman-collection
  url: https://app.getpostman.com/run-collection/519dd5697b81ba7336a3
- type: x-website
  url: https://kenticocloud.com/
- type: x-api-gallery
  url: http://kaltura.api.gallery.streamdata.io
- type: x-api-stack
  url: http://kentico.cloud.stack.network
- type: x-blog
  url: https://kenticocloud.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/kentico
- type: x-partners
  url: https://kenticocloud.com/partners
- type: x-pricing
  url: https://kenticocloud.com/pricing
- type: x-twitter
  url: https://twitter.com/kenticocloud
- type: x-website
  url: https://kenticocloud.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---