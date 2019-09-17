# NLP-Sentiment-Analysis-of-tweets-supervised-and-unsupervised-approach-
Identifying public opinion can be a powerful tool for businesses. With that in mind, user data has become hugely accessible throughout many different social media platforms. This task focuses heavily on text processing. The data source for this task is a 1-month collection of twitter tweets (July 1 2019 - July 31 2019) throughout London. Each tweet contains a text field with content posted by a user.
# Objective
The objective is to construct user Interest data (i.e what type of content is discussed by users) from
tweets posted by the users along with user sentiment about that subject. For instance, you may identify
positive or negative sentiment about certain consumer brands, or at a higher level identify categories of
tweets that receive overall positive sentiment from twitter users.
# Data Overview
The core field to focus on is extended_text, which contains the full post by the user in its raw format (no
processing has been done). Overall there are 374K tweets provided in CSV format with the following
fields:
● _id - Twitter tweet Identifier
● coordinates - Coordinates label attached by the user of the tweet (Note if the user didn't attach
any Point location Twitter labels this as NaN)
● created_at - String human-readable timestamp
● timestamp_ms - milliseconds Unix timestamp of the tweet.
● extended_text - the full-text body of the tweet (raw text data you may want to do some
preprocessing)
● bounding_box.coordinates - an associated place polygon of the tweet.

# To understand how i completed this project successfully, please check the jupyter notebook file and .ppt file with audio. Please find the attachments above.
