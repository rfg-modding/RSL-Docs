
.. attention:: This page is incomplete and needs better descriptions and research into the behavior of the variables.


Vehicle
********************************************************
Vehicle object. Flyers, automobiles, and walkers are all vehicle objects. They each have their own classes which inherit ``Vehicle``. Only `Flyer`_ has been binded so far.

Inherits `object`_

Variables
========================================================

**SpawnPriority** (`ObjectSpawnPriorities`_)
    Unknown value.

**Info** (`VehicleInfo`_)
    Unknown value.

**LastPos** (`Vector`_)
    Unknown value.

**LastOrient** (`Matrix`_)
    Unknown value.

**LastVelocity** (`Vector`_)
    Unknown value.

**LastAngularVelocity** (`Vector`_)
    Unknown value.

**ForwardVelocity** (`float`_)
    Unknown value.

**LastForwardVelocity** (`float`_)
    Unknown value.

**AimHandle** (`int`_)
    Unknown value.

**LastAnimTransform** (`Matrix43`_)
    Unknown value.

**PfFailureTimeout** (`Timestamp`_)
    Unknown value.

**DisableForNpcDriversTimer** (`Timestamp`_)
    Unknown value.

**NoNpcEntryTimer** (`Timestamp`_)
    Unknown value.

**RenderDistance** (`ObjectRenderDistance`_)
    Unknown value.

**SeatInfo** (`unsigned int[11]`_)
    Unknown value.

**NumTurretMounts** (`int`_)
    Unknown value.

**BombStatus** (`VehicleBombStatuses`_)
    Unknown value.

**WalkerVelocityHack** (`Timestamp`_)
    Unknown value.

**WalkerVelocityHackFollowup** (`Timestamp`_)
    Unknown value.

**WalkerThrownEnergyScaled** (`Timestamp`_)
    Unknown value.

**SavedAngularDampening** (`float`_)
    Unknown value.

**WalkerVehicleCollisions** (`int`_)
    Unknown value.

**VehicleVsBuildingDamage** (`Timestamp`_)
    Unknown value.

**NumDamageEvents** (`int`_)
    Unknown value.

**CorpseTimer** (`Timestamp`_)
    Unknown value.

**CorpseAbsoluteLongestTimer** (`Timestamp`_)
    Unknown value.

**OnFireTimestamp** (`Timestamp`_)
    Unknown value.

**CorpseEffect** (`unsigned int`_)
    Unknown value.

**ExhaustEffectNormal** (`unsigned int[4]`_)
    Unknown value.

**ExhaustEffectBurst** (`unsigned int[4]`_)
    Unknown value.

**Flags** (`VehicleFlags`_)
    Unknown value.

**TurretAutofireMs** (`int`_)
    Unknown value.

**NumSubPieces** (`unsigned int`_)
    Unknown value.

**StreamPlacementFlags** (`VehicleSpawnFlags`_)
    Unknown value.

**KillerHandle** (`unsigned int`_)
    Unknown value.

**MostRecentDriver** (`unsigned int`_)
    Unknown value.

**TeamOfMostRecentDriver** (`HumanTeams`_)
    Unknown value.

**MostRecentDriverExitTime** (`Timestamp`_)
    Unknown value.

**DamageSoundPropagateTimer** (`Timestamp`_)
    Unknown value.

**KillerWeapon** (`WeaponInfo`_)
    Unknown value.

**RammingDamageTaken** (`int`_)
    Unknown value.

**ElectricalDamagePercent** (`float`_)
    Unknown value.

**DamagePercent** (`float`_)
    Unknown value.

**DamageFuncHandle** (`unsigned int16`_)
    Unknown value.

**DestroyFuncHandle** (`unsigned int16`_)
    Unknown value.

**OnEnterFuncHandle** (`unsigned int16`_)
    Unknown value.

**OnExitFuncHandle** (`unsigned int16`_)
    Unknown value.

**OnTakeDamageHandle** (`unsigned int16`_)
    Unknown value.

**OnCollisionHandle** (`unsigned int16`_)
    Unknown value.

**OnHitPedHandle** (`unsigned int16`_)
    Unknown value.

**ReservedBy** (`unsigned int`_)
    Unknown value.

**SoundDelayAfterExplosion** (`Timestamp`_)
    Unknown value.

**FireDamageRate** (`float`_)
    Unknown value.

**FireFractionalDamage** (`float`_)
    Unknown value.

**FadeTimer** (`Timestamp`_)
    Unknown value.

**FadeTime** (`int`_)
    Unknown value.

**EmergencyLightTimer** (`Timestamp`_)
    Unknown value.

**StreamLoadDistanceSqr** (`float`_)
    Unknown value.

**StreamUnloadDistanceSqr** (`float`_)
    Unknown value.

**EngineInst** (`int`_)
    Unknown value.

**EngineStartedInst** (`int`_)
    Unknown value.

**EngineHighLoadStartTimer** (`Timestamp`_)
    Unknown value.

**PassByPlayId** (`int`_)
    Unknown value.

**PassByDistance** (`float`_)
    Unknown value.

**NavCellDetourRequestHandle** (`unsigned int`_)
    Unknown value.

**NavCellDetourComponentRequestHandles** (`unsigned int[8]`_)
    Unknown value.

**NumNavCellDetourComponentRequestHandles** (`unsigned int`_)
    Unknown value.

**LastDamageReported** (`float`_)
    Unknown value.

**SpawnNodeHandle** (`unsigned int`_)
    Unknown value.

**SquadHandle** (`unsigned int`_)
    Unknown value.

**VehicleCheckCoverTimestamp** (`Timestamp`_)
    Unknown value.

**VehicleCoverTimestamp** (`Timestamp`_)
    Unknown value.

**VehicleCoverCreationPos** (`Vector`_)
    Unknown value.

**VehicleCheckCoverIndex** (`int`_)
    Unknown value.

**VehicleCoverIndex** (`int`_)
    Unknown value.

**InfiniteMass** (`bool`_)
    Unknown value.

**ExtraMass** (`bool`_)
    Unknown value.

**ExtraMassValue** (`float`_)
    Unknown value.

.. _`ObjectSpawnPriorities`: ./ObjectSpawnPriorities.html
.. _`VehicleInfo`: ./VehicleInfo.html
.. _`Vector`: ./Vector.html
.. _`Matrix`: ./Matrix.html
.. _`float`: ./PrimitiveTypes.html
.. _`int`: ./PrimitiveTypes.html
.. _`Matrix43`: ./Matrix43.html
.. _`Timestamp`: ./Timestamp.html
.. _`ObjectRenderDistance`: ./ObjectRenderDistance.html
.. _`VehicleBombStatuses`: ./VehicleBombStatuses.html
.. _`unsigned int`: ./PrimitiveTypes.html
.. _`unsigned int[4]`: ./PrimitiveTypes.html
.. _`VehicleFlags`: ./VehicleFlags.html
.. _`VehicleSpawnFlags`: ./VehicleSpawnFlags.html
.. _`HumanTeams`: ./HumanTeams.html
.. _`WeaponInfo`: ./WeaponInfo.html
.. _`unsigned int16`: ./PrimitiveTypes.html
.. _`unsigned int[8]`: ./PrimitiveTypes.html
.. _`bool`: ./PrimitiveTypes.html
.. _`object`: ./object.html
.. _`Flyer`: ./Flyer.html