# notinder


Based on the code of loltinder. It swipes left on everyone, because going on dates is silly, I want to stay home
with my cat and play videos games while eating pie. 

## Motivation

Internet dating is annoying.

## Installation / Usage

* Install node
* Clone this repo
* npm install
* Get your numeric Facebook ID from: http://findmyfacebookid.com
* Get access token from the following URL:

```sh
https://www.facebook.com/dialog/oauth?client_id=464891386855067&redirect_uri=https://www.facebook.com/connect/login_success.html&scope=basic_info,email,public_profile,user_about_me,user_activities,user_birthday,user_education_history,user_friends,user_interests,user_likes,user_location,user_photos,user_relationship_details&response_type=token
```

* Quickly copy the url, then paste it, in quotes, after your Facebook numeric ID like so:

```sh
node app.js 305102211 "https://www.facebook.com/connect/login_success.html#access_token=CAAGm0PX4ZCpsc3npjYuZASBBIwGz8rS1aQcnjn2cThwpwVVJ9QNqlejhICzkharwvX56IIw5hEsebHIaxSXAs4RvoSBLhsCaKTgQAZBGny1EICA7orRtiuhHVjspFXZBs2GT6JpHUKtlAZD&expires_in=6902"
```
