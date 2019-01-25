# LEGO-machine-learning
Project in cooperation with The LEGO Company to bring advanced machine learning and reinforcement learning functionality to the LEGO Mindstorms platform.

# Swing Robot
This robot uses an evolutionary algorithm to learn how to swing. The motion was learned in 8 hours, over 75 generations with a total of 600 children evaluated. Demonstration of the results:

<iframe width="560" height="315" src="https://www.youtube.com/embed/6yY9P5vG-nA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Code used in training is in the jupyter notebook `src/swing_robot/CMA_Swing_Robot.ipynb` . Documentation in the report `Reinforcement_Learning_with_LEGO_Mindstorms.pdf` .

# Crawl Robot
This robot uses tabular Q-learning to learn a forward crawling motion. The motion is learned in 20 minutes. Timelapse of the training:

<iframe width="560" height="315" src="https://www.youtube.com/embed/NUTv-oNWEYo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Code used in training is in the jupyter notebook `Crawl_robot_tabular_q_learning.ipynb` . Documentation in the report `Reinforcement_Learning_with_LEGO_Mindstorms.pdf` .

