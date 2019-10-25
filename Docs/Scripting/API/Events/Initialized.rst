
Initialized
********************************************************
This event is triggered the first time that a save is loaded. It's only triggered once per session of the game. 
For it to trigger again you must restart the game. It's a useful way to activate your mods/scripts as once this event is triggered all 
game values and state should fully be initialized and ready for use. If you run your script immediately in your ``main.lua`` the values
it relies on may not be initialized yet.  It's ``RegisterId`` is ``"Initialized"``.

EventData
========================================================
This event has no data.

Examples
========================================================
Below is a simple example of simple mod that disables fog when the game runs and which utilizes this event. 
This script would be placed in a file named ``main.lua`` so its automatically loaded when the RSL starts.

.. code-block:: lua

    --This function will be called once when the Initialized event is triggered
    --This happens when the first save is loaded. By then, all lua values and 
    --functions are safe to use.
    function StartScript(EventData)
        rfg.HideFog()
    end

    rfg.RegisterEvent("Initialized", StartScript, "Hide fog script initializer")
