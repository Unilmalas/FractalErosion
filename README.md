# FractalErosion
Fractal terrain generation and and droplet erosion

- fractal terrain generation (used Hunter Loftis code: http://www.playfuljs.com/realistic-terrain-in-130-lines/)
- use a hydraulic erosion model to make terrain look more realistic (based on the model by Mei/Decaudin/Hu and Jako/Proceedings of CESCG 2011) -> changed this to simpler and much faster droplet erosion model, seems to work
- added two other versions of a droplet erosion model: the iterative version is much faster with good results
- terrain visualization via direction of slope and lightning (Buchin et al.)

next steps:
- clean up this mess (still have not gotten to it)
- stroke rendering pencil-like (Salsbury et al.)
