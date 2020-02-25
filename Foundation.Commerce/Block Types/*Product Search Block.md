# Product Search Block
"Configurable search block for all products, allows generic filtering."

![Product Search Block](Screenshots/Product%20Search%20Block%20-%20icon.png)

A *Block Type* designed to allow customers to search for products with or without filtering.

## Property List
The following property list includes properties that are unique to this content type. For a list of global properties, view our [*Common Page Properties*](./Common%20Page%20Properties.md) list.

Display Name *(Name in code)* | Type | Property Description
--------------|------|---------------
**Heading** *(`Heading`)* | Xhtmlstring | Headline of the product search page.
**Search term** *(`SearchTerm`)* | Xhtmlstring | Configure a predefined search term.
**Number of results** *(`ResultsPerPage`)* | Integer | The number of products to show in the list. Default is 6.
**Results per row** *(`ItemsPerRow)* | Xhtmlstring | The number of products to show in a row. Default is 3..
**Catalog categories** *(`Nodes`)* | ContentArea | Root categories to get products from, includes sub categories.
**Filters** *(`Filters`)* | ContentArea | Filters to apply to the search result.
**Priority products** *(`PriorityProducts`)* | ContentArea | Products to put first in the list.
**Minimum price** *(`MinPrice`)* | Integer | The minimum price in the current market currency.
**Maximum price** *(`MaxPrice`)* | Integer | The maximum price in the current market currency.

** **
![Product Search Block](Screenshots/Product%20Search%20Block%20-%20Content%20tab.png)

## Technical Information

### Category
`Commerce`

### Inherits
[FoundationBlockData](#)

### Restrictions
None

## Preview
![Product Search Block](Screenshots/Product%20Search%20Block%20-%20Preview.png)


