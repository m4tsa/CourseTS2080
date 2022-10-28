*   Activity diagram
    *   Most used diagram (Maged)
    *   Presents flow of control in the system
    *   Emphasizes the condition of flow and the sequence it happens
    *   We can use an activity diagram to present the steps involving in executing a use case
    *   Pre-condition & Post-condition
        *   Start and end
        *   Pre is solid circle
        *   Post is outlined solid circle
    *   Actor input (direction on arrows)
    *   Alternative or Extension flow - Diamond (Decision → Merge)
    *   Parallel activities - Solid rectangle (Fork → Join)
    *   You can reference another activity diagram (Rectangle with paper corner on top right)
    *   Can be drawn with “vertical swim lanes” if it has multiple defined actors (Some may do "horizontal swim lanes)
    *   Acitivity diagram within a activity diagram “sub activity diagram” (Input and output parameter) (Not recommended)
    *   Signals
        *   Wait duration
        *   Double triangle
    *   Flows and edges
        *   Direct (Arrows)
        *   Connector (Circle with label) “teleports”
        *   Object node (square in the middle)
        *   Pins
        *   Just use arrows >.< -Maged
    *   Pins and transformations
        *   Pin for parameter
        *   Transformation expression (Drawn like reference diagram but marked with “transformation”)
    *   Flow chart vs Activity diagram
        *   Flow chart does not support parallel behavior
    *   Used when a number of things require some sort of coordination
*   Sequence diagrams
    *   Actual operations of an action
    *   Interaction between elements
    *   Detailed flow
    *   Interaction with messages over time used to explore logic of complex operations, functions or procedures.
    *   Sequence of interactions are represented in a step-by-step manner.
    *   Almost self-explanatory for software engineers
    *   Two dimensions
        *   Vertical dimension shows the sequence of messages in chronological order
        *   The horizontal dimension shows the object instances which the messages are sent
    *   Message with open arrowhead pointing at receiving class with an open arrowhead and label the name of the message on top
    *   Rectangles on the vertical line shows how long a something takes
    *   A lifetime represent an individual participant in the interaction
    *   Activation a thin rectangle on a lifetime which is the period the element is performing an operation
    *   Call message is a invocation of operation of the target lifeline (solid line /w arrow)
    *   Return message  is pass of information back to the caller (dotted line w/ arrow)
    *   Self-message calling invocation inside the same lifetime (class), invocation within
    *   Some may introduce alternate path within boxes based on a condition, this invalidates having a sequence :(
*   Sequence vs acitivity
    *   Sequence
        *   Sequence of calls
        *   Message flow from object to boject
        *   Behavior of several objects in a single use case
        *   Represent time order
    *   Activity
        *   Model the workflow
        *   Message flow from activity to activity
        *   Sequence of actions
        *   Represent the execution of the process