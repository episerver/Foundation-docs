# Sales Page
"Show all items on sale."

![Sales](Screenshots/Sales%20Page%20-%20icon.png)

This page type shows all items on sale. You can define the overall number of products, the number of products to be displayed per page, the products to be included or excluded and your product's order. 


## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page  Properties*](../../Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main body** *(`MainBody`)* | XhtmlString | Provides an rich-text area for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable, drag-and-drop interface for placing media, blocks, or other content on the page.
**Number of products** *(`NumberOfProducts`)* | Integer | Determines the maximum number of products to show in the list.
**Number of products per page** *(`PageSize`)* | Integer | Determines the maximum number of products to show per page.
**Allow paging** *(`AllowPaging`)* | Boolean | If true, adds, if necessary, paging controls to browse products on the page. The paging functionality is used if the value of *Number of products per page* property is less than the value of *Number of products*, and the number of products to show exceeds the *Number of products per page*.
**Manual inclusion** *(`ManualInclusion`)* | ContentReferenceList | Allows for the manual inclusion of products or product categories in the listing.
**Manual inclusion ordering** *(`ManualInclusionOrdering`)* | String | Controls where in the list of products the manually included products appear. The options are **Beginning**, **End** and **Random**.
**Manual exclusion** *(`ManualExclusion`)* | ContentReferenceList | Allows for the manual exclusion of products or product categories from the listing.


** **
![Sales](Screenshots/Sales%20Page%20-%20Content%20tab.png)

## Technical Information

### Category
`Commerce`

### Inherits
BaseInclusionExclusionPage

### Restrictions
* none

## Preview
![Sales](Screenshots/Sales%20Page%20-%20Preview.png)
