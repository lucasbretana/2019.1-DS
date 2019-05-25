## Class Diagram Review
- one of the most used UML diagram
- describes the system classes (rectangles) and relation (many types) between them

- represent a static view of the system

- can have tree perspectives:
  * conceptual: does not need to have __ALL__ classes, only the more fundamental ones
    + no operations in this model
    + no class 
  * project: same as previous with a bit more details
  * implementation: a mirror of the system itself

- in the Conceptual Model
  * the class is a group of entities of project

### UML Class
```
  _____________________
  |   __Class Name__  |
  |___________________|
  |   _Atribbutes_    |
  |___________________|
  |   _Operations_    |
  |___________________|
```

- __attributes__: [visibility] <name> [multiplicity] : [type] = [value] [{properties}]

- __operations__: <name>(<{parameters}>

- **note**: the relationship amount the classes is similar to the DB relation
  * 1..\* <- means at least one and no upper bound
  * 0..\* <- no inferior or upper bounds
