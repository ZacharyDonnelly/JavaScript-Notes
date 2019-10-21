# Notes

# Basic DOM

Use innerHTML for creating new elements.
Use insertAdjascentHTML for more secure.
Use textContent for inside text.

# Local Storage

Stores in brower until hard reload/localstorage.clear(). Can be used to store data that will persist through a soft refresh.
Syntax is similiar to objects with dot notation.
The read-only localStorage property allows you to access a Storage object for the Document's origin; the stored data is saved across browser sessions. localStorage is similar to sessionStorage, except that while data stored in localStorage has no expiration time, data stored in sessionStorage gets cleared when the page session ends — that is, when the page is closed.

It should be noted that data stored in either localStorage or sessionStorage is specific to the protocol of the page.

The keys and the values are always strings (note that, as with objects, integer keys will be automatically converted to strings).
