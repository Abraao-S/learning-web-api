# GlobalEventHandlers
- https://developer.mozilla.org/en-US/docs/Web/API/GlobalEventHandlers

- The GlobalEventHandlers mixin describes the event handlers common to several interfaces like HTMLElement, Document, or Window. Each of these interfaces can, of course, add more event handlers in addition to the ones listed below.

- Note: GlobalEventHandlers is a mixin and not an interface; you can't actually create an object of type GlobalEventHandlers.
  
## Event handlers
 
 ### These event handlers are defined on the GlobalEventHandlers mixin, and implemented by HTMLElement, Document, Window, as well as by WorkerGlobalScope for Web Workers.

- GlobalEventHandlers.onsubmit: Is an event handler representing the code to be called when the submit event is raised.
