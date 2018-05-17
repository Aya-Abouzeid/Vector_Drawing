# Vector_Drawing

## Description:

Geometric shapes belong to different groups (ex: Elliptical Shapes, Polygons, …etc). Members of these different groups are related to each other in the sense that they share common properties. In order to be able to implement an efficient and object oriented drawing application. It is essential to design a model that takes these relations into consideration.

## Specs:

- An object oriented model that covers the following geometric shapes: 
```R
      Line Segment,
      Circle, Ellipse,
      Triangle, 
      Rectangle,
      Square.
  ```
- A UML Class diagram that represents the model, showing all the classes, attributes and methods.

- The concepts of inheritance and polymorphism were applied to the design.

- A GUI that allows the following functionalities for the user on all the shapes defined earlier:
```R
      Draw Color,
      Resize,
      Move,
      Delete.
      undo
      redo
 ```
- The cursor is used to select the location of a shape while drawing it, or moving it to another location.

- When an object is selected, its appearance change such that the user understands that it is selected. This is done by a dotted rectangle that shows up around it.

- The user is allowed to group objects to resize, move or delete together as one object.

- An option is included in GUI to save the drawing in XML and JSON file and user must choose where to save the file.

- User can load previously saved drawings and modify the shapes.
