# Procedural-mesh-generation-in-UE4
Script made in ue4 blueprints/ nativized C++ to automatically generate houses and random maps based on inputs and mesh added. consist of two tries: house/flat and randomized maps which uses perlin noise 1D for height

Just copy the content file to "unreal project/"Project name"/content " and open untitled_map map in ue4

__HOUSE SCRIPT__

-The house script can be used to make houses and buildings as well having "n X m X o" (lenght,breadth and no.of floors respectively).
 It requires few inputs like Static mesh for edges and sides for floors and terrace.
 Interior can be togglable using a tickbox and is fully customizable.
 The randomiser uses stream so that thousands of house combination can be made in an instant with change in seed.
 The files consist of medieval houses example since i'm fond of fantasy art.
 
__MAP GENERATOR__ 
 
-The map generation is still at work, need optimisation and need a replacement for perlin noise 1D.
 Works for couple of size i tried, would need scale adjustment and range value of perlin noise for height,if size is big.
 to build, click the update bool (you need to do it every time you update or add new values to avoid wate of time due to script compiling for large region).
 I'd recommend not to use it as a substitude for landscape (It is more heavy and takes time when compared to 4 X 4 Km map size).
