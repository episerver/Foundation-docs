# Tags Page
"Used to define a Tag"

<img src="../Screenshots/Tags%20Page%20-%20icon.png?raw=true" alt="Tags Page icon" width="40%" />

The *Tags Page* is used for presenting a collection of all pages of type [*Location Item Page*](./Location%20Item%20Page.md) whose *Tags* property matches this *Tags Page*. For instance, the Tags Page called "Beer Tasting" shows a list of all Location Item Pages that include "Beer Tasting" as one of the Tags. The *Tag* in the *Tags* property of the *Location Item Page* is a reference to the *Tags Page*.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Images** *(`Images`)* | ContentArea | Allows for inserting one or more images to act as carousel items on the page. **Note**: By default the image carousel on the page is populated by the Image property of each [*Location Item Page*](./Location%20Item%20Page.md) that matches this Tags Page.
**Top content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Intro text** *(`Intro`)* | String | Space for entering an introductory paragraph about the contents of this page.
**Main body** *(`MainBody`)* | XhtmlString | Provides a rich-text editor for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Bottom content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.

** **

<img src="../Screenshots/Tags%20Page%20-%20Content%20tab.png?raw=true" alt="Content tab of the Tag Page in All-properties view" width="50%"/>



## Technical Information

### Category
`Content`

### Inherits
[Landing Page](#)

### Restrictions
* The *Tags Page* only acts upon *Location Item Page* instances as only those have the *Tags* property.

## Preview
<img src="../Screenshots/Tags%20Page%20-%20OPE.png?raw=true" alt="Preview of Tags Page" width="100%"/>
