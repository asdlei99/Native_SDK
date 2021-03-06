==============
PostProcessing
==============

.. figure:: ./PostProcessing.png

This training course demonstrates a simple implementation of a 'bloom' post processing effect.

Description
-----------
This training course demonstrates a simple implementation of a 'bloom' post processing effect, using Render Passes (Vulkan)/ Render To Texture (OpenGL ES)
to render an intermediate scene and use it for postprocessing. The bright parts of the picture are extracted in lower resolution in a post processing step,
blurred and then added over the final image to create a glow around the object's borders.

APIS
----
* Vulkan
* OpenGL ES 2.0+

Controls
--------
- Left/Right- Change the rendering mode (Object with bloom, object w/o bloom, bloom textures)
- Up/Down- Increase/Decrease bloom intensity
- Any Action- Pause
- Quit- Close the application