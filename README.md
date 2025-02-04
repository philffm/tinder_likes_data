# tinder_likes_data
Gathering data of **Likes Sent** on [Tinder](https://tinder.com/) within the past 7 days. <br><br>
![Imgur](https://imgur.com/hSVjccD.jpg)

## Table of Contents
- [Versions](#versions)
- [Non-Python Requirements](#non-python-requirements)
- [FAQ](#faq)
- [Output](#output)
- [Potential Future Updates](#potential-future-updates)

## Versions
1. November 25th, 2021 - Added `like_data.py`, a script that gets the name and age of all of the profiles from **Likes Sent**.
2. November 27th, 2021 - Added functionality to `like_data.py` for downloading the profile picture (i.e., the main picture) from each profile from **Likes Sent**.
3. November 30th, 2021 - Added `pics_and_vids.py`, a script that downloads all pictures and videos from each profile from **Likes Sent**.*
4. December 2nd, 2021 - Added `card_data.py`, a script that downloads profile card data from **Likes Sent**.
5. December 4th, 2021 - Added `tinder_analysis.py`, a script that provides basic statistics and a word cloud from the Excel workbook from `card_data.py`.
6. December 13th, 2021 - Added `pics_and_vids_2.py`, a more advanced version of `pics_and_vids.py` which uses an Excel workbook as a database. The data are appended to an existing Excel workbook's worksheet so data can be gathered over time.
7. December 19th, 2021 - Added `hash_images.py`, a script that outputs a text file with the image name and its respective hash value.

## Non-Python Requirements
- Tinder Platinum.
- Google Chrome running on localhost. See [this video](https://youtu.be/FVumnHy5Tzo) for details.
- Microsoft 365 (used for Microsoft Excel).

## FAQ
### 1. What is Tinder?
- The [Wikipedia page](https://en.wikipedia.org/wiki/Tinder_(app)) for Tinder provides a great description.
- [Tinder's website](https://tinder.com/about-tinder) has an *About* section.

### 2. What is Tinder Platinum?
Taken from [Tinder's website](https://tinder.com/feature/platinum):
> Enjoy all of Tinder’s premium features while getting maximum visibility on the app. Dating online just got easier. See someone you’d love to meet and can’t wait to match? As a Platinum subscriber, you can attach a note to every Super Like you send, increasing your match-making potential by up to 25%. And when you do—feel free to stand out in a major way by complimenting their photos or giving them your best opener. By making the first move, you can speed up the process and start to chat with people sooner.

### 3. How much does Tinder Platinum cost?
Tinder platinum cost me $28.77 USD when I purchased it on 11/20/21. It is a **monthly** recurring charge. Please note that I am 31 years old and live in the U.S.
![Imgur](https://imgur.com/x7R0ruB.jpg)

### 4. What is "Likes Sent"?
Likes Sent is an area on Tinder Platinum that allows you to see the profiles you've liked within the past 7 days.

### 5. What Tinder Passions can someone select from (as of 12/02/21)?
![Imgur](https://imgur.com/3d1hBA8.jpg)
![Imgur](https://imgur.com/7uwIFnM.jpg)

### 6. Are you selling these data or distributing the pictures and videos to others?
No, the data are shown for research purposes and the pictures and videos are downloaded then deleted.

## Output
### 1. Excel workbook from `like_data.py`
![Imgur](https://imgur.com/6WjLKCs.jpg)

### 2. Saved jpgs from `like_data.py`
![Imgur](https://imgur.com/gD7bIJ4.jpg)

### 3. Basic Data Analysis from data of `2,169` likes from `like_data.py`
![Imgur](https://i.imgur.com/IbCubjv.png)
***
![Imgur](https://i.imgur.com/0Bhshd2.png)

### 4. Saved jpgs and mp4s from `pics_and_vids.py`
![Imgur](https://imgur.com/DjmsSP6.jpg)

### 5. Time lapse: downloading 10,990 pictures and videos from `pics_and_vids.py`
[![Video](http://img.youtube.com/vi/ZWvZJnCau0s/0.jpg)](https://www.youtube.com/watch?v=ZWvZJnCau0s "Tinder Time Lapse")

### 6. Tinder Women's Passions from `1,305` likes from `card_data.py`
![Imgur](https://imgur.com/WPltmKJ.jpg)

### 7. Count of Distances from `1,305` likes from `card_data.py`
![Imgur](https://imgur.com/cyTA2nO.jpg)

### 8. Song Analysis from `1,305` likes from `card_data.py`
![Imgur](https://imgur.com/VotItmm.jpg)

### 9. Word cloud from `1,305` likes' bios from `tinder_analysis.py`
![Imgur](https://imgur.com/Ev2Yud3.jpg)

### 10. Standard output from `tinder_analysis.py`
![Imgur](https://imgur.com/fy9ItA6.jpg)
![Imgur](https://imgur.com/OWIYa6R.jpg)
![Imgur](https://imgur.com/H1gP5st.jpg)
![Imgur](https://imgur.com/5t5Qt63.jpg)

### 11. Emoji workbook from `tinder_analysis.py`
![Imgur](https://imgur.com/YbWLuR3.jpg)

## Potential Future Updates
1. <s>Create a relational database that stores profile information and hashes of images.</s> <br>
I'm currently using Excel as my database instead of a relational database (e.g., sqlite or PostgreSQL).
2. Since some emojis are not read in the current `tinder_analysis.py` script, see if there's a way to properly decode them.
