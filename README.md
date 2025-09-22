Merge Arrays ROS2 Node
======================

contains a ROS2 node that merges two sorted integer arrays into a single sorted array

Node
----

- Name: `merge_arrays_node`
- Package: `merge_arrays`
- Subscribes to:
  - `/input/array1` (std_msgs/Int32MultiArray)
  - `/input/array2` (std_msgs/Int32MultiArray)
- Publishes to:
  - `/output/array` (std_msgs/Int32MultiArray)