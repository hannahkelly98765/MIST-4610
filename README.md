# Modeling Instagram Data

# Problem Description
Our data model represents the social media app, Instagram. The model consists of user accounts, which have associated profiles, content, and followers/following relationships. Each post can have multiple associated media, such as images or videos, which users can interact with through likes, comments, and shares. Instagram also supports messaging between users and the creation of stories, which are temporary posts that expire after a set time period. Tracking user activity helps Instagram generate personalized recommendations and trends to improve user experience. Despite being one of the most popular social media platforms in the world, Instagram does not allow its users to schedule posts in advance or to create communities of niche interests. From a backend perspective, our model demonstrates how users would interact with these two features and new insights Instagram could gain from them.

# Data Model
<img width="978" alt="Screenshot 2023-03-30 at 8 16 49 PM" src="https://user-images.githubusercontent.com/129444082/228992019-5361b9e6-338c-46cf-a6bd-bbe885eeeddb.png">
1:M Relationships: users have many accounts, users can send many messages, users can receive many messages, content schedule can schedule multiple content, accounts can have many shares, content can have many shares, accounts can have many comments, comments can be added to multiple content, accounts can have many likes, likes can be given to multiple content.

M:M Relationships: accounts can belong to many communities and communities can have many accounts, communities can have many community types and community types can have many communities


# Data Dictionary
[Data.Dictionary.pdf](https://github.com/hannahkelly98765/MIST-4610/files/11117067/Data.Dictionary.pdf)

# SQL Queries

# Database Information
ns_21479_8
