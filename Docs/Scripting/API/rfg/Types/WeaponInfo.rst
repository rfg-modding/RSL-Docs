
WeaponInfo
********************************************************
Values used to determine a weapon types behavior. To access this type you should use the `WeaponInfo`_ list ``rfg.WeaponInfos``. See the example scripts ``WeaponInfoTest1.lua`` and ``WeaponInfoTest2.lua`` in ``RSL/Scripts/Included scripts/`` for examples of how this can be done (included in each release). Note that when you edit a `WeaponInfo`_ instance, that you're editing the behavior of all weapons based off of that, unless you make your own copy of it.

Variables
========================================================

**Name** (`String`_)
    The instances name.

**NameCrc** (`ChecksumStri`_)
    The CRC checksum for the name.

**UniqueId** (`int`_)
    The unique id of this instance.

**Flags** (`WeaponInfoFlags`_)
    Flags which determine additional behavior of the weapon.

**WeaponClass** (`WeaponClasses`_)
    The weapon class.

**WeaponInvItemInfo** (`InvItemInfo`_)
    The weapons inventory info.

**DefaultTeam** (`HumanTeams`_)
    The default team for this instance.

**IconName** (`String`_)
    The name of the icon used. May be ``nil``.

**SmallIconName** (`String`_)
    The name of the small icon used. May be ``nil``.

**ReticuleName** (`String`_)
    The name of the reticule used. May be ``nil``.

**FineAimReticuleName** (`String`_)
    The name of the fine aim reticule used. May be ``nil``.

**WeaponAnimGroup** (`AnimationGroups`_)
    The animation group for this weapon.

**MuzzleFlashEffect** (`unsigned int`_)
    The id for the muzzle flash effect.

**MuzzleSmokeEffect** (`unsigned int`_)
    The id for the muzzle smoke effect.

**SpecialHitEffect** (`unsigned int`_)
    Unknown value.

**SpecialEffect** (`unsigned int`_)
    Unknown value.

**SecondarySpecialEffect** (`unsigned int`_)
    Unknown value.

**OverheatedEffect** (`unsigned int`_)
    The id for the overheating effect.

**TracerEffect** (`unsigned int`_)
    The id for the tracer effect.

**FireCameraShakeIgnoreDisabled** (`bool`_)
    Unknown value.

**AttachmentPoint** (`String`_)
    Unknown value.

**FireSound** (`int`_)
    The id for the fire sound.

**SecondarySound** (`int`_)
    The id for the secondary fire sound.

**UpgradeSound** (`int`_)
    The id for the upgrade sound.

**ReloadSound** (`int`_)
    The id for the reload sound.

**ReloadSoundDelay** (`int`_)
    The delay for the reload sound in unknown units.

**NoAmmoSound** (`int`_)
    The id for the no ammo sound.

**SpecialSound** (`int`_)
    Unknown value.

**FlybySound** (`int`_)
    The id for the bullet fly by sound.

**NumWeaponPersonas** (`int`_)
    Unknown value.

**NpcFireSounds[16]** (`int`_)
    Unknown value.

**MaxRange** (`float`_)
    The max range in meters for the weapon.

**RedRange** (`float`_)
    Unknown value.

**MaxEngagementDist** (`float`_)
    Unknown value.

**MinEngagementDist** (`float`_)
    Unknown value.

**MaxAiPenetratingDist** (`float`_)
    Unknown value.

**TriggerType** (`TriggerTypes`_)
    The trigger type (automatic/single).

**AmmoType** (`AmmoTypes`_)
    The ammo type (electric, bullet, projectile, etc).

**MagazineSize** (`unsigned int16`_)
    Magazine size.

**MagazineStartNum** (`unsigned int16`_)
    The starting number of rounds in a magazine.

**MaxRounds** (`unsigned int16`_)
    The max rounds carried.

**MaxRoundsUpgrade** (`unsigned int16`_)
    Unknown value.

**AmmoBoxRestock** (`unsigned int16`_)
    The amount of rounds to be restocked by an ammo box.

**ToMinSpread** (`unsigned int16`_)
    Unknown value.

**ToMaxSpread** (`unsigned int16`_)
    Unknown value.

**MeleeGroupIndex** (`int8`_)
    Unknown value.

**BulletGroupIndex** (`int8`_)
    Unknown value.

**TracerFrequency** (`int8`_)
    Unknown value.

**ShotsPerRound** (`int8`_)
    Unknown value.

**FiringSoundRadius** (`float`_)
    The radius in meters that the weapon can be heard firing from.

**NpcRefireDelay** (`float`_)
    The delay between shots for NPCs in seconds.

**DefaultRefireDelay** (`float`_)
    The delay between shots for the player in seconds.

**PrefireDelay** (`float`_)
    Unknown value.

**DefaultReloadDelay** (`int`_)
    Unknown value.

**LowScaleDamage** (`DamageScalingInfo`_)
    Unknown value.

**HighScaleDamage** (`DamageScalingInfo`_)
    Unknown value.

**ExplosionInfo** (`ExplosionInfo`_)
    The explosion that should be created when this weapons rounds impact. Will be ``nil`` if there's no explosion for this weapon.

**AiExplosionInfo** (`ExplosionInfo`_)
    An optional separate explosion that is used for AI. May be ``nil``.

**FireConeDot** (`float`_)
    The angle of the fire cone. Range should be from ``0.0`` to ``1.0``. At ``1.0`` the fire cone is perfectly accurate, firing exactly where you point, at ``0.0`` it's a 180 degree cone.

**EvenSpreadAccuracyDot** (`float`_)
    Unknown value.

**MaxSpread** (`float`_)
    The maximum spread of the weapons rounds. Units if any are unknown.

**MinSpread** (`float`_)
    The minimum spread of the weapons rounds. Units if any are unknown.

**FineAimMaxSpread** (`float`_)
    The max spread when in fine aim mode.

**FineAimMinSpread** (`float`_)
    The min spread when in fine aim mode.

**NpcMaxSpread** (`float`_)
    The max spread for NPCs.

**NpcMinSpread** (`float`_)
    The min spread for NPCs.

**SpreadMultiplierRun** (`float`_)
    The number spread should be multiplied by if you're running. If this is greater than ``1.0`` then your spread will increase while running.

**RagdollForceShoot** (`float`_)
    The amount of force to apply to a ragdoll when shot by this weapon. Units unknown, but likely in newtons.

**RagdollChance** (`float`_)
    The chance that getting hit by this weapon will cause the target to ragdoll.

**RecoilCameraKick** (`float`_)
    How much the camera should react to recoil.

**RecoilImpulse** (`float`_)
    Unknown value. Likely the impulse that should be applied to the player when this is fired.

**OutOfAmmoReloadDelay** (`int`_)
    Unknown value.

**OverheatCoolDownTime** (`float`_)
    Unknown value.

**OverheatPercentPerShot** (`float`_)
    Unknown value.

**DroppedAmmoScale** (`float`_)
    Unknown value.

**BulletHoleScale** (`float`_)
    Unknown value.

**HeadshotMultiplier** (`float`_)
    A number that damage is multiplied by when doing headshot damage.

**ZoomMagnification** (`float`_)
    How much the view should be magnified when using fine aim.

**AutoaimOverride** (`float`_)
    Unknown value.

**NpcAutoaim** (`float`_)
    Unknown value.

**AimAssist** (`float`_)
    Unknown value.

**PlayerMoveSpeedMultiplier** (`float`_)
    Unknown value.

**NpcMoveSpeedMultiplier** (`float`_)
    Unknown value.

**AlertMultiplier** (`float`_)
    Unknown value.

**ProjectileInfo** (`WeaponProjectileInfo`_)
    Information about the weapons projectiles if it uses projectile ammo.

**StandingPrimaryMeleeAttack** (`int`_)
    Unknown value.

**StandingSecondaryMeleeAttack** (`int`_)
    Unknown value.

**StandingTertiaryMeleeAttack** (`int`_)
    Unknown value.

**CrouchingPrimaryMeleeAttack** (`int`_)
    Unknown value.

**CrouchingSecondaryMeleeAttack** (`int`_)
    Unknown value.

**CrouchingTertiaryMeleeAttack** (`int`_)
    Unknown value.

.. _`String`: ./PrimitiveTypes.html
.. _`ChecksumStri`: ./ChecksumStri.html
.. _`int`: ./PrimitiveTypes.html
.. _`WeaponInfoFlags`: ./WeaponInfoFlags.html
.. _`WeaponClasses`: ./WeaponClasses.html
.. _`InvItemInfo`: ./InvItemInfo.html
.. _`HumanTeams`: ./HumanTeams.html
.. _`AnimationGroups`: ./AnimationGroups.html
.. _`unsigned int`: ./PrimitiveTypes.html
.. _`bool`: ./PrimitiveTypes.html
.. _`int8`: ./PrimitiveTypes.html
.. _`float`: ./PrimitiveTypes.html
.. _`TriggerTypes`: ./TriggerTypes.html
.. _`AmmoTypes`: ./AmmoTypes.html
.. _`unsigned int16`: ./PrimitiveTypes.html
.. _`DamageScalingInfo`: ./DamageScalingInfo.html
.. _`ExplosionInfo`: ./ExplosionInfo.html
.. _`WeaponProjectileInfo`: ./WeaponProjectileInfo.html
