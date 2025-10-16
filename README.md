# BIO_350_F25

Starting our BIO350 assignments repo.

IC Assignment 1: Chapter 1 of Ecology Handbook
- Making a difference equation
- Technical difficulties, SHOULD be better from now on
- It works!

IC Assignment 2: Chapter 2 of Ecology Handbook
- Making an exponential equation to measure how quickly duckweed covers a pond
- Minimal technical difficulties but better
- Installed matplotlib and made our first plot!

IC_InClass1.ipynb
- Here we used the code from IC Assignment 2 to make a logarithmic graph and we used else if statements to change the rate of growth of duckweed based on the total area covered.

IC_Assignment3.ipynb
- Made a logistic growth model almost all by myself
- Originally I had a somewhat decent one that reached carrying capacity way too fast but it was still logistic
- Once I figured out how to properly add the birth and death rates the growth sloped out more and the model was more like what we expected

IC_InClassExample2.ipynb
- For this we installed pandas
- We then imported data and made a graph out of it showing population growth
- We then used copilot to add a line of the carrying capacity and change around our axises and line color

IC_Assignment4.ipynb
- For this assignment we were once again using a log equation but adding in competition between two species
- I started with my code from assignment 3
- I figured out that my code was a little repetitive so we were able to take out a good chunk of it
- Then I added in the section that shows the growth of the other species for their competition
- After plotting the results you are able to see how the competition drives one of the species to extinction

IC_Assignment5.ipynb
- Here we set up an SIR model in order to monitor the health states of a population of foxes under the threat of rabies
- The equations were relatively easy to set up, however I did miss a few of the variables in terms of naming things in order to build off of earlier numbers. Because of this I used copilot to try to get thigns organized better because it wouldn't show me my results. SO after getting help with renaming things to better organize my data I put the beggining values back in and was finaly able to see my results.
- I then used plotting code from a previous assignment and edited it to show all three lines and our time frame of 30 days.

IC_Example3.ipynb
- Today we downloaded some of Dr Carters R Code from his Bsal paper
- We brought it in to VS Code and had Copilot translate it into python script for us
- After trying to run the first section of it we had trouble because the scipy.integrate couldn't be found
- Because of this we had to open a terminal to download scipy with conda. I had trouble with this because I accidentally downloaded it to the wrong file initially but I figured out how to fix it on my own!
- After downloaded that I split my code up and ran the different sections. I had trouble with my plotting one but it was because I forgot to bring in the times we had outlined in the previous section so it left the times undefined in the plotting
- I can tell I'm getting much better at reading errors and understanding how to fix my code

IC_AssignmentMatrix.ipynb
- This was a cool assignment where we combined and simplified the growth and death rates of three separate populations
- I think where we hadn't had class in a few days I was a little rusty in my coding because I kept having trouble having variables being undefined so I had to make sure everything was lined up right and I had to use copilot a few times to get things to work right.
- The main area where I had to use copilot was when we switched from 50 to 150 years. Somehow I had set my Y axis to only have 50 values and I had to have copilot fix it to where x and y had the same values.