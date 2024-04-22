# Write blog on difference between document and window object

## The Window Object
Let's commence with an exploration of the window object. Within web browsers, the window object embodies the browser window housing the viewed document. It acts as the global entity for JavaScript code executing within a webpage. Here's a breakdown of the key facets of the window object:

Global Scope: All global JavaScript variables, functions, and objects manifest as properties of the window object. When a global variable or function is declared, it automatically becomes a property of the window object.
Browser Window Management: The window object furnishes methods and properties for managing the browser window, encompassing functionalities like resizing the window, spawning new windows or tabs, and navigating to diverse URLs.
Window Lifecycle Events: It oversees various events associated with the browser window's lifecycle, such as onload, onunload, onbeforeunload, and more. These events empower developers to execute JavaScript code at specific junctures during the loading, unloading, or navigation of a webpage.
Global Functions and Objects: The window object houses global functions and objects commonly utilized in JavaScript, including setTimeout(), setInterval(), console, localStorage, sessionStorage, and others.
## The Document Object
Next, let's dissect the document object. Serving as a representation of the HTML document loaded within the browser window, the document object furnishes an interface for manipulating the document's content and structure. Here's an overview of the pivotal aspects of the document object:

DOM Manipulation: The primary function of the document object is to interact with the Document Object Model (DOM) of the webpage, enabling access to and modification of elements, attributes, and content dynamically.
Element Selection: Through methods like getElementById(), getElementsByClassName(), getElementsByTagName(), and querySelector(), the document object facilitates the selection and retrieval of specific elements from the DOM.
Content Manipulation: The document object empowers developers to create new elements, alter existing ones, set attribute values, and manipulate text or HTML content within elements.
Event Handling: Additionally, the document object manages events pertaining to the document, such as DOMContentLoaded, click, mouseover, submit, allowing for responsive reactions to user interactions or changes in the document structure.
Key Differences
Although the document and window objects are indispensable components of web development, they serve disparate functions and possess unique attributes:

The window object embodies the browser window, offering access to browser-level functionalities and global variables.
In contrast, the document object represents the loaded HTML document within the browser window, facilitating manipulation of its content and structure via the DOM.