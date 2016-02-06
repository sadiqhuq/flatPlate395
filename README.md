### OpenFOAM: LES of flow over a flat plate

The starting point of this case is 
> $FOAM_TUTORIALS/incompressible/pimpleFoam/channel359

The topWall is switched to be a symmetryPlane. The velocity at time _0_ is initialized with the perturbUGeneric utility.
[PerturbUChannel / Cylinder / Generic](https://github.com/wyldckat/perturbU)

##### TODO
* Add post processing scripts
* Validate the case
* try rough wall functions

------
[License: GNU General Public License, version 3 (GPL-3.0)](http://opensource.org/licenses/GPL-3.0)
