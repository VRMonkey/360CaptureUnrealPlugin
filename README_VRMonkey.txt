Two commands were added to the pluguin stereoPanorama:

SP.Stereo [1,0]

if it´s 1, it means that the output will be the both images (stereoscopic) left and right.

SP.CombineAtlasesOnOutput [1,0]

if it´s 1, it means that the output will create only one image file (per frame) for the right and left images, one on top of the other.
Obs.: if "SP.CombineAtlasesOnOutput 1", "SP.Stereo" must receive 1 as well (like "SP.Stereo 1").