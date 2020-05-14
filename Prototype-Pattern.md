This is used when the type of object to create is determined by a prototypical instance which is cloned to produce a new instance. Often, this pattern is used to get the unique instance of same object.
It is used to create duplicate objects without giving a performance hit, and is used when new object creation is costly. For example: Object to be created by a database call. In layman term, this pattern helps in cloning of the objects

## Concepts :
 - This avoid costly object creation.
 - Prototypes avoid subclassing, we generally create instance of actual prototype that we are trying to clone.
 - Doesn't use `new` keyword.
 - Often uses interfaces.
 - Usually implemented using registry, a new object is created and kept in a registry. When another object is reqd, clone of the object is created from the registry.
 - 
