# Common Properties and Tabs
"Properties that nearly all page types have in common."

## Categories 

Geta Tags is used for content categorization for both pages and blocks. The Categories are defined in the Assets panel:

<img src="Screenshots/Categories%20-%20Tree%20View.png?raw=true" alt="Categories pane in the Assets panel" width="30%" />

The category selector is in the header of the content type as shown below:

<img src="Screenshots/Page%20Type%20-%20Category%20Selector.png?raw=true" alt="Category selector in All Properties view" width="70%" />

There are several tabs in the *All Properties* view that are shared between almost all page types. Let's look at them one tab at a time.

<img src="Screenshots/Common%20Tabs.png?raw=true" alt="Common tabs for nearly all page types" />

*Common tabs for nearly all page types.*

## Teaser tab
The following property list includes properties that are specific to defining how a page looks and behaves when used as a teaser on another page (dragged into a content area on another page).

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Image** *(`PageImage`)* | Content Item | Provides a place for inserting an image that acts as the background when the page is viewed as a teaser.
**Video** *(`TeaserVideo`)* | Content Item | Provides a place for inserting a video clip that acts as the background when the page is viewed as a teaser. **Note:** if both *Image* and *Video* have a value, *Video* wins.
**Text** *(`TeaserText`)* | String | Provides a box for entering plain text to be shown as the teaser text.
**Text alignment** *(`TeaserTextAlignment`)* | String | Provides a way to control the alignment of the teaser text. The default value is Left. The options are **Left**, **Center** and **Right**.
**Color theme** *(`TeaserColorTheme`)* | String | Provides a way to control the tint of teaser text. The options are **Light** and **Dark**.
**Button label** *(`TeaserButtonText`)* | String | Provides a box for entering the button text.
**Button theme** *(`TeaserButtonStyle`)* | String | Provides a way to control the appearance of the button. The options are **Transparent Black**, **Transparent White**, **Dark** and **White**.
**Display hover effect** *(`ApplyHoverEffect`)* | Boolean | Provides a way to choose whether a hover effect should be used on the teaser element. If selected, the teaser text and button are not shown until the user hovers over the element. If not selected, teaser text and button are always visible. See screen shots below for reference.

### Technical Information

#### Restrictions
* If both Image and Video are filled in, Video takes presedence.
* If Text alignment is not set, the Page name, Text and Button properties are not shown at all. 

### Preview
#### The relationship between properties and the view
<img src="Screenshots/Teaser%20Tab%20-%20properties%20to%20view.png?raw=true" alt="Category selector in All Properties view" width="100%" />

#### How the teaser looks when Display Hover Effect is selected but the teaser is not in focus
<img src="Screenshots/Teaser%20View%20-%20hover%20but%20no%20mouse-over.png?raw=true" alt="Preview of teaser with hover effect but not in focus" width="50%" />

#### How the teaser looks when Display Hover Effect is selected and the teaser is in focus (hovered over)
<img src="Screenshots/Teaser%20View%20-%20hover%20with%20mouse-over.png?raw=true" alt="Preview of Teaser element with Hover effect selected when the mouse pointer is over it" width="50%"/>

#### How the teaser looks when Display Hover Effect is not selected
<img src="Screenshots/Teaser%20View%20-%20no%20hover.png?raw=true" alt="Preview of Teaser element without Hover effect selected" width="50%"/>

---

## Metadata tab
The following property list includes properties for providing meta data for the page.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Title** *(`MetaTitle`)* | String | Provides a place for the title.
**Keywords** *(`Keywords`)* | String | Provides a place for entering keywords for this page.
**Page description** *(`PageDescription`)* | String | Provides a place for entering a plain text description for the page. **Note:** if the *Text* property in the *Teaser* tab is empty, the Page description will be used as teaser text.
**Disable indexing** *(`DisableIndexing`)*  | Boolean | Provides a way to control whether the contents of this page should be indexed for search engines or not.

### Technical Information

#### Restrictions
* None

### Preview

<img src="Screenshots/Metadata%20Tab.png?raw=true" alt="Preview of Metadata tab in All-properties view" width="50%" />

---

## Styles tab
The following properties allow a skilled user to provide overrides of styles for this page and its children.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**CSS files** *(`CssFiles`)* | Link collection | Provides a place for dropping .css files to override the site defaults.
**CSS** *(`Css`)* | String | Provides a text box for typing or pasting CSS directly.

### Technical Information

#### Restrictions
* None

### Preview

<img src="Screenshots/Styles%20Tab.png?raw=true" alt="Preview of Styles tab in All-properties view" width="50%" />

---

## Scripts tab
The following properties allow a skilled user to provide JavaScript for this page and its children.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Script files** *(`ScriptFiles`)* | Link collection | Provides a place for dropping .js files to be utilized by this page and its children.
**Scripts** *(`Script`)* | String | Provides a text box for typig or pasting JavaScript code directly.

### Technical Information


#### Restrictions
* None

### Preview

<img src="Screenshots/Scripts%20Tab.png?raw=true" alt="Preview of Scripts tab in All-properties view" width="50%" />

---

## Settings tab
The following properties are what's added to the built-in options in the Settings tab.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Exclude from search results** *(`ExcludeFromSearch`)* | Boolean | Provides an option for determining whether this page should be shown in search results when an on-site search is performed.
**Hide site header** *(`HideSiteHeader`)* | Boolean | Provides an option for selecting whether the site header element should be hidden on this page.
**Hide site footer** *(`HideSiteFooter`)* | Boolean | Provides an option for selecting whether the site footer element should be hidden on this page.


### Technical Information


#### Restrictions
* None

### Preview

<img src="Screenshots/Settings%20Tab.png?raw=true" alt="The Setting tab in All Properties view" width="50%" />
