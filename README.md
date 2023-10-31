# AB-Testing with Cookie Cats Game
<p align="center">
  <img width="900" alt="187047952-d71eda19-b4d4-43ba-acd2-c71bc43035cb" src="https://github.com/Shashank-Reddy-M/AB_Testing/assets/114110108/0a945830-2b68-4003-b302-2dde7edf32ba">
</p>

Cookie Cats is a fun and addictive mobile puzzle game by Tactile Entertainment that has gained immense popularity. In this classic "connect three" style game, the player must connect tiles of the same color to clear the board and win the level. One of the unique features of the game is the presence of singing cats. 

As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged.

# AB Test Analysis
The placement of the gates is a critical decision for any mobile game developer. In this notebook, we analyze an A/B test where we moved the first gate in Cookie Cats from level 30 to level 40. We focus on player retention, a critical metric for the success of any mobile game. Before we dive into the analysis, it is important to understand the data.

Our analysis is presented in the form of a Jupyter notebook, where we use Python and various data visualization libraries to explore and visualize the data. We also perform statistical analysis to determine the significance of the observed differences in player retention.

# Conclusion
The analysis shows that there is strong evidence that 7-day retention is higher when the gate is at level 30 than when it is at level 40. 

The conclusion is: Our A/B test results show that moving the gate from level 30 to level 40 would negatively impact both 1-day and 7-day retention. Retention is one of the most important metrics for our game, as it directly impacts our revenue. Therefore, we should not move the gate from level 30 to level 40.
