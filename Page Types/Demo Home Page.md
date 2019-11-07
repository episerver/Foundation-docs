# Demo Home Page
"Used for home page of all sites."

<img src="../Screenshots/Demo%20Home%20Page%20-%20icon.png?raw=true" alt="Home Page icon" width="40%" />

An open-format *Page Type* designed to act as the home page or root of your website. Consists of three content areas and a main body area. 

## Preview: Property name (Tab name) in red

<img src="../Screenshots/Demo%20Home%20Page%20-%20OPE%20-%20Explained.png?raw=true" alt="Demo Home Page" width="100%" />

## Property List
The following property list includes properties that are unique to this content type. For a list of shared properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

### Content tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main body** *(`MainBody`)* | XhtmlString | Provides a rich-text editor for entering formatted content.
**Top content area** *(`TopContentArea`)* | ContentArea | Provides a drag-and-drop interface for placing media, blocks, or other content onto the page.
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a drag-and-drop interface for placing media, blocks, or other content onto the page.
**Bottom content area** *(`BottomContentArea`)* | ContentArea | Provides a drag-and-drop interface for placing media, blocks, or other content onto the page.

** **
#### Preview of the Content tab
<img src="../Screenshots/Demo%20Home%20Page%20-%20Content%20tab.png?raw=true" alt="Content tab of Demo Home Page in All Properties view" width="50%" />

---

### Header tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Site logo** *(`SiteLogo`)* | Content Item | Provides a drag-and-drop interface for placing a logo image for the entire site.
**Banner text** *(`BannerText`)* | XhtmlString | Provides a rich-text editor for entering formatted content that appears on the top of each page of the site.
**Menu style** *(`HeaderMenuStyle`)* | String | Allows for selecting the position of the site logo relative to the main navigation. The options are **Left logo** or **Center logo**.
**Show commerce header components** *(`ShowCommerceHeaderComponents`)* | Boolean | When selected, three extra options will be available in the site header: Wishlist, Shopping cart and the Market selector (see below).
  
<img src="../Screenshots/Demo%20Home%20Page%20-%20Header%20tab%20-%20Show%20commerce%20header%20components.png?raw=true" alt="Header tab of Demo Home Page in All Properties view" width="80%" /> 

*Show commerce header components* option selected on the left.

** **  

#### Peview of the Header tab

<img src="../Screenshots/Demo%20Home%20Page%20-%20Header%20tab.png?raw=true" alt="Header tab of Demo Home Page in All Properties view" width="50%" />

---

### Footer tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Introduction** *(`Introduction`)* | String | Provides a text box to enter text that appears on top of the footer.
**Company header** *(`CompanyHeader`)* | String | Provides a text box for entering a header for the left-most column of the footer.
**Company address** *(`CompanyAddress`)* | String | Provides a text for entering the address of the company.
**Company phone** *(`CompanyPhone`)* | String | Provides a text box for entering the company phone number.
**Company email** *(`CompanyEmail`)* | String | Allows for entering the company email address.
**Links header** *(`LinksHeader`)* | String | Provides a text box for entering a header for the second column of the footer.
**Links** *(`Links`)* | Link collection | Provides a drag-and-drop interface for adding one or more links to pages and other content. Links can be either internal (on this site) or external.
**Social header** *(`SocialHeader`)* | String | Provides a text box for entering a header for the third column of the footer.
**Content area** *(`ContentArea`)* | ContentArea | Provides a drag-and-drop interface for adding a block, a form or media to the bottom-right corner of the footer.
**Copyright** *(`FooterCopyrightText`)* | String | Provides a text box for entering the site copyright text.

** ** 

#### Preview of the Footer tab

<img src="../Screenshots/Demo%20Home%20Page%20-%20Footer%20tab.png?raw=true" alt="Footer tab of Demo Home Page in All Properties view" width="50%" />

---

### Search settings tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Search option** *(`SearchOption`)* | String | Provides a selector for the search option for the site. The options are **Quick search** and **Auto search**.
**Show products in search results** *(`ShowProductsSearchResults`)* | Boolean | Option to control wether site search should show commerce products in the search results or not.
**Show contents in search results** *(`ShowContentSearchResults`)* | Boolean | Option to control wether site search should show CMS contents in the search results or not.
**Search catalog** *(`SearchCatalog`)* | Integer | Provides a selector for determining which commerce catalogs should be searched when searching for products. The options are **All** or a particular Catalog.

** **

#### Preview of the Search settings tab

<img src="../Screenshots/Demo%20Home%20Page%20-%20Search%20settings%20tab.png?raw=true" alt="Search settings tab of Demo Home Page in All Properties view" width="50%" />

---

### Menu tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Main menu** *(`MainMenu`)* | ContentArea | Provides a drag-and-drop interface for placing blocks of type *Menu Item Block* to produce the main navigation menu.
**Mobile menu** *(`MobileNavigationPages`)* | Link collection | Provides a drag-and-drop interface for placing blocks of type *Menu Item Block* to produce the mobile navigation menu.
**My account menu (commerce)** *(`MyAccountCommerceMenu`)* | Link collection | Provides a drag-and-drop interface for placing blocks of type *Menu Item Block* to produce the *My account* menu (commerce).
**My account menu (CMS)** *(`MyAccountCmsMenu`)* | Link collection | Provides a drag-and-drop interface for placing blocks of type *Menu Item Block* to produce the *My account* menu (CMS).
**Organization menu** *(`OrganizationMenu`)* | Link collection | Provides a drag-and-drop interface for placing blocks of type *Menu Item Block* to produce the *Organization* menu.

** **

#### Preview of the Menu tab

<img src="../Screenshots/Demo%20Home%20Page%20-%20Menu%20tab.png?raw=true" alt="Menu tab of Demo Home Page in All Properties view" width="50%" />

---

### Site labels tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**My account** *(`MyAccountLabel`)* | String | Allows for providing a label for the property.
**Shopping cart** *(`CartLabel`)* | String | Allows for providing a label for the property. 
**Search** *(`SearchLabel`)* | String | Allows for providing a label for the property.
**Wishlist** *(`WishlistLabel`)* | String | Allows for providing a label for the property.
**Shared cart** *(`SharedCartLabel`)* | String | Allows for providing a label for the property.

** **

#### Preview of the Site labels tab

<img src="../Screenshots/Demo%20Home%20Page%20-%20Site%20labels%20tab.png?raw=true" alt="Site labels tab of Demo Home Page in All Properties view" width="50%" />

---

### Site structure tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Show product ratings on all product tiles** *(`ShowProductRatingsOnListings`)* | Boolean | When selected, the product ratings will be shown with each product tile.
**Search page** *(`SearchPage`)* | Content Item | Allows for picking the *Search* page from the site tree.
**Store locator page** *(`StoreLocatorPage`)* | Content Item | Allows for picking the *Store locator* page from the site tree.
**Address book page** *(`AddressBookPage`)* | Content Item | Allows for picking the Address book page from the site tree.
**Reset password page** *(`ResetPasswordPage`)* | Content Item | Allows for picking the *Reset password* page from the site tree.
**Wishlist page** *(`WishlistPage`)* | Content Item | Allows for picking the *Whishlist* page from the site tree.
**Shopping cart page** *(`CartPage`)* | Content Item | Allows for picking the *Shopping cart* page from the site tree.
**Shared cart page** *(`SharedCartPage`)* | Content Item | Allows for picking the *Shared cart* page from the site tree.
**Payment plan details page** *(`PaymentPlanDetailsPage`)* | Content Item | Allows for picking the *Payment plan details* page from the site tree.
**Organization main page** *(`OrganizationMainPage`)* | Content Item | Allows for picking the *Organization main* page from the site tree.
**Sub-organization page** *(`SubOrganizationPage`)* | Content Item | Allows for picking the *Sub-organization* page from the site tree.
**Organization order pads page** *(`OrganizationOrderPadsPage`)* | Content Item | Allows for picking the *Organization order pads* page from the site tree.
**Quick order page** *(`QuickOrderPage`)* | Content Item | Allows for picking the *Quick order page* from the site tree.
**Order details page** *(`OrderDetailsPage`)* | Content Item | Allows for picking the *Order details* page from the site tree.
**Order history page** *(`OrderHistoryPage`)* | Content Item | Allows for picking the *Order history* page from the site tree.
**Order confirmation page** *(`OrderConfirmationPage`)* | Content Item | Allows for picking the *Order confirmation* page from the site tree.
**Checkout page** *(`CheckoutPage`)* | Content Item | Allows for picking the *Checkout* page from the site tree.
**Resource not found page** *(`PageNotFound`)* | Content Item | Allows for picking the *Resource not found* page from the site tree.


** **

#### Preview of the Site structure tab

<img src="../Screenshots/Demo%20Home%20Page%20-%20Site%20structure%20tab.png?raw=true" alt="Site structure tab of Demo Home Page in All Properties view" width="50%" />

---

### Mail templates tab

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Send order confirmations** *(`SendOrderConfirmationMail`)* | Boolean | When selected, an order confirmation email is sent after an order is placed.
**Order confirmation** *(`OrderConfirmationMail`)* | Content Item | Allows for selecting the CMS page that contains the *Order confirmation* email message template.
**Reset password** *(`ResetPasswordMail`)* | Content Item | Allows for selecting the CMS page that contains the *Reset password* email message template.

** **

#### Preview of the Mail templates tab

<img src="../Screenshots/Demo%20Home%20Page%20-%20Mail%20templates%20tab.png?raw=true" alt="Mail template tab of Demo Home Page in All Properties view" width="50%" />

---


## Technical Information

### Category
`Content`

### Inherits
[Landing Page](#)

### Restrictions
* None.

## Preview
<img src="../Screenshots/Demo%20Home%20Page%20-%20OPE.png?raw=true" alt="Demo Home Page" width="100%" />
