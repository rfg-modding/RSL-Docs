
AddUserMessage
********************************************************
Creates a new user message in the specified position on the screen. Has no animation or sound, so it's useful for data that frequently changes

**Arguments:**

**Text** (`String`_)
    The text to be displayed.

**PositionX** (`float`_)
    The x position of the text on the screen. Uses normalized coordinates, so for example, 0.5 would be the middle of the screen.

**PositionX** (`float`_)
    The y position of the text on the screen. Uses normalized coordinates, so for example, 0.5 would be the middle of the screen.

**Outlined** (`bool`_)
    Whether or not the message should be surrounded with a grey rectangle.

**Lifespan** (`float`_)
    The time in seconds that the message should be on screen.

**Type** (`MessageTypes`_)
    The type of user message. The exact differences between these have not been fully explored, but you should use ``rfg.MessageType.Other`` if you don't want the message to be positioned based on other visible messages.

**Returns:**

**Handle** (`int`_)
    The handle of the new user message. Can be used to update the messages text or to delete it.

.. _`float`: ../Types/PrimitiveTypes.html#floating-point-types
.. _`String`: ../Types/PrimitiveTypes.html#string
.. _`bool`: ../Types/PrimitiveTypes.html#bool
.. _`int`: ../Types/PrimitiveTypes.html
.. _`MessageTypes`: ../Types/MessageTypes.html