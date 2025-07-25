This is a custom Hammer++ map compilation sequences (aka Run Map) config, which contains custom VRAD parameters (for Slammin Tools).


Alternatively, you can use these VRAD parameters:
Without ambient occlusion:
$path\$file -threads 11 -both -final -disppatchradius 16384 -extrasky 24 -bounce 200 -softencosine -TextureShadows -StaticPropPolys -StaticPropLighting -worldtextureshadows -translucentshadows -LargeDispSampleRadius -game $gamedir

With ambient occlusion (Slammin Tools required):
$path\$file -both -final -disppatchradius 8192 -extrasky 24 -bounce 200 -ambientocclusion -aoscale 0.3 -softencosine -TextureShadows -StaticPropPolys -StaticPropLighting -worldtextureshadows -translucentshadows -game $gamedir -LargeDispSampleRadius