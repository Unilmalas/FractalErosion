# FractalErosion
Fractal terrain generation and and droplet erosion

a horrible spaghetti-code to test
- fractal terrain generation (used Hunter Loftis code: http://www.playfuljs.com/realistic-terrain-in-130-lines/)
- use a hydraulic erosion model to make terrain look more realistic (based on the model by Mei/Decaudin/Hu and Jako/Proceedings of CESCG 2011) -> changed this to simpler and much faster droplet erosion model, seems to work

next steps:
- clean up this mess
- terrain visualization via direction of slope and lightning (Buchin et al.): working; some details to clean up: linear strokes in one direction, curvier the other (possibly due to gradient not following entire stroke); stroke rendering pencil-like (Salsbury et al.)
