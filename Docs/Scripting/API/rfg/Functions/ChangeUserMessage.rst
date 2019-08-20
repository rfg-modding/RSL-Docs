
ChangeUserMessage
********************************************************
Change the value of a pre-existing user message. Use `rfg.AddUserMessage`_ to create them.

**Arguments:**

**Handle** (`int`_)
    The handle of the user message you want to edit. This is returned by `rfg.AddUserMessage`_ when you create a user message.

**NewText** (`String`_)
    The new text to be displayed for the user message.

**Returns:**

**Handle** (`int`_)
    The handle of the user message you've edited. This shouldn't be different from the one you entered.

.. _`float`: ../Types/PrimitiveTypes.html#floating-point-types
.. _`String`: ../Types/PrimitiveTypes.html#string
.. _`bool`: ../Types/PrimitiveTypes.html#bool
.. _`int`: ../Types/PrimitiveTypes.html
.. _`MessageTypes`: ../Types/MessageTypes.html
.. _`rfg.AddUserMessage`: ./AddUserMessage.html