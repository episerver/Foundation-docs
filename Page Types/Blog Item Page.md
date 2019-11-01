# Blog Item Page
"Blog Item Page created underneath the start page and moved to the right area."

<img src="../Screenshots/Blog%20Item%20Page%20-%20icon.png?raw=true" alt="<PAGETYPE> icon" width="40%" />

The Blog Item is meant for writing blog posts. The page consists of an image that acts as the teaser image, Main content area, Main body and block for leaving and showing comments about this article.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](https://github.com/egandalf/FoundationDocumentation/blob/master/Page%20Types/Common%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Author** *(Author)* | Long string (>255) | Allows for entering the author of the blog post.
**Main body** *(MainBody)* | XHTML string (>255) | Provides a rich-text editor for entering formatted content.
**Main content area** *(MainContentArea)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Comments per page** *(CommentsPerPage)* | Integer | Provides a numeric control for selecting the number of reader comments to show on the blog item page.
**Block padding** (BlockPadding) | Floating point number | Provides a numeric control for selecting the padding for the comments block on the page.


** **

<img src="../Screenshots/Blog%20Item%20Page%20-%20Content%20tab.png?raw=true" alt="Content tab of Blog Item Page" width="70%"/>

## Technical Information

### Category
`Blog`

### Inherits
[Landing Page](#)

### Restrictions
* Only pages of type Blog Item Page and Blog List Page can be created as a child page of this page type.

## Preview
<img src="../Screenshots/Blog%20Item%20Page%20-%20Preview.png?raw=true" alt="Preview of Blog Item Page" width="50%"/>
