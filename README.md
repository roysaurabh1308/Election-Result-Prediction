# Predicting Elections Using Twitter Data Analysis
## About
With the rapid development of the Internet, more and more users are expressing their views using social media platforms and hence social media have changed the information behavior because of Realtime access of information to the people without restriction of time and data resources. About 1 quintillion bytes of data is generated on the daily basis, enriched of sentiments in the form of posts, status updates, tweets and blog posts etc. In this project, we are going to analyze a large number of election-oriented post by general social media (twitter) user. Based on these users posts, system will analyze if there exist any pattern between these posts and will apply sentiment classifier model and draw relevant information from the collections of these posts recorded over some period of time; the presented method point out the likelihood of development of a categorization model to identify the political orientation of the social media users based on the posted content and other social media based traits. Now since the twitter dataset which is needed to be extracted and processed for sentimental classification followed by the election result prediction contains over billions of tweet texts from twitter users, hence is beyond the capabilities of the normal processors. That is where Big Data concepts and methodologies comes into the picture. We will use popular Big Data tools like Apache YARN, Apache HIVE, Apache HADOOP (HDFS and MapReduce), Apache Flume etc. in order to efficiently extract, manipulate and process such massive amount of data and will use this analysis for the election prediction.


## My Model
My model is based on the technique that analyses the posts on the basis of keywords and hashtags. The implemented system collected the data on the basis of hashtags related to political parties and their agendas. The political orientation of peoples toward any particular party/ candidates can be predicted using these posts on social media. Now a day’s social media is flooded by journalists, politicians, film stars and academicians; for its extremely political value. Many politicians and political parties use these platforms to spread their agendas to general peoples specially the youth. These all post can be categorized on the basis of various points like to get the people opinion of any particular geo-location / area which might be helpful for the parties to design their political campaign for victory. This proposed model basically focused on collecting the posts to use volume analysis. A trend analysis on a popular and trending political parties/ candidates and a sentiment analysis to distinguishing on negative positive and posts for a candidates and party help them to act accordingly to make their reputation high. These trends also help the people to make their opinion about the political parties and their candidates. Our system architecture for this work is depicted in fig. 1.


## Results 
Based on Hadoop platform and java for Map Reduce framework, we have implemented this system. Porter Stemmer Algorithm and other user-defined functions are used to process the tweets from twitter database. And as discussed above these processed tweets will be pre-owned as input for the system for various analysis modules to generate sentiment, trend and volume analysis. We have applied our model on the above-mentioned twitter election data of Maharashtra 2017 general election and achieved an accuracy result which is consistent with the actual election result.


# Structure and Result #

|<img src="Structure and Result/Arch.png">|
|:--:|
|**Architecture**|

|<img src="Structure and Result/Hadoop.png" width="267">|<img src="Structure and Result/Yarn.png" width="267">|<img src="Structure and Result/Flume.png" width="267">|
|:--:|:--:|:--:|
|**Hadoop Structure**|**YARN Structure**|**FLUME Structure**|


|<img src="Structure and Result/Hive.png" width="267">|<img src="Structure and Result/Res.png" width="267">|<img src="Structure and Result/Table.png" width="267">|
|:--:|:--:|:--:|
|**HIVE Structure**|**Result**|**Hashtags Counts**|

|<img src="Structure and Result/Sentiments.png" width="267">|<img src="Structure and Result/Hashtags.png" width="267">|<img src="Structure and Result/Stats.png" width="267">|
|:--:|:--:|:--:|
|**Sentiment Analysis**|**Hashtags Graph**|**Election Statistics**|


## Tools Used
* [Tensorflow](https://www.tensorflow.org/) : Used as the Deep Learning Library.
* [Apache Hadoop](https://hadoop.apache.org/) : As a File Distribution system & MapReduce.
* [Apache YARN](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html) : As a resource manager.
* [Apache FLUME](https://flume.apache.org/) : For Data Ingestion.
* [Apache HIVE](https://hive.apache.org/) : As Data Warehouse.
* [SK Learn](https://scikit-learn.org/) : For Data Preprocessing & Results.

## Conclusion
Big Data is really a fascinating concept which have an endless scope with infinite applications. Observing the expanded use of social media platforms, this cutting-edge paper concentrated on exploring of social platform as the chase for elections campaign. Understanding India to be one of the highest socially connected countries, having greater than 70% of its young generation below 35 years of age; Social platform plays essential part young youth’s life. The designed system had worked upon the analyses of the Maharashtra state meeting election; taking a look at the impact of social platforms on the politics system of Maharashtra, found people can express their perspectives in one hundred forty characters more efficiently and openly. Our model was found to be accurate which is consistent with the actual result election. Hence, we can safely conclude that the Big Data tools like Hadoop HDFS, Hadoop MapReduce, Apache YARN, Apache Flume, Apache Hive, etc. are very efficient and reliable to analyze and deal with huge data applications with a good accuracy, which is impossible to achieve with traditional systems.


## Contributing
You are welcome to contribute :

1. Fork it (https://github.com/roysaurabh1308/Election-Result-Prediction/fork)
2. Create new branch : `git checkout -b new_feature`
3. Commit your changes : `git commit -am 'Added new_feature'`
4. Push to the branch : `git push origin new_feature`
5. Submit a pull request !

## Author 
**Thanks for going through this Repository! Have a nice day.**</br>
**Have any querry? Feel free to contact me.**</br>
</br>**Saurabh Roy**</br>
#### **Contact** :`roysaurabh1308@gmail.com`
<p align="left">
<a href="https://github.com/roysaurabh1308/" target="_blank"><img src="Documentation/icons/github.svg" height ="40" alt="github"></a>
<a href="mailto:roysaurabh1308@gmail.com" target="_blank"><img src="Documentation/icons/mail.svg" height ="40" alt="Gmail"></a>
<a href="mailto:saurabhr17100@iiitnr.edu.in" target="_blank"><img src="Documentation/icons/mail1.svg" height ="40" alt="College Mail"></a>
<a href="https://www.linkedin.com/in/saurabh-roy-18811014b" target="_blank"><img src="Documentation/icons/linkedin.svg" alt="Linkedin"></a>
</p>

## License
This Project is licensed under the MIT License, see the [LICENSE](LICENSE) file for details.
<br>
<br>
<p align="center"><img src="Documentation/icons/thank-you.png" height=50></p>
