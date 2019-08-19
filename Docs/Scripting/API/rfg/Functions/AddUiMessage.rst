
AddUiMessage
********************************************************
Creates a new ui message in the top left corner of the screen. Suitable for one-off messages, not suitable for constantly changing information.

**Arguments:**

- `String`_ **Info**: The message to be displayed.

- `float`_ **DisplayTime**: ``optional`` The amount of time in seconds to display the message for. Default value is ``3.0`` if not specified.

- `bool`_ **UseSecondaryAnim**: ``optional`` Whether or not to animate the background of the message. Default is ``false`` if not specified.

- `bool`_ **ForceRedisplay**: ``optional`` Unknown purpose. Default is ``false`` if not specified.

**Returns:**

- None

**Examples:**

.. code-block:: lua

    --Call it with no optional arguments
    rfg.AddUiMessage("Player position: " .. Player.Position:ToString())
    --Call it with the DisplayTime optional arg
    rfg.AddUiMessage("Player position: " .. Player.Position:ToString(), 8.0)
    --Call it with the UseSecondaryAnim optional arg to animate the message
    rfg.AddUiMessage("Player position: " .. Player.Position:ToString(), 8.0, true)


.. _`float`: ../Types/PrimitiveTypes.html#floating-point-types
.. _`String`: ../Types/PrimitiveTypes.html#string
.. _`bool`: ../Types/PrimitiveTypes.html#bool