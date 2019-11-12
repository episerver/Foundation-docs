# Location Item Page
"Used to display the details of a location"

<img src="../../Screenshots/Location%20Item%20Page%20-%20icon.png?raw=true" alt="Location Item Page icon" width="40%" />

Longer description

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

### Content tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Intro text** *(`MainIntro`)* | String | Supplies....
**Main body** *(`MainBody`)* | XhtmlString | Supplies....
**Image** *(`Image`)* | Content Item | Supplies the content with the image for this location. This property is separate from the Page Main Image property inherited from [FoundationPageData](#).
**Tags** *(`Tags`)* | ContentArea | An area for "tagging" this location content with "Tags" defined as [Tag Page](#). Used for filtering/faceting of Locations in the [Locations List Page](./Locations%20List%20Page.md).
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Left content area** *(`LeftCOntentArea`)* | ContentArea | Provides a drag-and-drop zone for including supplemental content for this location. E.g. videos, related destinations, promotions, etc.
**New location** *(`New`)* | Boolean | When selected, this location will show up in a listing of *new* locations.
**Promoted location** *(`Promoted`)* | Boolean | When selected, this locaiton will show up in a listing of promoted locations. 


** **

<img src="../../Screenshots/Location%20Item%20Page%20-%20Content%20tab.png?raw=true" alt="<PAGETYPE> icon" width="50%" />

### Location tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Continent** *(`Continent`)* | String | The name value for the continent in which this location resides.
**Country** *(`Country`)* | String | The name value for the country in which this location resides.
**Latitude** *(`Latitude`)* | Floating point number | Numeric latitude value for the approximate geographical center of this location. Used for geographic radius filtering and map pin placement in [Locations List Page](./Locations%20List%20Page.md).
**Longitude** *(`Longitude`)* | Floating point number | Numeric longitude value for the approximage geographical center of this location. Used for geographic radius filtering and map pin placement in [Locations List Page](./Locations%20List%20Page.md).
**Average temperature** *(`AvgTemp`)* | Floating point number | Numeric average annual temperature for this location. Used for temperature filter in [Locations List Page](./Locations%20List%20Page.md).
**Airport initials** *(`AirportInitials`)* | String | The airport code for travel to this location - e.g. "MIA" for a Miami location or "LHR, LGW" for a London location
**Yearly passengers** *(`YearlyPassengers`)* | Integer | A numeric estimate for the number of tourists per annum (as a measure of popularity) for this location.

** **

<img src="../../Screenshots/Location%20Item%20Page%20-%20Location%20tab.png?raw=true" alt="<PAGETYPE> icon" width="50%" />


## Technical Information

### Category
`Location`

### Inherits
[FoundationPageData](#)

### Restrictions
* none

## Preview
<img src="../../Screenshots/Location%20Item%20Page%20-%20OPE.png?raw=true" alt="Location Item Page" width="100%" />
