# Standard Page
"Allows for creation of rich standard pages."

<img src="Screenshots/Standard%20Page%20-%20icon.png?raw=true" alt="Preview of a Standard Page" width="50%"/>

Standard Page is designed for a variety of use cases, including marketing landing pages, product promotion pages, etc. Consists of a background image or video, a main body element and a main content area.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main body** *(`MainBody`)* | XhtmlString | Provides an area for rich, formatted content. 
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Background video** *(`BackgroundVideo`)* | Content Item | Allows for inserting a video clip that plays as the background of the page. **Note:** if nothing is provided here, the *Image* from the Teaser tab will be used as the background instead.
**Top padding mode** *(`TopPaddingMode`)* | String | Determines the way in which the background image or video is positioned on the page. The options are: **None**, **Half** or **Full**.

## Technical Information

### Category
`Content`

### Inherits
[Landing Page](#)

### Restrictions
* none

## Preview
<img src="Screenshots/Standard%20Page%20-%20All props to view.png?raw=true" alt="Preview of a Standard Page" width="100%"/>