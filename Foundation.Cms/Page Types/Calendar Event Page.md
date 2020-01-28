# Calendar Event Page
"A page for a calendar event. Provide start and end date, location and content."

<img src="Screenshots/Calendar%20Event%20Page%20-%20icon.png?raw=true" alt="Calendar Event Page icon" width="40%" />

This page type is used for creating a calendar event, complete with the start and end dates, the location of the event and other properties for enriching the event.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Start date** *(EventStartDate)* | Date/Time | Define the starting date and time for the event.
**End date** *(EventEndDate)* | Date/Time | Define the ending date and time for the event.
**Location** *(Location)* | String | Define the location for the event (could be a city, a venue).
**Main body** *(MainBody)* | XhtmlString | Provides a rich-text editor for entering formatted content.
**Main content area** *(MainContentArea)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.

## Technical Information

### Category
`Calendar`

### Inherits
[FoundationPageData](Foundation%20Page%20Data.md)

### Restrictions
* The *Calendar Event Pages* must be created inside a [Folder Page](./Folder%20Page.md) for the *Calendar Block* to be able to create a collection of calendar events.

## Preview
<img src="Screenshots/Calendar%20Event%20Page%20-%20Properties%20to%20View.png?raw=true" alt="Preview of Calendar Event Page Content tab in All-properties view" width="100%"/>


