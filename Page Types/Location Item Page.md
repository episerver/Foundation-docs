# Location Item Page
"Two column landing page with properties to determine column size"

An open-format *Page Type* designed for a variety of page types including marketing landing pages, product promotion pages, etc. Consists of two side-by-side columns (ContentAreas) that are width-adjustable by the content author using Bootstrap column size rules. Columns are stacked in mobile view.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Page Global Properties*](#) list as well as the System [*Global Page Properties*](#) list.

Property Name | Type | Property Description
--------------|------|---------------
**Image** (`Image`) | ContentReference | Supplies the content with the image for this location. This property is separate from the Page Main Image property inherited from [FoundationPageData](#).
**Tags** (`Tags`) | ContentArea | An area for "tagging" this location content with "Tags" defined as [Tag Page](#). Used for filtering / faceting of Locations in the [Location List Page](#).
**Continent** (`Continent`) | String | The name value for the continent in which this location resides.
**Country** (`Country`) | String | The name value for the country in which this location resides.
**Airport initials** (`AirportInitials`) | String | The airport code for travel to this location - e.g. "MIA" for a Miami location or "LHR, LGW" for a London location
**Yearly passengers** (`YearlyPassengers`) | Integer | A numeric estimate for the number of tourists per annum (as a measure of popularity) for this location.
**Latitude** (`Latitude`) | Double | Numeric latitude value for the approximate geographical center of this location. Used for geographic radius filtering and map pin placement in [Location List Page](#).
**Longitude** (`Longitude`) | Double | Numeric longitude value for the approximage geographical center of this location. Used for geographic radius filtering and map pin placement in [Location List Page](#).
**Average temperature** (`AvgTemp`) | Double | Numberic average annual temperature for this location. Used for temperature filter in [Location List Page](#).
**Sidebar area** (`SidebarContentArea`) | ContentArea | Provides a drag-and-drop zone for including supplemental content for this location. E.g. videos, related destinations, promotions, etc.
**Promoted destination** (`Promoted`) | Boolean | When 


## Technical Information

### Category
`Location`

### Inherits
[FoundationPageData](#)

### Restrictions
* none

## Preview
![Preview of Location Item Page Content in Author / On-page-editing view](../Screenshots/Location%20Item%20Page%20-%20View.png?raw=true)