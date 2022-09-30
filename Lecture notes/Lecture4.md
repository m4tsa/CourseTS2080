*   Use case diagrams
    *   Define behavior without revealing internal logic/structure
    *   Actors
        *   Acts upon the user case
    *   High level function
    *   User point
    *   Set of actions
    *   Visualise functional requirements
        *   Logic
    *   Non-functional requirements
        *   Does not affect the functionality of the software
        *   Aesthetics
    *   Relationship of requirements
        *   Actors to the essential processes
        *   Relationship between use cases
    *   Don't crowd the use case diagram (use other diagrams for further interactions)
    *   Drawing
        *   System boundary defines the scope and limits of the system, usually represented with a rectangle
        *   Actors, entities that interacts with the system from outside the system boundary
            *   The entity can be an external person, process or thing
            *   Can inherit the role of another actor by pointing at it (Generalization)
        *   Use cases, represented within an oval shape within the system boundary
            *   Every business functionality is a potential use case
        *   Arrows (associations)
            *   No arrowhead(s) means bidirectional
            *   Extend, Use a dotted line with a hollow arrow with label extends to extend an use case with another by pointing to the use case being extended
                *   Can be triggered conditionally
                *   Should be independent too
                *   May
            *   Include relationships representations the invocation of a use case by another use case.
                *   The base use case is incomplete without the included use case
                *   The included use case is mandatory for the base use case to function
                *   Need to