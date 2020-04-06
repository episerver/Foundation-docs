# Navigation Block
"Render normal left/right navigation structures"

![Navigation Block](Screenshots/Navigation%20Block%20-%20icon.png)


A block type that renders a normal left/right navigation structure. The block is "context aware" by default, so when placed on a page the navigation is built from that page and downwards. By selecting a root page, you can override the navigation starting point.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](../../Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Heading** *(`Heading`)* | String | Enter a headline for the navigation block.
**Root page** *(`RootPage`)* | PageReference | Select a starting page the navigation menu is built up from. If you do not set a root page, the navigation is built up from the page where the block is found and downwards.

** **
![Navigation Block - Content tab](Screenshots/Navigation%20Block%20-%20Content%20tab.png)

## Technical Information

### Category
`Content`

### Inherits
[FoundationBlockData](Foundation%20Block%20Data%20Block.md)

### Restrictions
None

## Preview
![Navigation Block - Preview](Screenshots/Navigation%20Block%20-%20Preview.png)
