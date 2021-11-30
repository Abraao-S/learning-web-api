# Node
- https://developer.mozilla.org/en-US/docs/Web/API/Node

- The DOM Node interface is an abstract base class upon which many other DOM API objects are based, thus letting those object types to be used similarly and often interchangeably. As an abstract class, there is no such thing as a plain Node object. All objects that implement Node functionality are based on one of its subclasses. Most notable are Document, Element, and DocumentFragment. 

## Node.appendChild()
- https://developer.mozilla.org/en-US/docs/Web/API/Node/appendChild

- The appendChild() method of the Node interface adds a node to the end of the list of children of a specified parent node. If the given child is a reference to an existing node in the document, appendChild() moves it from its current position to the new position (there is no requirement to remove the node from its parent node before appending it to some other node)

- This means that a node can't be in two points of the document simultaneously. So if the node already has a parent, the node is first removed, then appended at the new position. The Node.cloneNode() method can be used to make a copy of the node before appending it under the new parent. Copies made with cloneNode are not be automatically kept in sync.

- If the given child is a DocumentFragment, the entire contents of the DocumentFragment are moved into the child list of the specified parent node. 

- Note: Unlike this method, the Element.append() method supports multiple arguments and appending strings. You can prefer using it if your node is an element. 