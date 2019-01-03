# Fend notes - JavaScript and the DOM

## Selecting page elements

* Selecting An Element By ID  
  `document.getElementById('idName');`
* Selecting Elements By Their Class  
  `document.getElementsByClassName('className');`
* Selecting Elements By Their Tag  
  `document.getElementsByTagName('tagName');`
* The querySelector  
  `document.querySelector()`   
  // _returns a single element_
* The querySelectorAll  
  `document.querySelectorAll();`   
  // _returns a list of elements_

## Update Existing Page Content
   * .innerHTML
   * .outerHTML
   * .textContent
   * .innerText

## Add New Page Content
  * .createElement()
  * .appendChild()
  * .createTextNode()
  * .insertAdjacentHTML()

## Remove Page Content
  * .removeChild(
  * .remove()
  * .firstChild
  * .firstElementChild
  * .parentElement

## Style Page Content
  * .style.<property>
  * .cssText()
  * .setAttribute()
  * .className
  * .classList

## Respond to Events
  * .addEventListener()
  * .removeEventListener()
  * .dispatchEvent()
