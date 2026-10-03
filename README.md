# Particle-Filter
### Overview
There are two packages:
- **test_nodes**: Contains a skeleton publisher and subscriber for quickly checking if ros2 is working properly
- **particle_filter**: Contains the main simulation code

### Running the Packages
Build the package (Rebuild needed if setup.py is modified)
```
cd ~/ros2_ws
colcon build --packages-select test_nodes particle_filter --symlink-install
```
Then navigate to where the 'Particle-Filter' repo is stored. For example, if stored in ros2_ws:
```
cd ~/ros2_ws/Particle-Filter
```
Then run the node using ros2 run [insert package name here] [insert node name here].