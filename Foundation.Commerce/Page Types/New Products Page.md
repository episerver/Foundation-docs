# New Products Page
"Show the top new products by sorted by the creation date"

<img src="Screenshots/New%20Products%20Page%20-%20icon.png?raw=true" alt="New Products Page icon" width="40%" />

This is a page type that allows for creating a listing of products marked as "New arrival" in the product's *Content* tab.

<img src="Screenshots/Product%20-%20Content%20tab%20-%20New%20arrival.png?raw=true" alt="New Products Page icon" width="30%" />

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page  Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main body** *(`MainBody`)* | XhtmlString | Provides an rich-text area for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable, drag-and-drop interface for placing media, blocks, or other content on the page.
**Number of products** *(`NumberOfProducts`)* | Integer | Determines the maximum number of new products to show in the list.
**Number of products per page** *(`PageSize`)* | Integer | Determines the maximum number of new products to show per page.
**Allow paging** *(`AllowPaging`)* | Boolean | If true, adds, if necessary, paging controls to browse new products on the page. The paging functionality is used if the value of *Number of products per page* property is less than the value of *Number of products*, and the number of products to show exceeds the *Number of products per page*.
**Manual inclusion** *(`ManualInclusion`)* | ContentReferenceList | Allows for the manual inclusion of products or product categories in the listing, regardless of a product's "New arrival" status.
**Manual inclusion ordering** *(`ManualInclusionOrdering`)* | String | Controls where in the list of new products the manually included products appear. The options are **Beginning**, **End** and **Random**.
**Manual exclusion** *(`ManualExclusion`)* | ContentReferenceList | Allows for the manual exclusion of products or product categories from the listing.

** **
<img src="Screenshots/New Products Page%20-%20Content%20tab.png?raw=true" alt="Preview of Search Results Page" width="50%"/>

## Technical Information

### Category
`Commerce`

### Inherits
BaseInclusionExclusionPage

### Restrictions
* none

## Preview
<img src="Screenshots/New Products Page -%20OPE.png?raw=true" alt="Preview of New Products Page" width="100%"/>
