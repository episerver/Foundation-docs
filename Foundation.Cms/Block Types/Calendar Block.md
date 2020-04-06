# Calendar Block
"A block that lists a bunch of Calendar events."

![Calendar Block](Screenshots/Calendar%20Block%20-%20icon.png)

A *Block Type* designed to display a calendar with multiple view options that shows events that might be relevant to your customers.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](../../Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**View as** *(`ViewMode`)* | String | Select the view mode, consisting of *Day*, *Week*, *Month* or *List*.
**Events root** *(`EventsRoot`)* | PageReference | Select the path to your events' folder.
**Number of events** *(`Count`)* | Integer | Enter the number of events to be displayed.
**Filter by category**(`CategoryFilter`)* | CategoryList | Select a category for filtering events.


** **
![Calendar Block - Content tab](Screenshots/Calendar%20Block%20-%20Content%20tab.png)

## Technical Information

### Category
`Calendar`

### Inherits
[FoundationBlockData](Foundation%20Block%20Data%20Block.md)

### Restrictions
None

## Preview
![Calendar Block - Preview](Screenshots/Calendar%20Block%20-%20Preview.png)
