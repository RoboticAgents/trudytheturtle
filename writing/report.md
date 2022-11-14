# Report by Rian Watson, Rebekah Rudd, Danny Ullrich, Pallas Cain

## Step 1: Getting Started and `teleop`

Describe the steps you took to turn on and get your robot set up, and the steps you took to successfully use `teleop` on the robot.

We first turned our robot on a plugged it into the power and then we heard the two chimes and waited for it to show up on the wifi. When it wasn't showing up we held the two buttons on either side of the power button and then it showed up on the wifi. Then we waited for it to connect and went to the webpage. We then watched the videos about navigation and map building and started to take the steps to complete that with our robot.

## Step 2: Implementation Details

TODO: Describe the application/task that you decided to pursue. Include **all** steps you took to implement the task, including all non-technical and technical details. Please include references (links are okay) to all resources you have used.

For this lab we had our Turtlebot4 do a navigation task. We started by creating a map of the campus center with its obstacles such as the pillars, tables, and chairs.

## Outcomes

Demonstrate your completed application/task with visual representations of your working solution (pictures or videos of each experiment's scenario or a simulated map). Describe your observations of your working robot in a specific application.

In this activity when we opened the rviz applications with our saved map we we able to click on the 2D Pose Estimate and then we clicked on the Nav2 Goal. When we took these actions the map generated a fuzzy blue outline around anywhere on the map where there was an obstacle. After having clicked on the 2D Pose Estimate you could then click somewhere on the map to indicate the location you wanted your robot to reach. After doing this your robot would find a route around obstacles to the final destination. The red line indicates the route the robot intends to take and the black dot with dispersing green color around it indicates the robot itself.

[alt text]'https://drive.google.com/drive/u/0/my-drive'

## Challenges and Learning Experiences

Discuss any challenges you have encountered during the work on this assignment and describe the biggest learning takeaways.
A: At first we had trouble connecting to the robot and getting it to move. Kept getting an error when trying to do the generate the map portion.

One of the first challenges we experienced was while making the map. The robot would not move and we were not exactly sure why the commands were not working. However, we closed all of the terminals and restarted and the second time it worked fine.

## Team Work

Describe the details of your team working strategy, specifically explain how did you complete this work as a team and describe the specific contributions of each team member.
A: We had all observed what the team before us had accomplished then started working. We read together how to set up the robot set by set. Once we set the robot us we started to discuss where we wanted the robot to start and end for its path within the campus center. Once we decided this, we moved on to developing the map. Last then we did was take a video of it and uploaded it to our repo. We divided up the report so that everyone could commit to it. We also helped each other by suggesting other small commits for participation points such as adding a word to cspell or adding our names to the report.
