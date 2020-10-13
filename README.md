# Predicting-YouTube-Likes
 
![Project Image](https://www.techinexpert.com/wp-content/uploads/2019/05/buy-youtube-likes_dd9e56d7-2c6e-457f-b8a9-0a25d4913999.jpg)

---

## Can the Number of Likes a Youtube Video will get be predicted?
As YouTube becomes one of the most popular video-sharing platforms, YouTuber is developed as a new type of career in recent decades. YouTubers earn money through advertising revenue from YouTube videos, sponsorships from companies, merchandise sales, and donations from their fans. In order to maintain a stable income, the popularity of videos become the top priority for YouTubers. Meanwhile, some of our friends are YouTubers or channel owners in other video-sharing platforms. This raises our interest in predicting the performance of the video. If creators can have a preliminary prediction and understanding on their videos’ performance, they may adjust their video to gain the most attention from the public.
 
You have been provided details on videos along with some features as well. Can you accurately predict the number of likes for each video using the set of input variables?

## Hypothesis Generation
Simply put, a hypothesis is a possible view or assertion of an analyst about the problem he or she is working upon. It may be true or may not be true.
* **Do videos with more views get more likes** ?
* **Do videos with more comments get more likes ?**
* **Do with videos with more dislikes get less likes ?**
* **Do longer videos get more likes than shorter videos ?**
* **Do descriptive videos get more number of likes ?**
* **Does a channel affect the number of likes?**
* **Does the country of origin affect the number of likes ?**
* **Do people post more videos on weekends than weekdays ?**

### Data Description
**Train Set** 

|Variable |Variable Type |Variable Description |
| -------- | ------------- | -------------------- |
| video_id |	ID           	| Identifier for each video |
| title   	| Text          |	Name of the Video on Youtube |
| channel_title |	Text/Category |	Name of the Channel on Youtube |
| category_id	| Category |	Category of the Video (anonymous)|
publish_date	| Date |	The date video was published |
|tags |	Text	| Different tags for the video |
| views |	Numerical |	Number of views received by the Video |
| dislikes	| Numerical	| Number of dislikes on the Video |
| comment_count |	Numerical	| Number on comments on the Video |
| description |	Text	| Textual description of the Video |
| country_code |	Category	| Country from which the Video was published |
| likes	| Target	| (Target) Number of Likes on the video |


**Test Set**

