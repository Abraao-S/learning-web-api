# Storage
- https://developer.mozilla.org/en-US/docs/Web/API/Storage

- The Storage interface of the Web Storage API provides access to a particular domain's session or local storage. It allows, for example, the addition, modification, or deletion of stored data items.

## Properties:
### Storage.length  //read only
- Returns an integer representing the number of data items stored in the Storage object.

## Methods:
### Storage.key()
- When passed a number n, this method will return the name of the nth key in the storage.

### Storage.getItem()
- When passed a key name, will return that key's value.

### Storage.setItem()
- https://developer.mozilla.org/en-US/docs/Web/API/Storage/setItem

- When passed a key name and value, will add that key to the storage, or update that key's value if it already exists.

### Storage.removeItem()
- When passed a key name, will remove that key from the storage.

### Storage.clear()
- When invoked, will empty all keys out of the storage.
