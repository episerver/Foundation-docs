# Two Column Landing Page
"Two column landing page with properties to determine column size"

<img src="../Screenshots/Two%20Column%20Landing%20Page%20-%20icon.png?raw=true" alt="Two Column Landing Page icon" width="40%" />

An open-format *Page Type* designed for a variety of page types including marketing landing pages, product promotion pages, etc. Consists of a top content area, main body, main content area and right content area.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page  Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Top content area** *(`TopContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Main body** *(`MainBody`)* | XhtmlString | Provides an rich-text area for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Right content area** *(`RightHandContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Left column** *(`MainContentAreaColumn`)* | Integer | Configures the *Main content area* (or left) column width in Bootstrap column integer values. 
**Right column** *(`RightHandContentAreaColumn`)* | Integer | Configures the *Right content area* column width in Bootstrap column integer values.


** **
<img src="../Screenshots/Two%20Column%20Landing%20Page%20-%20Content%20tab.png?raw=true" alt="Preview of Two Column Landing Page" width="50%"/>

## Technical Information

### Category
`Content`

### Inherits
[Landing Page](#)

### Restrictions
* The combined column width of *Left column* and *Right column* must equal 12. The default valu for each column width is 6.

## Preview
<img src="../Screenshots/Two%20Column%20Landing%20Page%20-%20OPE.png?raw=true" alt="Preview of Two Column Landing Page" width="100%"/>