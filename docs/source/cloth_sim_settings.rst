Cloth Sim Settings
------------------

These settings can be set prior to activating the **Geometry** menu commands or after a setup that uses cloth simulations has been generated.

Stiffness
^^^^^^^^^

This setting applies a proportional pin weight to the vertices in the mesh with the cloth sim where the base is always with a weight of 1.0 and
decreases at each vertex point until you get to the last vertex.  Stiffness is just a multiplier where you can increase/decrease all of the weights beyond
the base vertex.  The lower the value the more sensitive the setting becomes, but is also a good place to find the best simulation to emulate things such as hair, rope, and other strand-like objects.  

Tip Hold
^^^^^^^^

This setting is useful in making sure that the stiffness setting doesn't create too much of a limp end of the strand and will inherit the weight of
vertices with lower index values keeping the tip from being limp in the cloth simulation.  It's operates like the blue pill to avoid flacid sims.

As of right now the Schwurve add-on does not create collisions with these simulations, but is something that will
be implemented in future versions if there is substantial interest in updating and if Blender development doesn't make such an add-on unnecessary.
