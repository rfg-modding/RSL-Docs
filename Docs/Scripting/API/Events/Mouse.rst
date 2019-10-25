
Mouse
********************************************************
This event is triggered whenever the mouse is moved or the scroll wheel is scrolled. It's ``RegisterId`` is ``"Mouse"``.

EventData
========================================================

**Scrolled** (`bool`_)
    True if the mouse wheel has been scrolled.

**ScrollDelta** (`int`_)
    If the mouse wheel has been scrolled this is how much it's been scrolled and in what direction. Otherwise this is 0.

**MouseMove** (`bool`_)
    True if the mouse has been moved.

**MouseX** (`int`_)
    The x position of the mouse in screen coordinates.

**MouseY** (`int`_)
    The y position of the mouse in screen coordinates.

**Control** (`bool`_)
    True if the ctrl button is being held down.

**ShiftDown** (`bool`_)
    True if the shift button is being held down.

**AltDown** (`bool`_)
    True if the alt button is being held down.

**WindowsDown** (`bool`_)
    True if the windows button is being held down.

.. _`bool`: ../rfg/Types/PrimitiveTypes.html
.. _`int`: ../rfg/Types/PrimitiveTypes.html
.. _`KeyCodes`: ../rfg/Types/KeyCodes.html