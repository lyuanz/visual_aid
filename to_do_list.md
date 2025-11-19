For Aim 2, the angle of the ghost swimmer is incorrect. Currently, it's set as 0, but it should be negative of the angle of the original swimmer.
For Aim 2, remove the fixed_time variable. ghost swimmers should be at the same phase as the original swimmer. Hence, ghost.time = p.time.
For Aim 2, alignment radius between swimmers and the images should be the same as between swimmers. 
For Aim 2, the strength of weathervane torque should be dependent on the gradient of flow velocity, rather than just flow velocity. 