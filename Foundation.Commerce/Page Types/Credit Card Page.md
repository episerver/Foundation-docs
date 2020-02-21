# Credit Card Page
"Manage credit cards"

![Credit card page](Screenshots/Credit%20Card%20Page%20-%20icon.png)

This page lets you perform all activities related to credit cards.


## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page  Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main body** *(`MainBody`)* | XhtmlString | Provides an rich-text area for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**B2B** *(`B2B`)* | Boolean | Check box
**MetaContentType** *(`Content Type`)* | LongString(>255) | Available in the Metadata tab
**Industry** *(`Industry`)* | LongString(>255) | Available in the Metadata tab
**AuthorMetaData** *(`Author`)* | LongString(>255) | Available in the Metadata tab

** **
![Credit card page](Screenshots/Credit%20Card%20Page%20-%20Content%20tab.png)width="50%"/>

## Technical Information

### Category
`Commerce`

### Inherits
[FoundationPageData](Foundation%20Page%20Data.md), IDisableOPE

### Restrictions
The Checkout Page is not available in edit view by default. To enable it, go to Admin view > Content type > [Commerce] Checkout Page > Settings and select the **Available in edit view** check box.

## Preview
<img src="Screenshots/Credit%20Card%20Page%20-%20OPE.png?raw=true" alt="Preview of Credit Card Page" width="100%"/>
