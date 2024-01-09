# What is Dom in JS?

## The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

![](./dom.jpg)

# The dom tree structure..
## The DOM represents a document with a logical tree. Each branch of the tree ends in a node, and each node contains objects. DOM methods allow programmatic access to the tree. With them, you can change the document's structure, style, or content.

![](./dom-tutorial.webp )

# Method Dom

## innerHTML - Это свойство предоставляет простой способ полностью заменить содержимое элемента. Например, все содержимое элемента body может быть удалено:

##  createElement(elementName): Creates an html element whose tag is passed as a parameter. Returns the created element

## add( String [,String] ) Adds the specified classes to the element
## remove( String [,String] ) 
## Removes the specified classes from the element toggle(String[, Boolean]) If the element has no class, it adds it, otherwise it removes it. When false is passed as the second parameter, it removes the specified class, and if true, it adds it.