## mono_lidar_plot.vi
<p align="center">
<img src="https://github.com/monoDriveIO/client/raw/master/WikiPhotos/LV_client/utilities/monoDrive_lvlib_mono__lidar__plotc.png" 
width="400"  />
</p>

### Description 

### Inputs

- **Lidar Data Out(Cluster):**.

| Type  | Name   |
| ------------ | ------------ |
|DBL  | Rotational Angle (degrees) |
|DBL | Vertical Angle (degrees)  |
|DBL | Distance (cm)  |
|U8 | Intensity (0-255)  |
|DBL | Vertical Offset (cm) |

- **error in (Error Cluster):** Can accept error information wired from VIs previously called. Use this information to decide if any functionality should be bypassed in the event of errors from other VIs.


### Outputs

- **Plot_data:** Proccessed data ready to plot in a 3D Plot Datatype.lvclass
- **error out (Error Cluster):** Can accept error information wired from VIs previously called. Use this information to decide if any functionality should be bypassed in the event of errors from other VIs.