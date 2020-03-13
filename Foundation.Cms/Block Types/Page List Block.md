# Page List Block
"A block that lists a bunch of pages."

![Page List Block](Screenshots/Page%20List%20Block%20-%20icon.png)


A *Block Type* designed to list multiple pages with preview image, publishing date and teaser text. Available as grid or as list with multiple layout options.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](../../Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Heading** *(`Heading`)* | String | Enter a headline for the Page List Block.
**Include publish date** *(`IncludePublishDate`)* | Boolean | Select whether to show the publish date on each listed page.
**Include teaser text** *(`IncludeTeaserText`)* | Boolean | Select whether to show the teaser text on each listed page.
**Number of results** *(`Count`)* | Integer | Enter the number of listed pages to be displayed.
**Sort order** *(`SortOrder`)* | FilterSortOrder | Define the sort order: *According to creation date (latest first/oldest first)*, *Alphabetical*, *According to sort index*, *According to change date (latest first)* or *According to start publish date (oldest first/latest first)*.
**Root** *(`Root`)* | PageReference | Select the root folder for the Page List Block.
**Filter by page type** *(`PageTypeFilter`)* | PageType | Select whether to include specified page types only.
**Filter by category** *(`CategoryListFilter`)* | IList | Categories to filter the list on.
**Include all levels** *(`Recursive`)* | Boolean | Select whether to show pages of the same level only.
**Template of pages listing** *(`Template`)* | String | Define the layout: *Grid*, *Image on the left*, *Image on the top* or *No image*.
**Preview option (not available in the Grid template)** *(`PreviewOption`)* | String | If you selected *Image on the left* or *Image on the top*, you can define the preview size to be *One third width*, *Half width* or *Full width*.

** **
![Page List Block - Content tab](Screenshots/Page%20List%20Block%20-%20Content%20tab.png)

## Technical Information

### Category
`Content`

### Inherits
[FoundationBlockData](#)

### Restrictions
None

## Preview
![Page List Block - Preview](Screenshots/Page%20List%20Block%20-%20Preview.png)


