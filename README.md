# RSelenium.extras

A few functionalities i required beyond the functions in the great (R Selenium)["https://github.com/ropensci/RSelenium"] package.


getElementAttributeValues(remDr, elem, excludeAttribute = "")

Get all attrivute values of a given element.

getElementWithDates(remDr)
Extract all dates from a page as elements.

getElementWithEntities(remDr, spacyModel = "de", entityType = "LOC_B")
Extract all elements given an entity.

clickElemen2(remDr, elem)

In case an element is not clickable with `$clickElement()`, the element can be clicked with `clickElemen2(remDr, elem)`. It is a wrapper for the javascript function `.click()`.

getElementFullXPathfunction(elem, excludeAttribute = "")

mapContainerPort(portNr, password)
