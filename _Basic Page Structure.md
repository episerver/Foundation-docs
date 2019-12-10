# <Page Type Name> Page
"(Description from the icon.)"

<img src="../Screenshots/Blog%20Item%20Page%20-%20icon.png?raw=true" alt="<PAGETYPE> icon" width="40%" />

(Longer description of usage) The Blog Item is meant for writing blog posts. The page consists of an image that acts as the teaser image, Main content area, Main body and block for leaving and showing comments about this article.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Author** *(`Author`)* | String | Allows for entering the author of the blog post.
**Main body** *(`MainBody`)* | XhtmlString | Provides a rich-text editor for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Comments per page** *(`CommentsPerPage`)* | Integer | Provides a numeric control for selecting the number of reader comments to show on the blog item page.
**Categories** *(`Categories`)* | ContentReferenceList | List of categories.
**Exclude from search results** *(`ExcludeFromSearch`)* |  Boolean | Whether or not to exclude this content item from search results.
**Image** *(`PageImage`)* | Content Item | Used as the teaser image when page is referenced on other pages.
**CSS files** *(`CssFiles`)* | Link collection | Allows for providing one or more CSS files for this page.
**Left column** *(`MainContentAreaColumn`)* | Integer | Used to determine the column width.
**Continent** *(`Continent`)* | String (<=255) | Space for typing the name of the continent.
**Latitude** *(`Latitude`)* | Floating point number | Used for providing the latitude of a location.
**Root** *(`Root`)* | Page | Used to define the starting point in the page hierarchy.
**Start date** *(`EventStartDate`)* | Date/Time | Set the starting date for the event.

** **

<img src="../Screenshots/Blog%20List%20Page%20-%20Content%20tab.png?raw=true" alt="Content tab of the Blog List Page in All-properties view" width="50%"/>



## Technical Information

### Category
`Blog`

### Inherits
[Landing Page](#)

### Restrictions
* Only pages of type Blog Item Page and Blog List Page can be created as a child page of this page type.

## Preview
<img src="../Screenshots/Blog%20Item%20Page%20-%20Preview.png?raw=true" alt="Preview of Blog Item Page" width="100%"/>
