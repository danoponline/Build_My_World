# Build My World

Message for mentors: <br>

To build this repo, clone and cd into this repo, and then
```
mkdir build
cd build
cmake ../
make
```
Before running Gazebe, run the following,
```
export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:<your path to Build_My_World>/build
```
Then,
```
gazebo <your path to Build_My_World>/world/myHouse
```