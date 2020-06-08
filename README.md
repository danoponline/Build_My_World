# Build My World

Message for mentors: <br>

To build this repo, run
```
cd /home/workspace/Build_My_World/build
cmake ../
make
```
Before running Gazebe, run the following,
```
export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/home/workspace/Build_My_World/build/
```
Then,
```
gazebo /home/workspace/Build_My_World/world/myHouse
```