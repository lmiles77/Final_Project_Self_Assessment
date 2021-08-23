# Final_Project_Self_Assessment

This final project for our group came out of our love for football (Okay, mainly my love for the football, but who's counting?). An offensive team's ability to maintain possession of the ball is a key aspect of the game. An offensive team's to successfullly convert third downs greately impacts their ability to move down the field to score if trailing the other team, or to maintain possession, and run the clock down to end game. This project focused on 3rd down plays called in the 4th quarter of the 2020 NFL season.

The final project for this course required classmates and I to form a team that would utilize skills acquired during the bootcamp to create a machine learning model, a fully integrated database, and an interactive dashboard. For this project I was the square. The squares responsibility it to create the repository and the branches for each team member. I found creating branches and merging them to the main branch to be fairly straight forward, although there were times when I was unsure if I had created the correct branch or successfully merged each branch to the main branch. I was the only one in my group who was willing to give this task a try, so that game me some confidence. In addition to setting up the repository, I was responsible for writing the code for the machine learning model. The raw data used for this machine learning project was 2020 NFL play data. This was a fairly large csv file comprised of 46,189 rows and 43 columns. The file didn't require an extra ordinary amount of clean up. Analysis of the file did reveal that there were thousands of cells in the 'Formation', and 'PlayType' columns without values. Using .fillna, empty cells were filled with 'unk'. Additionally, analysis of 'PlayType' data reveled plays that did not result in positive outcomes. The loc method was use to create dataframe of positive play types.We decided to build our machine learning project around the analysis of 3rd down plays in the 4th quarter. This machine learning model project utilizes logistic regressoin to predict the probability of the offensive team's ability to successfully convert a third down play in the 4th quarter of a game. The accuracy score for this model is 68%. I feel the overall accuracy of the model suffered becasue no feature besides distance had any importance greater that 18%.

The greatest challenge I had during this project was trying to not become too overwhelmed by the demands of the project. As a group we would plan to have a given section completed at a certain time, but would inevitably run into set backs. Each setback made me feel like we weren't going to be able to complete the project. I eventually settled into a space where I allowed myself to be overly consumed with each aspect of what needed to be completed and allowed myself to focus on what I was learning about group projects. The journey of figuring out how to work together as a team was what was most important. Although not having a model that was able to make a prediction during group presentations wasn't the greatest of feelings, I was still proud of the fact that we completed as much as we had. One tip I have for future group would be to communicate as much as possible. Although we identified resources we would utilize to communicate with one another such as Slack, txt messaging, and Zoom, we did schedule dates and times we would meet.  Simply have the means by which we would communicate was not enough to ensure everyone knew when and how we would meet. I would suggest creating a shared calendar with scheduled meet up times to keep the group on track.

Overall, this was a great experience! I believe we could have done an even better job had we met more often. This I believe would have led to us being able to  and were able to complete tasks on the schedule we set. 

















