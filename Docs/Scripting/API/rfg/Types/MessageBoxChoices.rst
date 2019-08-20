
MessageBoxChoices
========================================================
Used by `rfg.AddMessageBox`_ so message box callback functions can receive user input on yes/no or accept/cancel style message boxes. These are defined in ``./Core/rfg/MessageBoxChoices.lua``.

====================================== ==========
Access Variable                        Value     
====================================== ==========
``rfg.MessageBoxChoices.Ok``           0
``rfg.MessageBoxChoices.Yes``          0 
``rfg.MessageBoxChoices.Accept``       0        
``rfg.MessageBoxChoices.Abort``        1        
``rfg.MessageBoxChoices.No``           1
``rfg.MessageBoxChoices.Cancel``       1
``rfg.MessageBoxChoices.ForcedExit``   2
``rfg.MessageBoxChoices.Invalid``      3
====================================== ==========

.. _`Object`: ./Object.html
.. _`Human`: ./Human.html
.. _`Zone`: ./Zone.html
.. _`Player`: ./Player.html
.. _`rfg.AddMessageBox`: ../Functions/AddMessageBox.html