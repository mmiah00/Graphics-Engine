# Final Project
## Maisha Miah Period 5
### Features Added:
* Light
  * creates a "light" datastructure with rgb values
  * syntax: light r g b x y z 
    * color rgb at location xyz
  * Add ight to the symbol table

* Mesh
  * load a mesh from a file
  * syntax: mesh [constants] :filename [coord_system]
    * filename does not include .obj
    
* Set
  * sets a knobs value (in the symbol table).
  * syntax: set knobname value
  
* Save_coordinate_system
  * Makes a copy of the top of the stack and saves it in the symbol table under "name."
  * syntax: save_coord_system name
        
* Setknobs
  * set all the knobs to value
  * syntax: setknobs value

* Save_knobs
  * saves the current values of all knobs under the name "knoblist."
  * syntax: save_knobs knoblist	
