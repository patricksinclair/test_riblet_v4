This is based on the gradient slippy riblet case.  We'll change it by changing the geometry to 4 riblets, all on the micron scale

UPDATE: It appears that there's some issue using the custom boundary conditions for U when I try and run the code remotely on the uni computer and then try to process it locally.
There's some sort of make error when the custom boundary gets compiled on the uni system, and then gets recompiled for some reason when I run paraFoam locally.

Not sure why this is an issue but oh well. Hopefully when the uni system is used as the local system for processing, this won't be an issue.  However for now I think possible
solutions could be either to stick a long tube into the system before the riblets appear and try and develop a poisseiulle flow profile, pr just use a constant inlet x_velocity.

I'll do the latter for now
