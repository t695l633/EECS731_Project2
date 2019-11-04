# EECS731_Project2
Classifying Shakespeare Actors based on line info

# To Be, or not to be.

  Classifying Shakespeare plays and players
1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the Shakespeare plays dataset from https://www.kaggle.com/kingburrito666/shakespeare-plays
3. Load the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more classification models to determine the player using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

In this project I used a decision tree to classify what character was speaking a specific line of a Shakespeare play. The first thing I did was modify my data set to include only the most worthwhile data. I also split up ActSceneLine into 3 separate columns so their numerical values could be used in my decision tree.

I used a decision tree to solve this classification problem because all of the attributes I worked with were numerical, so a decision tree could easily separate characters by play, act, and scene. 

After training my decision tree on 70% of my data, it was ~77% accurate in classifying characters from the remaining 30% of lines.

While this accuracy is good for a first attempt, I believe if I had used natural language processing on the spoken lines by each character I may have achieved even greater accuracy. For simplicity in this project my model only predicts character based on when and in what play they speak, rather than their actual spoken lines.

Source code, mark down comments, and explanation of my procedure can be found in the notebook contained within this repository.
