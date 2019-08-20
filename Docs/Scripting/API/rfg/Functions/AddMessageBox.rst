
AddMessageBox
********************************************************
Adds a message box to the screen using RFGs UI system.

**Arguments:**

**Type** (`MessageBoxTypes`_)
    The type of message box to create (OK, yes/no, accept/cancel, etc, see `MessageBoxTypes`_ for more info).

**Title** (`String`_)
    The title of the message box.

**Description** (`String`_)
    The description/content of the message box.

**CallbackFunction** (Function) ``optional`` 
    A lua function which is used to process any user input for this message box. Useful for yes/no style message boxes that expect an option to be chosen. See the examples section for an example of how this works.

**Button1Override** (`String`_) ``optional`` 
    A custom name for the first button of the message box if you don't want the standard "yes" "no" "ok" labels.

**Button2Override** (`String`_) ``optional`` 
    A custom name for the second button of the message box.

**Returns:**

**Handle** (`int`_)
    The handle of the message box. Currently has no use.

**Examples:**

This example shows how to use a callback function to determine if the user selected yes or no on a yes/no message box:

.. code-block:: lua

    --This function is called when the user selects on of the message box options
    local function MyMboxCallback(CallbackData)
        if(CallbackData.Choice == rfg.MessageBoxChoices.Yes) then
            rsl.Log("Selected \"Yes\" option in the message box\n")
        elseif(CallbackData.Choice == rfg.MessageBoxChoices.No) then
            rsl.Log("Selected \"No\" option in the message box\n")
        end
    end

    --Create the message box, register it's callback function as the last arg
    rfg.AddMessageBox(rfg.MessageBoxTypes.YesNo, "Test message box", "Player pos: " .. Player.Position:ToString(), MyMboxCallback)

.. _`float`: ../Types/PrimitiveTypes.html#floating-point-types
.. _`String`: ../Types/PrimitiveTypes.html#string
.. _`bool`: ../Types/PrimitiveTypes.html#bool
.. _`int`: ../Types/PrimitiveTypes.html
.. _`MessageBoxTypes`: ../Types/MessageBoxTypes.html