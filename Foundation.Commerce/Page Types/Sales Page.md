# Sales Page
"Show all items on sale."

![Sales](Screenshots/Sales%20Page%20-%20icon.png)

This is a page type that...


## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page  Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main body** *(`MainBody`)* | XhtmlString | Provides an rich-text area for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Number of products** *(`NumberOfProducts`)* | Integer | Number of displayed products.
**Number of products per page** *(`PageSize`)* | Integer | Number of displayed products per page.
**Manual inclusion** *(`ManualInclusion`)* | IList<ContentReference> | Gets or sets the list of included catalog items (catalogs, categories or entries).
**Manual inclusion ordering** *(`ManualInclusionOrdering`)* | String | The manual inclusion products based on the Manual Inclusion Ordering.
**Manual exclusion** *(`ManualExclusion`)* | IList<ContentReference>  | Gets or sets the list of excluded catalog items (catalogs, categories or entries).

** **
![Sales](Screenshots/Sales%20Page%20-%20Content%20tab.png)

## Technical Information

### Category
`Commerce`

### Inherits
BaseInclusionExclusionPage

### Restrictions
This page is not available in edit view by default. To enable it, go to Admin view > Content type > [Commerce] Checkout Page > Settings and select the **Available in edit view** check box.

## Preview
![Sales](Screenshots/Sales%20Page%20-%20Preview.png)
