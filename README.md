# ICC-2023-Worldcup-prediction
## Predicting the winner of 2023 cricket world cup using random forest algorithm

![](./wc.png)

The 2023 Cricket World Cup winner prediction using the Random Forest algorithm involves a machine learning technique that analyzes various historical and current cricket data factors, such as team performance, player statistics, pitch conditions, and more. By considering these factors, the Random Forest algorithm generates predictions for the tournament's winner. This method enhances the accuracy of predictions by aggregating multiple decision trees and ultimately helps cricket enthusiasts and analysts make informed guesses about the potential champion of the 2023 Cricket World Cup. 

Check out the corresponding medium blog post: https://medium.com/@paulandrew1507/the-road-to-glory-predicting-the-icc-world-cup-2023-champion-dd44f9328bd2

## Goals

* To forecast the tournament's winner with a high degree of accuracy, based on historical and current data.
* To analyze various cricket-related data, including team performance, player statistics.
* To identify and evaluate the most influential factors affecting a team's chances of winning, helping teams and analysts focus on critical aspects.
* Additionally, predict the results of individual matches throughout the entire tournament.
* Conduct simulations for upcoming matches, specifically the semi-finals and finals.

## Data

I have collected data from HowStat.com, which includes the results of ODI matches since the 2015 World Cup. While I acknowledge that the model's accuracy may not be exceptionally high, I believe it provides a reasonably good sense of the trends. I chose not to include matches prior to the 2015 World Cup because I consider recent results to be more influential, with older data carrying less weight. For the remaining data files, I sourced them from the Cricbuzz website.

## Environment and tools
1. Google Colab
2. Numpy
3. Pandas
4. Seaborn
5. Matplotlib
6. Scikit-learn


I employed datasets consisting of the ICC rankings as of August 2023 and a fixture dataset outlining the group stage matches for the tournament. I conducted a comparative analysis of Support Vector Machines, Naive Bayes, Random Forest, and K-Nearest Neighbors models.

Among these models, Random Forest emerged as the top performer, achieving a training accuracy of 74.9% and a test accuracy of 67.3%.

Based on the outcomes of this model, it suggests that India has a higher likelihood of winning the World Cup.

## Reference
https://github.com/abhinavsagar/ICC-2019-WC-prediction
