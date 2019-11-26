# New Products Page
"Show the top new products by sorted by the creation date"

<img src="../Screenshots/New%20Products%20Page%20-%20icon.png?raw=true" alt="New Products Page icon" width="40%" />

This is a page type that allows for creating a listing of products marked as "New arrival" in the product's *Content* tab.

<img src="../Screenshots/Product - Content tab - New arrival.png?raw=true" alt="New Products Page icon" width="30%" />

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page  Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main body** *(`MainBody`)* | XhtmlString | Provides an rich-text area for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Number of products** *(`NumberOfProducts`)* | Integer | Determines the maximum number of new products to show in the listing of new products.
**Number of products per page** *(`PageSize`)* | Integer | Determines the maximum number of new products to show per page.
**Allow paging** *(`AllowPaging`)* | Boolean | When selected, adds, if necessary, paging controls to browse the new products listed on this page. The paging functionality will be used if the value of *Number of products per page* property is less than the value of *Number of products*, and there are a greater number of products to show than the *Number of products per page*.
**Manual inclusion** *(`ManualInclusion`)* | ContentReferenceList | Allows for manually including products or product categories to be included in the listing, regardless of the "New arrival" status of a product.
**Manual inclusion ordering** *(`ManualInclusionOrdering`)* | String | Controls where in the list of new products the manually included products should be. The options are **Beginning**, **End** and **Random**.
**Manual exclusion** *(`ManualExclusion`)* | ContentReferenceList | Allows for manually excluding products or product categories to be excluded from the listing.

** **
<img src="../Screenshots/New Products Page%20-%20Content%20tab.png?raw=true" alt="Preview of Search Results Page" width="50%"/>

## Technical Information

### Category
`Commerce`

### Inherits
[Landing Page](#)

### Restrictions
* none


## Preview
<img src="../Screenshots/New Products Page -%20OPE.png?raw=true" alt="Preview of New Products Page" width="100%"/>