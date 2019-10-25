
FrameUpdate
********************************************************
This event is triggered every single frame. This makes it the most performance heavy event. Prefer using other events when 
possible since they will likely be more selectively triggered instead of being every frame. It's ``RegisterId`` is ``"FrameUpdate"``.

EventData
========================================================

**Frametime** (`float`_)
    The time since the last frame.

.. _`float`: ../rfg/Types/PrimitiveTypes.html