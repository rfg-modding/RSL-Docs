
GetObject
********************************************************
Attempts to find a game object with the provided name or handle. Most objects don't have names, so the Handle overload is more useful.

**Arguments:**

**Name** (`String`_)
    The name of the object to find.

**Alternative:**

**Handle** (`unsigned int`_)
    The handle of the object to find.

**Returns:**

**Object** (`Object`_) 
    May be ``nil`` depending on if an object of the given name or handle is found.

.. _`Object`: ../Types/Object.html
.. _`unsigned int`: ../Types/PrimitiveTypes.html
.. _`String`: ../Types/PrimitiveTypes.html
