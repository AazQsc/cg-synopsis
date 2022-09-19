---
Use **PostProcessVolume** for changing global world parameters.

---
Use **Material Instance** for parametrise you materials.

---
foliage.ForceLOD 0 --> enable  LOD (detalisation)
<br>foliage.ForceLOD -1 ->  disable LOD

---
r.Streaming.PoolSize -> resize streaming pool

---
For create light for landscape add:
1) Direction Light
2) Sky Atmosphere
3) Sky Light
4) Exponential HeightFog

---
For create Landscape:
1) Landscape mode -> Create New 
2) add cube
3) add character
4) add PostProcessVolume
5) PostProcessVolume -> Exposure Mode : Manual
6) PostProcessVolume -> Infinity Extent : true
7) PostProcessVolume -> Exposure Compensation : 10.5
8) add Volumetric Cloud

---
Cinematic:
1) add cine camera actor
2) add level sequence
3) add camera to sequence
4) add transform keyframe to sequence from camera
5) 

---
## Naming

<br>M_      materials
<br>MI_     material instance
<br>T_      textures
<br>BP_     Blueprint
