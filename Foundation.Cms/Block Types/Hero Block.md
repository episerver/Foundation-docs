# Hero Block
"Image block with overlay for text."

![Hero Block](Screenshots/Hero%20Block%20-%20icon.png)

A *Block Type* designed to display content of a Linkedin feed.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](../../Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Image** *(`BackgroundImage`)* | ContentReference | Upload an image to be displayed as background.
**Video** *(`MainBackgroundVideo`)* | ContentReference | Upload a video to be displayed as background.
**Link** *(`Link`)* | Url | Select where to forward users clicking on the hero block's content.
**Callout** *(`Callout`)* | HeroBlockCallout | A group of parameters that defines how the callout is displayed.
**Text** *(`CalloutContent`)* | XhtmlString | Enter a text to be displayed in front of the background content.
**Text placement** *(`CalloutContentAllignment`)* | String | Select the place where the text is displayed. You can choose from **Left**, **Right** or **Center**. 
**Text color** *(`CalloutTextColor`)* | String | Select the color of the text. You can choose from **None**, **Light** or **Dark**.
**Background color** *(`BackgroundColor`)* | String | Enter a HTML color name of the content text's background banner, for example *darkorange*. 
**Background opacity (0 to 1)** *(`CalloutOpacity`)* | Double | Enter a value between 0 and 1 to define the opacity of the colored banner, while 1 is full color without opacity.
**Callout position** *(`CalloutPosition`)* | String | Define with the four padding parameters where to place the text within the banner.
**Padding top** *(`Padding`)* | ContentReference | XXXXXXXXXXXXXXXXXXXX
**Padding right** *(`MainBackgroundVideo`)* | ContentReference | XXXXXXXXXXXXXXXXXXXXXXXXX
**Padding bottom** *(`MainBackgroundVideo`)* | ContentReference | XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
**Padding left** *(`MainBackgroundVideo`)* | ContentReference | XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX



** **
![Hero Block - Content tab](Screenshots/Hero%20Block%20-%20Content%20tab.png)

## Technical Information

### Category
`Content`

### Inherits
[FoundationBlockData](#)

### Restrictions
None

## Preview
![Hero Block - Preview](Screenshots/Hero20Block%20-%20Preview.png)



