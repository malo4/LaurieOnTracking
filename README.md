# LaurieOnTracking
Laurie's code for reading and working with Metrica's tracking and event data.

The sample data can be found in Metrica's github repository here: https://github.com/metrica-sports/sample-data

We'll be updating this repo as the friends of tracking series develops, adding code for measuring player velocity and acceleration, measuring team formations, and evaluating pitch control using a model published by Will Spearman. 

To create movies from the tracking data you'll need to have ffmpeg installed. You can do this by following the instructions here: https://anaconda.org/conda-forge/ffmpeg (you may need to restart python afterwards).


# What's extra:
Forked LaurieOnTracking repository, implementing the code from Laurie's tutorials into Jupyter notebooks. Taking it one step further, my notebooks contain the following customizations (hope you find interesting):

(In tutorial_2) Calculating & Visualizing the top speed a player reached during the game. Worth noting that this process allows you to throw away most outlying values (due to player position incorrectly recorded in tracking data).

(In tutorial_3) Recreating a real-game situation aiming to explain better the usefulness of Pitch Control model and how analysts/coaches can actually use it to quantify the actions of players off the ball.



