
HdrStateBlock
********************************************************
Hdr state values. Access this through ``rfg.Hdr``. So, for example, if you wanted to set the value of ``BloomSoft``, you'd that like so: ``rfg.Hdr.BloomSoft = false``. Another example, if you wanted to set the value of ``IrisRate``, you'd do ``rfg.Hdr.IrisRate = 0.33``.

Variables
========================================================

**Override** (`bool`_)
    Needs description. Default value: ``true``

**Enable** (`bool`_)
    Needs description. Default value: ``true``

**BloomSoft** (`bool`_)
    Needs description. Default value: ``true``

**BloomAlternate** (`bool`_)
    Needs description. Default value: ``true``

**ToneMappedBloom** (`bool`_)
    Needs description. Default value: ``true``

**LuminanceRange** (`float`_)
    Needs description. Default value: ``3.0``

**LuminanceOffset** (`float`_)
    Needs description. Default value: ``10.0``

**HdrLevel** (`float`_)
    Needs description. Default value: ``0.6``

**IrisRate** (`float`_)
    Needs description. Default value: ``3.0``

**LuminanceMin** (`float`_)
    Needs description. Default value: ``0.001``

**LuminanceMax** (`float`_)
    Needs description. Default value: ``4.0``

**LuminanceMaskMax** (`float`_)
    Needs description. Default value: ``4.0``

**BrightpassThreshold** (`float`_)
    Needs description. Default value: ``3.0``

**BrightpassOffset** (`float`_)
    Needs description. Default value: ``6.0``

**UseHdrLevel** (`bool`_)
    Needs description. Default value: ``true``

**BloomNew** (`bool`_)
    Needs description. Default value: ``true``

**EyeAdaptionBase** (`float`_)
    Needs description. Default value: ``0.2``

**EyeAdaptionAmount** (`float`_)
    Needs description. Default value: ``0.5``

**EyeFadeMin** (`float`_)
    Needs description. Default value: ``1.0``

**EyeFadeMax** (`float`_)
    Needs description. Default value: ``1.0``

**BloomAmount** (`float`_)
    Needs description. Default value: ``2.5``

**BloomTheta** (`float`_)
    Needs description. Default value: ``1.2``

**BloomSlopeA** (`float`_)
    Needs description. Default value: ``0.0``

**BloomSlopeB** (`float`_)
    Needs description. Default value: ``0.08``

**LuminanceConversion** (`Vector`_)
    Needs description. Note that being a vector, it has ``x``, ``y``, and ``z`` values. So for example, you'd set it's y value like this: ``rfg.Hdr.LuminanceConversion.y = 0.23``. Default value: ``x: 0.213, y: 0.715, z: 0.072``.

**BloomSuperSoft** (`bool`_)
    Needs description.  Default value: ``false``

**EyeOverride** (`bool`_)
    Needs description. Default value: ``false``

.. _`bool`: ./PrimitiveTypes.html
.. _`float`: ./PrimitiveTypes.html
.. _`Vector`: ./Vector.html
.. _`unit vector`: https://en.wikipedia.org/wiki/Unit_vector
.. _`string`: ./PrimitiveTypes.html