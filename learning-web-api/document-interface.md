# Document
- https://developer.mozilla.org/en-US/docs/Web/API/Document

- The Document interface represents any web page loaded in the browser and serves as an entry point into the web page's content, which is the DOM tree.
  
- The Document interface describes the common properties and methods for any kind of document. Depending on the document's type (e.g. HTML, XML, SVG, …), a larger API is available: HTML documents, served with the "text/html" content type, also implement the HTMLDocument interface, whereas XML and SVG documents implement the XMLDocument interface.


## Constructor:
### Document()
- Creates a new Document object.


## Methods:
### Document.querySelector()
- https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector

- The Document method querySelector() returns the first Element within the document that matches the specified selector, or group of selectors. If no matches are found, null is returned.The parameter for this method should be a DOMString containing one or more selectors to match. This string must be a valid CSS selector string; if it isn't, a SyntaxError exception is thrown.

- Syntax: element = document.querySelector(selectors);

### Document.getElementById()
- https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById

- The Document method getElementById() returns an Element object representing the element whose id property matches the specified string. If you need to get access to an element which doesn't have an ID, you can use querySelector() to find the element using any selector.

- Syntax: var element = document.getElementById(id);

- Unlike some other element-lookup methods such as Document.querySelector() and Document.querySelectorAll(), getElementById() is only available as a method of the global document object, and not available as a method on all element objects in the DOM. Because ID values must be unique throughout the entire document, there is no need for "local" versions of the function.

### Document.createElement()
- https://developer.mozilla.org/en-US/docs/Web/API/Document/createElement

- In an HTML document, the document.createElement() method creates the HTML element specified by tagName, or an HTMLUnknownElement if tagName isn't recognized.

- Syntax: let element = document.createElement(tagName[, options]);
