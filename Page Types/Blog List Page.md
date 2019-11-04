# Blog List Page
"Blog List Page for dates such as year and month."

<img src="../Screenshots/Blog%20List%20Page%20-%20icon.png?raw=true" alt="Blog List Page icon" width="40%" />

The *Blog List Page* acts as a entry point to blog items ([Blog Item Page](./Blog%20Item%20Page.md)). There are controls for determining the appearance and order of the blog items on the *Blog List Page*.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

### Content tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Heading** *(`Heading`)* | Long string (>255) | Allows for entering a heading for the blog listing.
**Main body** *(`MainBody`)* | XHTML string (>255) | Provides a rich-text editor for entering formatted content.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.

** **
<img src="../Screenshots/Blog%20List%20Page%20-%20Content%20tab.png?raw=true" alt="Content tab of the Blog List Page in All-properties view" width="50%"/>

---


### Blog list tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Root** *(`Root`)* | Page | Lets the user determine the root page for a blog listing.
**Recursive** *(`Recursive`)* | Selected/not selected | Determines whether sub-items under the items under the root level should be searched for Blog Item Pages.
**Sort order** *(`SortOrder`)* | Integer | Defines the order in which the Blog Item Pages should be sorted in the list.
**Include publish date** *(`IncludePublishDate`)* | Selected/not selected | Lets the user select whether the publish date of the *Blog Item Page* should be included in the listing or not.
**Include teaser text** *(`IncludeTeaserText`)* | Selected/not selected | Lets the user select whether the contents of the *Text* property in the *Teaser* tab of the *Blog Item Page* should be included in the listing or not.
**Category filter (match all selected)** *(`CategoryListFilter`)* | ContentReferenceList | Lets the user select a list of content categories to use as a filter when gathering the listing of Blog Item Pages.
**Template of blogs listing** *(`Template`)* | Long string (>255) | Determines the appearance of the listing of Blog Item Pages. The options are **Grid**, **Image on the left** and **Image on the top**.
**Preview option (not available in the Grid template)** *(`PreviewOption`)* | Long string (>255) | Determines the appearance of the listing of Blog Item Pages. The options are **One third width**, **Half width** and **Full width**.


** **

#### Blog list when *Template of blogs listing* is set to "Grid".

<img src="../Screenshots/Blog%20List%20Page%20-%20Blog%20list%20tab%20-%20Grid.png?raw=true" alt="Blog list tab of the Blog List Page in All-properties view -- Grid" width="100%"/>

#### Blog list when *Template of blogs listing* is set to "Image on the top".

<img src="../Screenshots/Blog%20List%20Page%20-%20Blog%20list%20tab%20-%20ImageOnTheTop.png?raw=true" alt="Blog list tab of the Blog List Page in All-properties view -- Image on the top" width="100%"/>

#### Blog list when *Template of blog listing*"* is set to "Image on the left".

<img src="../Screenshots/Blog%20List%20Page%20-%20Blog%20list%20tab%20-%20ImageOnTheLeft.png?raw=true" alt="Blog list tab of the Blog List Page in All-properties view -- Image on the left" width="100%"/>

---



## Technical Information

### Category
`Blog`

### Inherits
[Landing Page](#)

### Restrictions
* This page type lists only pages of type [Blog Item Page](./Blog%20Item%20Page.md).

* The *Preview option* in the *Blog list* tab is effective only when *Image on the top* is selected in the *Template of blogs listing* property.

## Preview
<img src="../Screenshots/Blog%20List%20Page%20-%20OPE.png?raw=true" alt="Preview of the Blog List Page" width="100%"/>
