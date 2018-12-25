# fend notes - JavaScript and the DOM

## Selecting page elements

### Selecting An Element By ID
`document.getElementById('idName');`

### Selecting Elements By Their Class
`document.getElementsByClassName('className');`

### Selecting Elements By Their Tag
`document.getElementsByTagName('tagName');`

### The querySelector
`document.querySelector()`
_returns a single element_

### The querySelectorAll
`document.querySelectorAll();`
_returns a list of elements_

## Update Existing Page Content
`const selection = document.querySelector('.className');`
`selection.textContent = "This is the new text";`
