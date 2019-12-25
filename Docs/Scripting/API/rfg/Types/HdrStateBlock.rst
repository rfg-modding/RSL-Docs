
HdrStateBlock
********************************************************
Hdr state values. Access this through ``rfg.Hdr``. So, for example, if you wanted to set the value of ``BloomSoft``, you'd that like so: ``rfg.Hdr.BloomSoft = false``. Another example, if you wanted to set the value of ``IrisRate``, you'd do ``rfg.Hdr.IrisRate = 0.33``.

Variables
========================================================

**Override** (`bool`_)
    Needs description.

**Enable** (`bool`_)
    Needs description.

**BloomSoft** (`bool`_)
    Needs description.

**BloomAlternate** (`bool`_)
    Needs description.

**ToneMappedBloom** (`bool`_)
    Needs description.

**LuminanceRange** (`float`_)
    Needs description.

**LuminanceOffset** (`float`_)
    Needs description.

**HdrLevel** (`float`_)
    Needs description.

**IrisRate** (`float`_)
    Needs description.

**LuminanceMin** (`float`_)
    Needs description.

**LuminanceMax** (`float`_)
    Needs description.

**LuminanceMaskMax** (`float`_)
    Needs description.

**BrightpassThreshold** (`float`_)
    Needs description.

**BrightpassOffset** (`float`_)
    Needs description.

**UseHdrLevel** (`bool`_)
    Needs description.

**BloomNew** (`bool`_)
    Needs description.

**EyeAdaptionBase** (`float`_)
    Needs description.

**EyeAdaptionAmount** (`float`_)
    Needs description.

**EyeFadeMin** (`float`_)
    Needs description.

**EyeFadeMax** (`float`_)
    Needs description.

**BloomAmount** (`float`_)
    Needs description.

**BloomTheta** (`float`_)
    Needs description.

**BloomSlopeA** (`float`_)
    Needs description.

**BloomSlopeB** (`float`_)
    Needs description.

**LuminanceConversion** (`Vector`_)
    Needs description. Note that being a vector, it has ``x``, ``y``, and ``z`` values. So for example, you'd set it's y value like this: ``rfg.Hdr.LuminanceConversion.y = 0.23``.

**BloomSuperSoft** (`bool`_)
    Needs description.

**EyeOverride** (`bool`_)
    Needs description.

.. _`bool`: ./PrimitiveTypes.html
.. _`float`: ./PrimitiveTypes.html
.. _`Vector`: ./Vector.html
.. _`unit vector`: https://en.wikipedia.org/wiki/Unit_vector
.. _`string`: ./PrimitiveTypes.html