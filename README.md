# Minipresentation 
<html>
<body>
<h2>1. Introduction</h2>
<p>Hi, everyone. Today my team wil present how we collect and analyze data.
This is data about the Australian FootBall League including information about playerId,displayName,height,weight,dob,position,origin.And where we collected this? We collect them here on Kaggle.com.This web have many datasets for people to analysis with many topics. We want to study player statistics for the Australian Rules Football League (AFL), use different charts to determine who the main players are, predict performance performance and results. Our aim is to filter information about the players to select the best players. Important players performance that no one has noticed before. With scoring competitions in the AFL as popular as any other sport, surely this is just waiting for Data Science to take over.</p>
<p>First, we updated fiel data to jupyter and type code to have 5 different charts.First chart about the dispersion in the correlation between weight and height of players.</p>
Chart 1: 
<br>dfscatter = df[['weight','height']]
<br>plt.scatter(dfscatter['weight'], dfscatter['height'], color='pink', s=50, marker='*') 
<br>plt.ylabel("weight")
<br>plt.xlabel("height")
<br>plt.title("The dispersion in the correlation between weight and height of players ") 
<br>plt.show(). <br>
<center><img src="chart 1.jpg" alt="Error display image" width="500" height="500></center>

<p>Describe chart 1:
In this chart we can see, the largest number of points is concentrated in the lower left quadrant, representing players with higher height and greater weight,it ranges from over 170cm - 190cm and from 70kg - under 90kg.
Next, a moderate number of points are concentrated in the middle of the chart representing players with heights from over 190cm - under 200cm and weight from over 90kg - under 100kg.
A small number of points concentrated in the upper right quadrant represent players over 200cm tall and weighing over 110kg.</p>
</body>
</html>

