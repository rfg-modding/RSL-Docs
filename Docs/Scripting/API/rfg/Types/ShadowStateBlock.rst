
.. attention:: This page is incomplete and needs better descriptions and research into the behavior of the variables.


ShadowStateBlock
********************************************************
Shadow state values. Access this through ``rfg.Shadows``. So, for example, if you wanted to set the value of ``ShadowPercent``, you'd do that like so:  ``rfg.Shadows.ShadowPercent = 0.5``.

Variables
========================================================

**ShadowsEnabled** (`bool`_)
    Needs description. Default value: ``true``

**CloudShadowEnabled** (`bool`_)
    Needs description. Default value: ``true``

**CloudShadowScale** (`float`_)
    Needs description. Default value: ``0.5``

**CloudShadowIntensityScale** (`float`_)
    Needs description. Default value: ``4.5``

**CloudShadowIntensityBias** (`float`_)
    Needs description. Default value: ``-0.5``

**ShadowMapMaxDist** (`float`_)
    Unknown purpose. Name is contradictory since increasing this value makes closeby shadows look worse. Default value: ``100.0``

**ShadowMapFadePercent** (`float`_)
    Needs description. Default value: ``0.8``

**ShadowPercent** (`float`_)
    Needs description. Default value: ``1.0``

**DropShadowPercent** (`float`_)
    Needs description. Default value: ``0.4``

**TerrainShadowMaxDist** (`float`_)
    Needs description. Default value: ``240.0``

.. _`bool`: ./PrimitiveTypes.html
.. _`float`: ./PrimitiveTypes.html