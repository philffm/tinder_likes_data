# tinder_likes_data
Gathering data of **Likes Sent** on [Tinder](https://tinder.com/) within the past 7 days. <br><br>
![Imgur](https://imgur.com/hSVjccD.jpg)

## Table of Contents
- [Versions](#versions)
- [Non-Python Requirements](#non-python-requirements)
- [FAQ](#faq)
- [Output](#output)

## Versions
1. November 25th, 2021 - Added `like_data.py`, a script that gets the name and age of all of the profiles from **Likes Sent**.
2. November 27th, 2021 - Added functionality to `like_data.py` for downloading the profile picture (i.e., the main picture) from each profile from **Likes Sent**.
3. November 30th, 2021 - Added `pics_and_vids.py`, a script that downloads all pictures and videos from each profile from **Likes Sent**.*
4. December 2nd, 2021 - Added `card_data.py`, a script that downloads profile card data from **Likes Sent**.
5. December 4th, 2021 - Added `tinder_analysis.py`, a script that provides basic statistics and a word cloud from the Excel workbook from `card_data.py`.

*\*Note: The script will only download the h264 compressed videos. There may be a way to get around this, but the gist of it is that non-h264 compressed videos can be the profile picture, within a profile card, and can show up in the HTML of another profile card. Currently, I'm not working on a fix for this edge case.*

## Non-Python Requirements
- Tinder Platinum.
- Google Chrome running on localhost. See [this video](https://youtu.be/FVumnHy5Tzo) for details.

## FAQ
### 1. What is Tinder?
The Wikipedia page for [Tinder](https://en.wikipedia.org/wiki/Tinder_(app)) provides a good description.
### 2. What is "Likes Sent"?
Likes Sent is an area on Tinder Platinum that allows you to see the profiles you've liked within the past 7 days.

### 3. How much does Tinder Platinum cost?
Tinder platinum cost me $28.77 USD when I purchased it on 11/20/21. It is a **monthly** recurring charge.
![Imgur](https://imgur.com/x7R0ruB.jpg)

### 4. What Tinder Passions can someone select from (as of 12/02/21)?
![Imgur](https://imgur.com/3d1hBA8.jpg)
![Imgur](https://imgur.com/7uwIFnM.jpg)

### 5. Are you selling these data or distributing the pictures and videos to others?
No, the data are shown for research purposes and the pictures and videos are downloaded then deleted.

## Output
### 1. Excel workbook from `like_data.py`
![Imgur](https://imgur.com/6WjLKCs.jpg)

### 2. Saved jpgs from `like_data.py`
![Imgur](https://imgur.com/gD7bIJ4.jpg)

### 3. Saved jpgs and mp4s from `pics_and_vids.py`
![Imgur](https://imgur.com/DjmsSP6.jpg)

## 4. Basic Data Analysis from Output data of `2,169` likes from `like_data.py`
![Imgur](https://i.imgur.com/IbCubjv.png)
***
![Imgur](https://i.imgur.com/0Bhshd2.png)

## 5. Tinder Women's Passions from `1,305` likes from `card_data.py`
![Imgur](https://imgur.com/WPltmKJ.jpg)

## 6. Word cloud from `1,305` likes' bios from `tinder_analysis.py`
![Imgur](https://imgur.com/iCEhZn0.jpg)
