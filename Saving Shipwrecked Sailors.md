= Saving Shipwrecked Sailors =


=== Best Practices ===
- When importing modules into a program, the preferred order is
    - the Python Standard Library modules
    - third-party modules
    - user-defined modules
- Assign constants, as per PEP8 Python style guide
    - constant names should be all caps
    - this doesn't make the variables truly immutable
    - but it does alert other developers that they shouldn't change them
- When defining a class the first letter of the class name should be capitalized.
    - list all the initial attribute values for an object under the `__init__()` method
        - this way users can see all the key attributes
        - the code will also be easier to read and update
    




=== Object Oriented Programing ===

- Attribute:
    - a named vallue associated with an object
    - if your object was a person, an attrubute could be:
        - height
        - weight
        - eyecolor
        - age
- Method:
    - attributes that also happen to be functions:
        - they are passed a reference to their instance when they are run
        - duble underscore methods are special built in methods:
            - 'dunder' `__init__()` method:
                - automatically invoked as soon as a new object is created
                - it binds the attributes of each newely created instance of a class
        
