# Common Properties and Tabs
"Properties that all page types have in common."

There are several tabs in the All Properties view that are shared between all page types. Let's look at them one tab at a time.

## Teaser
The following property list includes properties that are specific to defining how a page looks and behaves when used as a teaser on another page (dragged into a content area on another page).

Property Name | Type | Property Description
--------------|------|---------------
**Image** | Image | Provides a place for placing an image that acts as the background when the page is viewed as a teaser.
**Video** | Video | Provides a place for placing a video clip that acts as the background when the page is viewed as a teaser. Note: if both Image and Video have a value, Video wins.
**Text**  | Text Area | Provides a box for entering plain text to be shown as the teaser text.
**Text alignment**  | Dropdown | Provides a way to control the alignment of the teaser text. The default value is Left. The options are Left, Center and Right.
**Color theme**  | Dropdown | Provides a way to control the tint of teaser text. The options are Light and Dark.
**Button label**  | Text | Provides a box for entering the button text.
**Display hover effect**  | Checkbox | Provides a way to choose whether a hover effect should be used on the teaser element. If selected, the teaser text and button are not shown until the user hovers over the element. If not selected, teaser text and button are always visible. See screen shots below for reference.

## Technical Information

### Category
`Content`

### Restrictions
* If both Image and Video are filled in, Video takes presedence.
* If Text alignment is not set, the Page name, Text and Button properties are not shown at all. 

## Preview
#### The relationship between properties and the view
![Preview of Teaser tab in All-properties view and the rendering side-by-side](../Screenshots/Teaser%20Tab%20-%20properties%20to%20view.png?raw=true)
#### How the teaser looks when Display Hover Effect is selected but the element is not in focus
![Preview of Teaser element with Hover effect selected but before gaining focus](../Screenshots/Teaser%20View%20-%20hover%20but%20no%20mouse-over.png?raw=true)
#### How the teaser looks when Display Hover Effect is selected and it has focus (is being hovered over)
![Preview of Teaser element with Hover effect selected when the mouse pointer is over it](../Screenshots/Teaser%20View%20-%20hover%20with%20mouse-over.png?raw=true)
#### How the teaser looks when Display Hover Effect is not selected
![Preview of Teaser element without Hover effect selected](../Screenshots/Teaser%20View%20-%20no%20hover.png?raw=true)
