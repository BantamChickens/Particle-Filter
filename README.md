# Particle-Filter
### Running Test Nodes Package

Build the package (Rebuild needed if setup.py is modified)

```
cd ~/ros2_ws
colcon build --packages-select test_nodes --symlink-install
```
Then naviagte to where the 'Particle-Filter' repo is stored. For example, if stored in ros2_ws:
```
cd ~/ros2_ws/Particle-Filter
```
Then run the node using ros2 run <package name> <node name>. For example, if running send_message:
```
ros2 run test_nodes send_message
```
### Running Particle Filter Package
``` 
cd ~/ros2_ws
colcon build --packages-select test_nodes --symlink-install
```