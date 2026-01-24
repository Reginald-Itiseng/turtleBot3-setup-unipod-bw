This section references the **official TurtleBot3 camera setup documentation**:


👉 https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/


## What the Official Docs Cover Well


- Basic camera support overview
- ROS 2 camera launch files
- Expected topics


## What the Official Docs Do *Not* Cover


!!! warning
The following issues were encountered on the Unipod TurtleBot3 Waffle Pi but are **not mentioned** in the official documentation.


- libcamera not in PATH
- LD_LIBRARY_PATH not persistent
- v4l2 device mismatch
- Conflicts between `libcamera` and `v4l2_camera`


Each of these is documented in detail in the next sections.