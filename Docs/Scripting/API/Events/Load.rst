
Load
********************************************************
This event is triggered every time a save is loaded. Note that every time the player dies a save is loaded, so this 
can also be used as a "AfterPlayerDies" style event. Eventually an explicit event for the player dying may be added 
too if this isn't specific enough. It's ``RegisterId`` is ``"Load"``.

Note the difference between this and `Initialized`_. This event is triggered every time a save is loaded, while `Initialized`_ is triggered
only when the first save is done loading. `Initialized`_ is useful for one time script/mod activation and other things that should only happen
once while this is useful for something that should be updated each time a save is loaded. 

If you're using user messages to display data you'll need to have one of these events to regenerate them,
as the game removes them each time a save is loaded.

EventData
========================================================
This event has no data.

.. _`Initialized`: ./Initialized.html