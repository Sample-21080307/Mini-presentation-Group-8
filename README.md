# Mini-presentation-Group-8
Report of Mini presentation Group 8 

1.	**Introduction**
+	Information about the NBA:
NBA (National Basketball Association) was founded in 1946. NBA stands for National Basketball Association, i.e National Basketball Association. This is the world's leading professional basketball league, based in the United States and Canada.
	With 30 teams divided into two conferences, the NBA is not only a place for athletes to compete but also a culture and a lifestyle. NBA matches always attract millions of spectators around the world, creating a community of passionate fans. 
	NBA, not simply a sports league, but also a giant entertainment industry. From dramatic matches, beautiful plays to side stories, NBA always provides fans with great entertainment experiences. With the rise of social media, the NBA has become a global cultural phenomenon, connecting people from every country.
+	The main discussion point
Finding and developing young talent is a vital factor for the longevity and development of the NBA. By constantly searching for future stars, the tournament not only ensures exciting competition but also creates inspiring stories that attract a large number of fans. Young talents bring new ideas and unique playing styles, helping to enrich basketball and maintain the tournament's appeal. At the same time, developing young players is also a way for the NBA to expand its global influence and build a strong basketball community.
Based on data on the statistics of basketball players in the NBA since 1950, I want to bring to the attention of the managers of the basketball association the importance of finding and developing new young talents. This not only helps improve the competitiveness of the players but also brings a breath of fresh air to the basketball sport in general and attracts many interested fans whenever new talents are discovered.
2.	Data discussion

  ![image](https://github.com/user-attachments/assets/eac62cb0-7f7f-4eff-a8ae-1d16992d477a)


 
2.1. Overview of data

+	Analyze columns
In the data we can see that the data has 8 columns and 3922 rows based on the function “Print("Total of columns: ",df_iris.shape[1])” and “Print("Total of rows: ",df_iris.shape[0])”
Based on the data table given above, from left to right, the first column is the player numbers and there are a total of 3922 players. The next column is the full name of the players, the next column is the height index and next to that is the column about the players' weight index. Next are the universities that the players attend. Indispensable are the year of birth columns and the cities where the players were born. Finally is the state the player was born in. For our group, there are 3 extremely important indicators in the table that contribute to making an excellent NBA player: the height index column, the school where the player studies and the city where the player was born. 
+	Which column is important to analyze?
Look at the board NBA Players stats since 1950 We can see a lot of information about the players, and height in basketball is very important. The advantage of height can help them receive the ball more easily and defend more effectively. Height is often accompanied by other important characteristics of a basketball player, including arm reach and arm span, more Taller players often have more control over the aerial advantage, increasing the effectiveness of smashes and blocks. Besides, university is a factor - a place to train players with basic skills to play basketball. Universities have modern, well-equipped basketball courts, creating favorable conditions for students to practice and compete. Specialized training equipment and training support technology help improve athletes' skills. The city where the players live is also important. Big cities often organize many tournaments, giving players the opportunity to compete and develop skills. Training programs in big cities are often methodically and professionally designed. Big cities often have rich basketball cultures, exposing players to many different playing styles and strategies.

2.2. Cleaning process
	Our data cleaning process will be based on the following key factors:
+	Missing value
+	Duplicate value
+	Reality of data
a)	Handling missing values
In this data, we first use the function “Data.info” to check the data and notice that there are quite a few Null values, that is, missing values. Specifically, when using the function "df_iris.isna().sum()” specifically showed the null values as follows:

![image](https://github.com/user-attachments/assets/6c516b2b-236f-4742-824e-4801f326a4d1)

 
We used functions “Dataframe.dropna()” to handle the missing values of the columns and then those missing values disappeared in 7 columns of data. The output value gave us the following result:
 
Additionally, In functions “Data.info”,  We also want to check the format of each column and see what the output is Dtype gave correct results.

![image](https://github.com/user-attachments/assets/e4dbfb9d-5f7a-4cf8-9620-82dd9f8a39a0)


We then use the function “Data.duplicated()” to check for possible duplicate data and handle duplicate data of each column, but the results show that there is no duplicate data:

 ![image](https://github.com/user-attachments/assets/cb067a1e-0b18-47f4-98aa-90392bc6dce5)


Next we want to check if the columns appear to be unique variables using the function:
print("All unique variables in", x) 
print(df_iris[x].value_counts()) 
print("")
and the results let us see that the columns are normal and do not have any special values.

Finally we use the command “Df.describe” to check one last time after cleaning and now the data has been cleaned.

3.	Chart discussion base on data
3.1. Chart 1: Top 10 city with the most NBA’s Players

 ![image](https://github.com/user-attachments/assets/6d55367e-a28b-4dab-9c71-d2096ec29370)


Below are the "Top 10 cities with the most NBA players". We can easily see that Chicago has the highest number of NBA players with nearly 200. The chart shows a clear city trend. Big as Chicago is the birthplace of many NBA players. So we should focus on developing and finding talent in these cities. On the other hand, Los Angeles and Philadelphia also have a large number of people participating in the NBA with more than 80 people.

 Investment in facilities Modern sports centers and training grounds will help develop skills and create conditions for young players to have better opportunities to practice and compete. Establishing high-quality training programs is important to encourage more young talent and help them develop further. In addition, opportunities such as tournaments, training camps and support from former players can also play an important part in building a foundation for basketball in Chicago. Furthermore, organize activities to invite famous and experienced players at the first meeting to share knowledge, experience and necessary skills and tactics in matches before entering the NBA and be recognized. Hosted by famous professional NBA players will attract many young talents, helping them improve their hard and soft skills. Moreover, the City of Los Angeles and Philadelphia should also be interested and keep an eye on potential young players here. 

 That's why the NBA needs to invest heavily in the above factors so that players have the opportunity to develop and easily find potential young players.

3.2. Chart 2: Top 10 college with the most NBA’s players

 ![image](https://github.com/user-attachments/assets/24034085-ae9a-44b7-9f8b-58c53619d97f)


The University of Kentucky and The University of California, Los Angeles (UCLA) have the highest number of alumni currently playing in the NBA with more than 80 players, which is far surpassing other universities on this list. This shows that we should focus on developing and seeking talents in these two  universities. Secondly, other universities in the top 10 are also well-known names in American college basketball and provide a significant amount of talent to the NBA. 
In summary, this table shows that universities have students participating in the NBA. This indicates that the NBA is growing and becoming increasingly popular. One of the most effective ways for the NBA to scout for potential young talented players is to strengthen collaboration, mainly with the University of Kentucky and University of California. Establishing specialized training programs, supporting facilities, and organizing exchange events will help college players access the most modern knowledge and skills. Additionally, expanding the scouting network and applying modern technology in the talent evaluation process are also important factors for the NBA to seek and discover future stars. On the other hand, other universities may have numerous potential players so we should also keep an eye on them. 
To create more opportunities for scouting potential young players, the NBA could consider Providing scholarships and financial support for potential young players, helping them focus on training and developing their skills to the maximum. Furthermore, connecting young players with former NBA stars and experienced coaches for professional and spiritual guidance and advice is quite necessary to reinforce what they need when enter the NBA arena.

3.3 Chart 3: NBA players height
 ![image](https://github.com/user-attachments/assets/eab44e31-e222-477d-8755-dca1a35dbe9e)




The histogram chart of NBA player heights shows that the ideal height ranges from 185cm to 210cm. The red line in the chart represents an average height of about 200cm. Based on that, the NBA should focus on finding young talents in this height group, for example by organizing selections at high schools and universities. However, players with different heights should not be ignored. For shorter players, attention should be paid to their speed, technique and ability to handle the ball, for example by observing their skills in youth tournaments. On the contrary, for players over 210cm tall, the NBA should focus on arm span, jumping ability and movement. Height is a huge advantage for basketball players and this is a factor that cannot be ignored. Height helps players be able to develop and adapt well in all elements of the game. We suggest that the NBA needs to pay attention to height first, specifically looking for young players with an average height of 185cm to 210cm. Additionally, the NBA could establish youth player development programs that focus on nutrition, training and other factors that can promote healthy height growth.  Cooperate with  nutrition and sports experts to develop scientific diet and exercise regimens for young players. The NBA can also organize summer basketball camps, giving young players access to a professional training environment, thereby optimizing their development potential.




4.	Conclusion 

Finding and nurturing young talent is an important, long-term strategic task for the development of any field, especially in professional sports like basketball. Investing in the young generation not only helps leagues like the NBA maintain their attractiveness and competitiveness, but also contributes to promoting the overall development of the sports industry. Discovering and nurturing young talents early is to create a solid foundation for the future, ensuring inheritance and sustainable development. By combining traditional methods with modern technology, focusing on human factors and building a comprehensive development environment, we can create favorable conditions for young talents to maximize their potential. potential, reach its peak and contribute to the overall development of the community.


	
