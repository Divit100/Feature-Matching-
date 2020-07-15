# Feature-Matching

This is a very interesting project where the featues of a cereal Box are matched with the same cereal box in another image where there are a lot of other cereal brands in the supermarket.
An image of the cereal whose features are to be matched:

![reeses_puffs](https://user-images.githubusercontent.com/58786895/87532631-1316e500-c6b1-11ea-837d-d9e116218ef8.png)

An image on which feature matching of the a cereal box is done.The picture is of a supermarket containing many other cereal brands on the shelf:


![many_cereals](https://user-images.githubusercontent.com/58786895/87532725-33df3a80-c6b1-11ea-968f-98b5e60df08f.jpg)


Results of the feature matching:
![Untitled](https://user-images.githubusercontent.com/58786895/87533020-a05a3980-c6b1-11ea-8fb4-f4df45ab96a6.png)


We can observe that the feature matching is having a very good accuracy usinng the FLANN Based Matcher.However,the words 'Family Size' printed at the top of the cereal are being matched with the features of other cereal boxes as they have similar labels printed on them.
