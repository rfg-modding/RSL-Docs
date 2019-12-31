
.. attention:: This page is incomplete and needs better descriptions and research into the behavior of the variables.


TerrainStateBlock
********************************************************
Terrain state values. Access this through ``rfg.Terrain``. So, for example, if you wanted to set the value of ``FadeEnd``, you'd do that like so:  ``rfg.Terrain.FadeEnd = 5000``.

Variables
========================================================

**DetailMapTiling** (`float`_)
    Needs description. Default value: ``1.3``

**DetailMapScale** (`float`_)
    Needs description. Default value: ``4.8``

**DetailMapBias** (`float`_)
    Needs description. Default value: ``-0.035``

**DetailMapBlend** (`float`_)
    Needs description. Default value: ``0.72``

**DetailMapEnable** (`bool`_)
    Needs description. Default value: ``true``

**SpecularEnable** (`bool`_)
    Needs description. Default value: ``true``

**RenderAlphaSkirts** (`bool`_)
    Needs description. Default value: ``true``

**AnisotropyLevel** (`int`_)
    Needs description. Default value: ``4``

**FadeStart** (`float`_)
    Needs description. Default value: ``140.0``

**FadeEnd** (`float`_)
    Increase this value to make terrain stay in high lod form at further distances. Default value: ``250.0``

**MedLod** (`bool`_)
    Needs description. Default value: ``true``

**UseNewRenderer** (`bool`_)
    Needs description. Default value: ``true``

.. _`float`: ./PrimitiveTypes.html
.. _`bool`: ./PrimitiveTypes.html
.. _`int`: ./PrimitiveTypes.html
