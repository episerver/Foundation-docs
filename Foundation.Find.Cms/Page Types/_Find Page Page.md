# Locations List Page
"Used to disploay of list of all locations"

<img src="Screenshots/Locations%20List%20Page%20-%20icon.png?raw=true" alt="<PAGETYPE> icon" width="40%" />

A Locations List Page gathers all [Location Item Pages](./Location%20Item%20Page.md) in one list. The user can then filter the list using various filters, such as temperature, tags, distance from current location, etc.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main body** *(`MainBody`)* | XhtmlString | Provides a rich-text editor for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Filter area** *(`FilterArea`)* | ContentArea | Provides a drag-and-drop interface for entering blocks of type Filter. These filters are provided as facets on the page for further narrowing down the listing of locations.

** **

<img src="Screenshots/Locations%20List%20Page%20-%20Content%20tab.png?raw=true" alt="Content tab of the Locations List Page in All-properties view" width="50%"/>

## Technical Information

### Category
`Location`

### Inherits
[Landing Page](#)

### Restrictions
* Only pages of type [Location Item Page](./Location%20Item%20Page.md) can be created as a child page of this page type.

## Preview
<img src="Screenshots/Locations%20List%20Page%20-%20OPE.png?raw=true" alt="Preview of Blog Item Page" width="100%"/>
