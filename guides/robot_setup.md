# How to set up the robot

1. install ev3dev on the robot
    
    Follow this tutorial: https://www.ev3dev.org/docs/getting-started/
    
    During the tutorial, set up an internet connection on the ev3. This allows to later access the python package index.

2. Setup rpyc to remotely run python code on the ev3. This allows us to execute most code on the PC instead of on the robot.

    Tutorial: 
    https://github.com/ev3dev/ev3dev-lang-python/blob/ev3dev-stretch/docs/rpyc.rst

    Make sure you install the same version of rpyc on both your robot and your computer

    To test your connection, try the jupyter notebook in `src/rpc_test`
