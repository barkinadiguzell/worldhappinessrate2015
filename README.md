# World Happiness Rate For 2015

# Introduction 
The World Happiness Report is a landmark survey of the state of global happiness. The first report was published in 2012, the second in 2013, the third in 2015, and the fourth in the 2016 Update. The World Happiness 2017, which ranks 155 countries by their happiness levels, was released at the United Nations at an event celebrating International Day of Happiness on March 20th. The report continues to gain global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. Leading experts across fields – economics, psychology, survey analysis, national statistics, health, public policy and more – describe how measurements of well-being can be used effectively to assess the progress of nations. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness.
# Review Data 
![image](https://user-images.githubusercontent.com/70849534/175607837-e1b90f0f-11aa-469e-858a-d3cadfdfa1a7.png)
# Histogram of Happiness Score
![image](https://user-images.githubusercontent.com/70849534/175608052-af3b5003-031a-4add-b769-2dc0998fdf38.png)
# Unhappy Nations
- We can use df.tail(). This will show us the last 5 data and let's visualize it.
- ![image](https://user-images.githubusercontent.com/70849534/175608374-e3e3cdbc-90f7-45f3-8af6-a88555d3166a.png)
- Investigating the table, no single factor appears to fully explain why these nations appear at the bottom of the list. There are some clues to indicate why these nations appear at the bottom of the list.
## Top 10 Nations and their Happiness Score sorted by Freedom
- ![image](https://user-images.githubusercontent.com/70849534/175608553-174a56de-3918-4db2-a384-58522342019c.png)
### We can check corr
![image](https://user-images.githubusercontent.com/70849534/175608778-ff689aa7-d332-4029-a5ed-9e14d17571e3.png)
- According to this analysis, the economy is the factor that most affects the happiness rate.Then in order Family, Health, Freedom.
- ----------
- We use Tendorflow for predict and fitting the model
- ![image](https://user-images.githubusercontent.com/70849534/175609039-4ea5cc26-00db-44a4-a052-2506db6731f0.png)
#### loss Data 
![image](https://user-images.githubusercontent.com/70849534/175609106-7cb9be00-3312-4d26-9d3c-bbe9d87043e6.png)
### mean_absolute_error ( mse )
![image](https://user-images.githubusercontent.com/70849534/175609209-21706c6d-bd59-4f81-8cd9-cc9c593b6f37.png)
- *It can predict the happiness rate of countries with a 26 percent margin of error.*
