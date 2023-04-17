# theta_driver

## Getting started

```bash
docker build -t theta_driver .
docker run --rm -it --net=host --privileged theta_driver
roscore&
rosrun theta_driver theta_driver_node
```

## Output

| **Name（Topic）**        | **Type**                                 | **Description**                                      | 
| -------------------- | ------------------------------------ | ------------------------------------------------ | 
| `/theta_driver_node/image_raw`      | `sensor_msgs::Image`         | カメラ画像| 
