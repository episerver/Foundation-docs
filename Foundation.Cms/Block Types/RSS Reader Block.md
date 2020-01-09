# RSS Reader block
"Displays content from an RSS feed"

![RSS Reader Block](Screenshots/RSS%20Reader%20Block%20-%20icon.png)

A *Block Type* designed to display content from an RSS feed. The RSS feed can be internal or external and it can be used to display, for example, the latest updates to the website or a list of newsletters.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**RSS feed URL** *(`RssUrl`)* | Url | Allows for entering a URL to the RSS feed. The link can be either internal or external.
**Number of results** *(`MaxCount`)* | Integer | Determines how many of the RSS feed's latest items will be displayed. The default value is 5.
**Include publish date** *(`IncludePublishDate`)* | Boolean | If this check box is selected, the publish date of each RSS feed item will be displayed.
**Heading** *(`Heading`)* | String | Allows for adding a header to the RSS feed block.
**Main body** *(`MainBody`)* | Xhtmlstring | Allows for inserting a body text describing the RSS block content.

** **
![RSS Reader Block - Content tab](Screenshots/RSS%20Reader%20Block%20-%20Content%20tab.png)

## Technical Information

### Category
`Content`

### Inherits
[FoundationBlockData](#)

### Restrictions
None

## Preview
![RSS Reader Block](Screenshots/RSS%20Reader%20Block%20-%20Preview.png)
