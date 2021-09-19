# vehicle-speed-detection
Vehicle speed detection is used to estimate the velocity of the moving vehicle using image and video processing techniques.
Without any camera calibrations video is captured and analyzed for speed in real time. By employing frame subtraction and masking techniques, moving vehicles are segmented out.
Speed is calculated using the time taken between frames and corner detected object traversed in that frames. 
Finally frame masking is used to differentiate between one or more vehicles.

Detection of vehicle speed on the highway is supporting the management of traffic engineering. 
The purpose of this study is to detect the speed of the moving vehicles using digital image processing. 
Vehicle tracking is required in order to build a robust ve-hicle speed estimation model. 
Many methods have been de-veloped that use classic computer vision and machine learn-ing approaches for object tracking.
Our vehicle tracking algorithm relies on localization re-sults from the vehicle detection methods.
