
Useful values
************************
These are useful variables that the RSL finds at runtime and provides for use in scripts.

`Player`_ ``rfg.ActivePlayer`` or ``Player``: This is the player type instance. Allows you to easily access the player without needing to iterate the world object list and look for them.

`World`_ ``rfg.ActiveWorld`` or ``World``: The rfg world instance. Holds the global/world object list which you can loop through to manipulate and collect data on all the objects in the game world.

.. Document rfg.ActivePhysicsWorld here once it's bound. For now only the solver is bound since it has real uses.

`hkpSolverInfo`_ ``rfg.PhysicsSolver``: Contains values which influence the physics solvers behavior. You can already change these values in the physics tweaks gui. Be careful changing these if you want a stable game experience. The physics sim is in a very delicate balance and changing these values can easily make it unstable.

`ExplosionInfo`_ ``rfg.ExplosionInfos``: A list of the games explosion presets. You generally shouldn't edit these unless you intend to change an explosions properties globally. You can see examples on how to use this in `explosion examples`_.

`float`_ ``rfg.GameSpeedScale``: Default is ``1.0``. Affects the speed of animations, explosions, and movement. If set greater than ``1.0`` the game will move quicker, if set lower than ``1.0`` the game will move slower.

`float`_ ``rfg.MaxVehicleSpeed``: Default is ``40.23``. Sets the max vehicle speed enforced by the game. If increased vehicles won't immediately move faster. Their engine characteristics must also be changed to make them go faster. Use ``rfg.ResetMaxVehicleSpeed()`` to reset it.

`bool`_ ``rfg.UnlimitedAmmo``: Default is ``false``. If ``true``, the player will have unlimited ammo.

`int`_ ``rfg.ChargeExplosionDelay``: Number of milliseconds between remote charge explosions. Default is ``250``. 

`bool`_ ``rfg.SsaoVisionEnabled``: Default is ``false``. Whether or not SSAO vision is enabled. Visualizes the effect of SSAO on lighting and shadows.

`float`_ ``rfg.TimeScale``: Default is ``48.0``. Affects the rate of change of time of day. Does not affect physics, animations, or explosions, only time of day. Higher values make time of day pass more quickly. Use ``rfg.ResetTimeScale`` to reset this. Use ``rfg.DisableTodChange()`` to pause tod change by setting ``TimeScale`` to zero. Use ``rfg.EnableTodChange()`` to set it back to ``48.0``. Can also set manually if you don't want to use those helper functions.

`uint`_ ``rfg.CurrentDayTicks``: The current time of day value. Change this to change the time of day. Values range from 0 to 4,294,967,2965.


.. _`Player`: ./Types/Player.html
.. _`World`: ./Types/World.html
.. _`hkpSolverInfo`: ./Types/hkpSolverInfo.html
.. _`ExplosionInfo`: ./Types/ExplosionInfo.html
.. _`explosion examples`: ../../Examples/Explosions.html
.. _`float`: ./Types/PrimitiveTypes.html
.. _`int`: ./Types/PrimitiveTypes.html
.. _`uint`: ./Types/PrimitiveTypes.html
.. _`bool`: ./Types/PrimitiveTypes.html