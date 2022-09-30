*   Class diagrams
    *   Templates for creating an object
    *   Show relationships
    *   Show inheritance, show abstraction, show encapsulation
    *   Describes the types of objects that will be created
    *   Attributes of the classes (Any variable that is bound in a class)
    *   Operations of class that can occur
    *   Relationships between these objects
    *   Diagram structure (Box, Separated by HR inside)
        *   Name (header)
        *   Attributes
        *   Methods
    *   Association
        *   Relationships between classes
            *   A and B can call each other.
        *   Solid line between two classes, source class to target class. Name of the property goes at the target end of the association, together with its multiplicity
        *   Multiplicity
            *   Type A: One
            *   Type B: Zero or one
            *   Type C: Zero or more
    *   Generalization
        *   Abstract base class
            *   Write class name in itallics
            *   Partially implement or not implement at all
            *   Methods in an abstract class can be both abstract and concrete
        *   A implements B
        *   Dotted line with outlined triangle on end with base class
    *   Composition
        *   A has an instance of B
        *   B cannot exist without A
        *   Drawn with diamond on side of A
    *   Aggregation
        *   A “has-an” instance of B. B can exist without A
        *   Drawn with outlined diamond on side of A
        *   Meaningless in UML? Try to solve with multiplicity or unidirectional arrows first