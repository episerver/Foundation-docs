# Demo Home Page
"Used for home page of all sites."

<img src="../../Screenshots/Demo%20Home%20Page%20-%20icon.png?raw=true" alt="Blog Item Page icon" width="40%" />

An open-format *Page Type* designed to act as the home page or root of your website. Consists of three content areas and a main body area. 

## Property List
The following property list includes properties that are unique to this content type. For a list of shared properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

### Content tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main body** *(`MainBody`)* | XHTML string (>255) | Provides a rich-text editor for entering formatted content.
**Top content area** *(`TopContentArea`)* | ContentArea | Provides a drag-and-drop interface for placing media, blocks, or other content onto the page.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a drag-and-drop interface for placing media, blocks, or other content onto the page.
**Bottom content area** *(`BottomContentArea`)* | ContentArea | Provides a drag-and-drop interface for placing media, blocks, or other content onto the page.

** **
#### Preview of the Content tab
<img src="../../Screenshots/Demo%20Home%20Page%20-%20Content%20tab.png?raw=true" alt="Content tab of Demo Home Page in All Properties view" width="50%" />

---

### Header tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Site logo** *(`SiteLogo`)* | Content Item | Provides a drag-and-drop interface for placing a logo image for the entire site.
**Banner text** *(`BannerText`)* | XHTML string (>255) | Provides a rich-text editor for entering formatted content that appears on the top of each page of the site.
**Menu style** *(`HeaderMenuStyle`)* | Long string (>255) | Allows for selecting the position of the site logo relative to the main navigation. The options are **Left logo** or **Center logo**.
**Show commerce header components** *(`ShowCommerceHeaderComponents`)* | Selected/not selected | When selected, three extra options will be available in the site header: Wishlist, Shopping cart and the Market selector.
  
<img src="../../Screenshots/Demo%20Home%20Page%20-%20Header%20tab%20-%20Show%20commerce%20header%20components.png?raw=true" alt="Header tab of Demo Home Page in All Properties view" width="80%" /> 

*Show commerce header components* option selected on the left.

** **  

#### Peview of the Header tab

<img src="../../Screenshots/Demo%20Home%20Page%20-%20Header%20tab.png?raw=true" alt="Header tab of Demo Home Page in All Properties view" width="50%" />

---

### Footer tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Introduction** *(`Introduction`)* | Long string (>255) | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Company header** *(`CompanyHeader`)* | Long string (>255) | Configures the *Main content area* column width in Bootstrap column integer values. *Main content area* is inherited from [FoundationPageData](#) as a global page property.
**Company address** *(`CompanyAddress`)* | Long string (>255) | Configures the *Right hand content area* column width in Bootstrap column integer values.
**Company phone** *(`CompanyPhone`)* | Long string (>255) | Configures the *Right hand content area* column width in Bootstrap column integer values.
**Company email** *(`CompanyEmail`)* | Long string (>255) | Configures the *Right hand content area* column width in Bootstrap column integer values.
**Links header** *(`LinksHeader`)* | Long string (>255) | Configures the *Right hand content area* column width in Bootstrap column integer values.
**Links** *(`Links`)* | Link collection | Configures the *Right hand content area* column width in Bootstrap column integer values.
**Social header** *(`SocialHeader`)* | Long string (>255) | Configures the *Right hand content area* column width in Bootstrap column integer values.
**Content area** *(`ContentArea`)* | ContentArea | Description here.
**Copyright** *(`FooterCopyrightText`)* | Long string (>255) | Configures the *Right hand content area* column width in Bootstrap column integer values.

** ** 

#### Preview of the Footer tab

<img src="../../Screenshots/Demo%20Home%20Page%20-%20Footer%20tab.png?raw=true" alt="Footer tab of Demo Home Page in All Properties view" width="50%" />

---

### Search settings tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Search option** *(SearchOption)* | Long string (>255) | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Show products in search results** *(ShowProductsSearchResults)* | Selected/not selected | Configures the *Main content area* column width in Bootstrap column integer values. *Main content area* is inherited from [FoundationPageData](#) as a global page property.
**Show contents in search results** *(ShowContentSearchResults)* | Selected/not selected | Configures the *Main content area* column width in Bootstrap column integer values. *Main content area* is inherited from [FoundationPageData](#) as a global page property.
**Search catalog** *(SearchCatalog)* | Integer | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.

** **

#### Preview of the Search settings tab

<img src="../../Screenshots/Demo%20Home%20Page%20-%20Search%20settings%20tab.png?raw=true" alt="Search settings tab of Demo Home Page in All Properties view" width="50%" />

---

### Menu tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main menu** *(MainMenu)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Mobile menu** *(MobileNavigationPages)* | Link collection | Description here.
**My account menu (commerce)** *(MyAccountCommerceMenu)* | Link collection | Description here.
**My account menu (CMS)** *(MyAccountCmsMenu)* | Link collection | Description here.
**Organization menu** *(OrganizationMenu)* | Link collection | Description here.

** **

#### Preview of teh Menu tab

<img src="../../Screenshots/Demo%20Home%20Page%20-%20Menu%20tab.png?raw=true" alt="Menu tab of Demo Home Page in All Properties view" width="50%" />

---

### Site labels tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**My account** *(MyAccountLabel)* | Long string (>255) | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Shopping cart** *(CartLabel)* | Long string (>255) | Configures the *Main content area* column width in Bootstrap column integer values. 
**Search** *(SearchLabel)* | Long string (>255) | Configures the *Right hand content area* column width in Bootstrap column integer values.
**Wishlist** *(WishlistLabel)* | Long string (>255) | Configures the *Right hand content area* column width in Bootstrap column integer values.
**Shared cart** *(SharedCartLabel)* | Long string (>255) | Configures the *Right hand content area* column width in Bootstrap column integer values.

** **

#### Preview of the Site labels tab

<img src="../../Screenshots/Demo%20Home%20Page%20-%20Site%20labels%20tab.png?raw=true" alt="Site labels tab of Demo Home Page in All Properties view" width="50%" />

---

### Site structure tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Search page** *(SearchPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Store locator page** *(StoreLocatorPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Address book page** *(AddressBookPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Reset password page** *(ResetPasswordPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Wishlist page** *(WishlistPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Shopping cart page** *(CartPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Shared cart page** *(SharedCartPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Payment plan details page** *(PaymentPlanDetailsPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Organization main page** *(OrganizationMainPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Sub-organization page** *(SubOrganizationPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Organization order pads page** *(OrganizationOrderPadsPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Quick order page** *(QuickOrderPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Order details page** *(OrderDetailsPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Order history page** *(OrderHistoryPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Order confirmation page** *(OrderConfirmationPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Checkout page** *(CheckoutPage)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Resource not found page** *(PageNotFound)* | Content Item | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Show product ratings on all product tiles** *(`ShowProductRatingsOnListings`)* | Selected/not selected | When selected, the product ratings will be shown with each product tile.


** **

#### Preview of the Site structure tab

<img src="../../Screenshots/Demo%20Home%20Page%20-%20Site%20structure%20tab.png?raw=true" alt="Site structure tab of Demo Home Page in All Properties view" width="50%" />

---

### Mail templates tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Send order confirmations** *(SendOrderConfirmationMail)* | Selected/not selected | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.
**Order confirmation** *(OrderConfirmationMail)* | Content Item | Description here.
**Reset password** *(ResetPasswordMail)* | Content Item | Description here.

** **

#### Preview of the Mail templates tab

<img src="../../Screenshots/Demo%20Home%20Page%20-%20Mail%20templates%20tab.png?raw=true" alt="Mail template tab of Demo Home Page in All Properties view" width="50%" />

---


## Technical Information

### Category
`Content`

### Inherits
[Landing Page](#)

### Restrictions
* none

## Preview
<img src="../../Screenshots/Demo%20Home%20Page%20-%20OPE.png?raw=true" alt="Demo Home Page" width="100%" />
