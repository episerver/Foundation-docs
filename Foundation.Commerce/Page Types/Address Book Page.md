# Address Book Page
"Manages address book for customer."

![Address book page](Screenshots/Address%20Book%20Page%20-%20icon.png)

This page type lets customers manage and edit their billing and shipping addresses.


## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page  Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main body** *(`MainBody`)* | XhtmlString | Provides an rich-text area for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**MetaContentType** *(`Content Type`)* | LongString(>255) |
**Industry** *(`Industry`)* | LongString(>255) |
**AuthorMetaData** *(`Author`)* | LongString(>255) |


** **
![Address book page](Screenshots/Address%20Book%20Page%20-%20Content%20tab.png)

## Technical Information

### Category
`Commerce`

### Inherits
[FoundationPageData](Foundation%20Page%20Data.md)

### Restrictions
The Checkout Page is not available in edit view by default. To enable it, go to Admin view > Content type > [Commerce] Checkout Page > Settings and select the **Available in edit view** check box.

## Preview
![Address book page](Screenshots/Address%20Book%20Page%20-%20Preview.png)
