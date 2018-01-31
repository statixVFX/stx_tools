# stx_tools

VFX Tools, mostly Fusion related. Some Houdini, Blender and Shell related.

## Fusion Macros 
stx_metaballs    - 4 2d Metaballs with curve to change shading profile. <br>
<p align="left">
  <img src="images/blob.gif"/>
</p>

stx_patchPal     - Warps patches or stabilizes based on motion vectors. SLOW and requires the FrameAverage.Fuse . <br>
<p align="left">

  <img src="images/stx_patchPal_original.gif"/>
  <img src="images/stx_patchPal_warped.gif"/>
  <img src="images/stx_patchPal_stabilized.gif"/> <br>
    Original, Warped patch and stabilized <br>
</p>
stx_deflicker     - Simple deflicker for global flicker removal. <br>
<p align="left">
  <img src="images/deflicker.gif"/>
</p>
stx_highpass      - Highpass filter, for easy tracking and finding edges. <br>
<p align="left">
  <img src="images/highpass1001.png"/>
</p>
stx_pMatte        - Create mattes from World space position, sphere, cube or noise. Can be daisy-chained for complex shapes. <br>
<p align="left">
  <img src="images/pmatte2.png"/>
</p>
stx_slopeAndDot   - Slope/derivative of image, spits out vectors in RG and dot product in B. Great for displacements. <br>
<p align="left">
  <img src="images/slop4.png"/>
</p>
stx_strangeLoop   - Can create infinite looping / displacing effect. <br>
<p align="left">
  <img src="images/strange.gif"/>
</p>
stx_tileTexture   - Simple texture tiler with soft blend and optional removal of shadows / low freq detail. <br>
<p align="left">
  <img src="images/texturetiler.png"/>
</p>
stx_vectorDenoise - Simple temporal median or average of 3 frames to produce a clean image based on motion vectors <br>
<p align="left">
  <img src="images/vectorDenoise.gif"/>
</p>
stx_loopzilla     - Soft looper for clips. Makes looping elements much easier. <br>
