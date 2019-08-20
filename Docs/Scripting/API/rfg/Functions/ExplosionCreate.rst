
ExplosionCreate
********************************************************
Spawns an explosion.

**Arguments:**

**Info** (`ExplosionInfo`_)
    The properties of the explosion to be spawned. You can use `rfg.GetExplosionInfo`_ to get one of the games explosion presets, or iterate the preset list as shown in the `explosion examples`_.

**Position** (`Vector`_)
    The position to spawn the explosion in. 

**Alternative:**

**Info** (`ExplosionInfo`_ 
    The properties of the explosion to be spawned. You can use `rfg.GetExplosionInfo`_ to get one of the games explosion presets, or iterate the preset list as shown in the `explosion examples`_.

**x** (`float`_)
    The x position to spawn the explosion in.

**y** (`float`_)
    The y position to spawn the explosion in.

**z** (`float`_)
    The z position to spawn the explosion in.

**Alternative:**

**Info** (`ExplosionInfo`_)
    The properties of the explosion to be spawned.

**Source** (`Object`_)
    The source of the explosion.

**Owner** (`Object`_)
    The owner of the explosion.

**Position** (`Vector`_)
    The position to spawn the explosion in.

**Orientation** (`Matrix`_)
    The orientation to spawn the explosion at.

**Direction** (`Vector`_)
    The direction the explosion should point in. 

**Returns:**

- None

.. _`float`: ../Types/PrimitiveTypes.html
.. _`Vector`: ../Types/Vector.html
.. _`Matrix`: ../Types/Matrix.html
.. _`Object`: ../Types/Object.html
.. _`ExplosionInfo`: ../Types/ExplosionInfo.html
.. _`rfg.GetExplosionInfo`: ./GetExplosionInfo.html
.. _`explosion examples`: ../../../Examples/Explosions.html