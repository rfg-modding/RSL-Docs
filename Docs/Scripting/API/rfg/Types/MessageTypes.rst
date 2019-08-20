
MessageTypes
========================================================
Used by `rfg.AddUserMessage`_ when creating new user messages. The exact differences between these have not been fully explored, but you should use ``rfg.MessageType.Other`` if you don't want the message to be positioned based on other visible messages. These are defined in ``./Core/rfg/MessageTypes.lua``.

================================== ==========
Access Variable                    Value     
================================== ==========
``rfg.MessageTypes.Swap``          0
``rfg.MessageTypes.MpKill``        1
``rfg.MessageTypes.MpKillShadow``  2
``rfg.MessageTypes.Other``         3        
================================== ==========

.. _`Object`: ./Object.html
.. _`Human`: ./Human.html
.. _`Zone`: ./Zone.html
.. _`Player`: ./Player.html
.. _`rfg.AddUserMessage`: ../Functions/AddUserMessage.html