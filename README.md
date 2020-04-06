# Self Driving RC car description files

## Description and launch files for self driving RC car project

tf_static.launch file should be added to the launch file of the self driving RC car projects launch file where TF publishing is necessary (i.e. SLAM) and/or visualization is desired.

```xml
	<include file="$(find rc_car_description)/launch/tf_static.launch"/> 
```