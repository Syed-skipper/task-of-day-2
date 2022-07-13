The Difference Between Window and Document Object :
         
Web browser is made up of hierarchy of objects. At the root level we have a window object.

WINDOW OBJECT : 1. It is the root level element in any web page.
                2. All the global variables are defined on the window object.
                3. For example, alert(), confirm() are methods defined on the window object.
                4. Writing alert() is similar to window.alert()
                5. Also, properties like document, location are properties of the window object.
         
DOCUMENT OBJECT : 1. It is the direct child of the window object. It is aka Document Object Model (DOM).
                  2. You can access it via window.document or document.
                  3. document object has many useful methods defined on it.For example, document.getElementById(), document.getElementByTagName(),                                          document.createElement(), document.querySelector() and many more
