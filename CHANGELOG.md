Change Log
==========

Version 1.1.1 *(2014-01-03)*
----------------------------

 * Fix: Invalidate view when changing whether the scale ratio is enabled.


Version 1.1.0 *(2014-01-03)*
----------------------------

 * New: Option to draw the scale ratio as text on top of the pixel grid. Control with
   `setOverlayRatioEnabled`.


Version 1.0.1 *(2013-12-05)*
----------------------------

 * Properly expose whether the overlay is enabled or not via `isOverlayEnabled()`.
 * Toggling the overlay will automatically trigger a drawing pass.
 * Free bitmap resources when disabling the overlay.
 * Fix: Changing the color now actually changes the color.


Version 1.0.0 *(2013-12-05)*
----------------------------

Initial release.
