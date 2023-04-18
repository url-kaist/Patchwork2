# patchwork2

Are you ready to exploit fast and robust ground-segmentation for all terrestrial robots?

***Patchwork2*** is under revision and soon will be available! :sunglasses::sunglasses::sunglasses: 

## Features

* Two times faster than [Patchwork](https://github.com/LimHyungTae/patchwork) while showing better precision and recall!
* Contains an outlier-robust approach to prevent bin-wise ground segmentation failure
* Supports all terrain.
* Super-easy usability (because all the parameters are automatically changed)

```bash
% When running Patchwork2 using VLP-16 with a wheel-based robot or quadruped robot
$ roslaunch patchwork2 run_patchwork2.launch sensor_type:=VLP16

% When running Patchwork2 using Ouster OS1-64
$ roslaunch patchwork2 run_patchwork2.launch sensor_type:=OS1-64

% When running Patchwork2 using Velodyne HDL-64E (i.e., on SemanticKITTI dataset)
$ roslaunch patchwork2 run_patchwork2.launch sensor_type:=HDL-64E
```

**Stay tuned!** :stuck_out_tongue_closed_eyes:	

![tmp](materials/Patchwork2_demo_original.gif)
