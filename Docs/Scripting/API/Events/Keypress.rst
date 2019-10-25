
Keypress
********************************************************
This event is triggered whenever a key is pressed or released. It's ``RegisterId`` is ``"Keypress"``.

EventData
========================================================

**KeyDown** (`bool`_)
    True if a key is being held down.

**KeyUp** (`bool`_)
    True if a key was just released.

**KeyCode** (`KeyCodes`_)
    The code of the key being pressed. Used to check which specifically which key is being pressed. See ``RSL/Core/rfg/KeyCodes.lua`` for a full list of keycodes.

**Control** (`bool`_)
    True if the ctrl button is being held down.

**ShiftDown** (`bool`_)
    True if the shift button is being held down.

**AltDown** (`bool`_)
    True if the alt button is being held down.

**WindowsDown** (`bool`_)
    True if the windows button is being held down.

.. _`bool`: ../rfg/Types/PrimitiveTypes.html
.. _`KeyCodes`: ../rfg/Types/KeyCodes.html