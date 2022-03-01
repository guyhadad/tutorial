# bash

## debugging:
1. when you need to debug your script you should open terminals for each process and see which fail.
2. keep it simple! if some process fail, try to run the same process alone and copy the system enivroment value that run this process successfully for example  PYTHONPATH


## parameters:
1. `$0` will contain a path, absolute or relative to the script.
2. `$` represent the value of a parameter.
3. `2>&1` will represnt both stdout and stderr.
4. `$#` represent the number of arguments the the scrip get.
5. `$1` the first argument of the script
6. `$!` is the PID of the last program your shell ran in the background 


## commands:
1. `rostopic list` will tell you all the topics that open.
2. `grep` is basicly for searching .
3. `wc -l` is flag for grep to count.
4. if statement - if(statement); then
                  --------------------
                  fi
5. `echo` is to print.
6. `exit 0` is exit successfully. 
7. `sleep 3` sleep for 3 seconds.
8. `-f` in if statement is use to ask if something exists.
9. `&` in bash meant to run something in the background.
10. `rosparam` is connect to ros parameters that with `set` you can set a value in parameters. for example,  `/use_sim_time` `true`.
11. `rviz -d rviz.config` is for set a cofiguration to rviz.
12.  `cd` is for open a directory.
13.  `python "program.py"` is for run program in python on script.
14.  `rosbag` is for bags of data `play` is for playing the bag `-s 30` is for play 30 seconds after the start `-r 5` is run x5 speed
15.  `rostopic pub` if for publishing data `<topic-name> <topic-type> [data...]` 
16.  

9

