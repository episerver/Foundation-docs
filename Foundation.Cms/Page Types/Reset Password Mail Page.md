# Reset Password Mail Page

The Reset Password Mail Page is used for sending the reset password link to the requesting user (see also [*Reset Password Page*](./Reset%20Password%20Page.md)). The page consists of a subject line, main body element and a main content area.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](../../Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Subject** *(`Subject`)* | String | Provides an area for the subject line of the email. 
**Main body** *(`MainBody`)* | XhtmlString | Provides an area for rich, formatted content. 
**Main content area** *(`MainContentArea`)* | ContentArea | Provides a configurable drag-and-drop interface for placing media, blocks, or other content onto the page.

** **

<img src="Screenshots/Reset%20Password%20Mail%20Page%20-%20Content%20tab.png?raw=true" alt="Content tab of the Reset Passowrd Mail Page" width="50%"/>


## Technical Information

### Category
`NA`

### Inherits
[MailBasePage](Mail%20Base%20Page.md)

### Restrictions
* The user who clicked the "Forgot your password?" link will receive an email defined in this template.

* It is not possible to add a Reset Password Mail Page as an editor.

## Preview
<img src="Screenshots/Reset%20Password%20Mail%20Page%20-%20OPE.png?raw=true" alt="Preview of a Reset Password Mail Page" width="100%"/>
