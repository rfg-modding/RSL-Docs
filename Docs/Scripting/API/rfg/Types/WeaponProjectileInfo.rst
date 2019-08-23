
WeaponProjectileInfo
********************************************************
Properties of the projectiles used by a given weapon. Used in the `WeaponInfo`_ type.

Variables
========================================================

**StartSpeed** (`float`_)
    The initial speed of the projectile in m/s.

**MaxSpeed** (`float`_)
    The max speed of the projectile in m/s.

**Acceleration** (`float`_)
    The acceleration of the projectile in m/s^2.

**FuseTime** (`unsigned int16`_)
    The time that must pass before the projectile can explode if explosion.

**MaxThrowDist** (`float`_)
    The max distance the projectile can be thrown in meters.

**Gravity** (`float`_)
    The strength of gravity for the projectile (separate from global gravity) in m/s^2.

**Sound** (`int`_)
    Unknown value. Likely the handle for the sound the projectile uses.

**Effect1** (`unsigned int`_)
    The id of the first effect the projectile uses.

**Effect2** (`unsigned int`_)
    The id of the second effect the projectile uses.

**Effect3** (`unsigned int`_)
    The id of the third effect the projectile uses.

**Effect4** (`unsigned int`_)
    The id of the fourth effect the projectile uses.

**Flags** (`unsigned int`_)
    Unknown value.

**InaccurateFlight** (`float`_)
    Unknown value.

**TimeUntilPropelled** (`float`_)
    The time in seconds before the projectile starts getting accelerated.

**TimeUntilPropExpire** (`float`_)
    Unknown value. Possibly the time until the projectiles propellant expires.

**TimeUntilDrop** (`float`_)
    The time in seconds before the projectile starts falling towards the ground.

**DamageEffect** (`unsigned int`_)
    Unknown value.

.. _`float`: ./PrimitiveTypes.html
.. _`unsigned int16`: ./PrimitiveTypes.html
.. _`int`: ./PrimitiveTypes.html
.. _`unsigned int`: ./PrimitiveTypes.html
.. _`WeaponInfo`: ./WeaponInfo.html