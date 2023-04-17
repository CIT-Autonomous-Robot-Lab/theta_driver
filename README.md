# theta_driver

## Getting started
```
mkdir -p catkin_ws/src
cd catkin_ws
git clone --recursive https://github.com/CIT-Autonomous-Robot-Lab/theta_driver.git ./src
catkin build
roslaunch theta_driver theta_driver.launch
```


Dockerを使う場合
```bash
docker build -t theta_driver .
docker run --rm -it --net=host --privileged theta_driver
roslaunch theta_driver theta_driver.launch
```
  


## Output

| **Name（Topic）**        | **Type**                                 | **Description**                                      | 
| -------------------- | ------------------------------------ | ------------------------------------------------ | 
| `/theta_driver_node/image_raw`      | `sensor_msgs::Image`         | カメラ画像| 
