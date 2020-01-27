## How to run:
* `mkdir build && cd build`
* `cmake ..`
* `make`
* `./Image publisher`

    This will publish Video Cam Image on `/ImagePubSubTopic`. You can subscribe using ROS2 Node on the same topic.
    or try ros2 built in node `ros2 run image_tools showimage -t /ImagePubSubTopic`
 