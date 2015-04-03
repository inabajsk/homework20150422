# homework20150423

1. execute `talker/listener` sample

  - Open new terminal and execute command below:
  ```bash
# Terminal 1
roscore
```
  - Open new terminal and execute command below
  ```bash
# Terminal 2
rosrun roseus talker.l
```
  - Open new terminal and execute command below:
  ```bash
  # Terminal 3
rosrun roseus listener.l
```
2. Try `turtlesim` sample
  - Open Terminal and launch roscore
  ```bash
  roscore # do not exit till finishing other programs
  ```
  - Open Terminal and execute command below:
  ```bash
  sudo apt-get install ros-hydro-turtlesim
  exec -l $SHELL
  rosrun turtlesim turtlesim_node
```
  - Open new Terminal and execute command below:
  ```bash
  rosrun turtlesim turtle_teleop_key
  # focus mouse pointer to this window, and press arrow keys
  ```
  
