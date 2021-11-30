# EventTarget
- https://developer.mozilla.org/en-US/docs/Web/API/EventTarget

-  The EventTarget interface is implemented by objects that can receive events and may have listeners for them. In other words, any target of events implements the three methods associated with this interface.

Element, and its children, as well as Document and Window, are the most common event targets, but other objects can be event targets, too. For example XMLHttpRequest, AudioNode, and AudioContext are also event targets.

Many event targets (including elements, documents, and windows) also support setting event handlers via onevent properties and attributes.

## Constructor:
- ### EventTarget()
    Creates a new EventTarget object instance.

## Methods:
- ### EventTarget.addEventListener()
    Registers an event handler of a specific event type on the EventTarget.

- ### EventTarget.removeEventListener()
    Removes an event listener from the EventTarget.

- ### EventTarget.dispatchEvent()
    Dispatches an event to this EventTarget.