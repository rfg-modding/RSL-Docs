
Script events
********************************************************
The RSL supports binding lua functions to different events. This allows you to have functions that run when certain things such as mouse clicks or keypresses occur. There's also a per-frame event available for anything the other events don't cover, but it's preferred to use more specific events when possible. See the `Events page`_ for a list of events that can be used in scripts currently.

Registering events
--------------------------------------------------------
Below is an example of how to register a lua function to be called when an event occurs. In this case, we're using a ``Keypress`` event to detect when the q key is pressed and toggle the hud.

.. code-block:: lua

    --This function will be called each time the event it's registered to is triggered
    --EventData will contain the data specific to that event
    --In this case, it's info on what keys are being pressed
    function MyKeypressEvent(EventData)
        if(EventData.KeyCode == rfg.KeyCodes.q) then
            rsl.Log("q pressed! Toggling Hud\n")
			rfg.ToggleHud()
        end
    end

    --First arg is the type of event to register the func to
    --^Also known as the "RegisterId"
    --Second arg is the function to register
    --Third arg is just a label for the event viewer. Useful for debugging.
    rfg.RegisterEvent("Keypress", MyKeypressEvent, "ToggleHud keypress event hook")

So, the process for using events is simple. 
1. Choose your event type.
2. Write a function that you want to be called each time that event is triggered.
3. Register your function with that event.

.. _`Events page`: ../API/Events.html