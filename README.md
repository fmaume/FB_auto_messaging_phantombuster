Phantombuster made their own API for it which should be better maintain.

Get from the code from https://github.com/phantombuster/api-store/blob/master/store/Facebook%20Message%20Sender/Facebook%20Message%20Sender.js

Get the API from https://phantombuster.com/api-store/8852/facebook-message-sender?referral=fmc-f8VgvF4 


# FB_auto_messaging_phantombuster
In this depository you will find the required code to send automated Facebook messaging using Phantombuster.

## In order to use this script you will need:
- To create a phantombuster account: https://phantombuster.com/?referral=fmc-f8VgvF4 
- To create a copy of this googledoc file: https://docs.google.com/spreadsheets/d/1t7MhTtYa6vdrxuB8DyuOwe0Fp7Hjs54W9Qv4wbmO6-8/edit?usp=sharing
- Have access to a facebook account

## Step by step Gide:
1. Create a copy of google above. Use this doc to provide list of Facebook account you want to contact, message you want to send

2. Create an account on Phantombuster: https://phantombuster.com/?referral=fmc-f8VgvF4 

3. Create an API agent (under My APIs menu, create an API using NickJS template)

4. Copy paste the code from Agent_script to replace the code sample from NickJS template

5. Go to setting of you API:

  * 5a Copy past the code from Agent_object under Agent Object
  * 5b Replace cookie_user parameter by your own
  * 5c Replace cookie_xs by your own
  * 5d  Replace google_url by a link to your own google file
  * 5e Select Repetitively once a days or once every 2 days (you can use advance setting if you which to setup specific time)
  
6. You are all set. The automation will run until all facebook account you put in the google doc are contacted.

## how to get cookie parameter?
On Chrome simple type F12 to open developer tool. Then go under Applications tab.

For Mozila: https://developer.mozilla.org/en-US/docs/Tools/Storage_Inspector

For Safari: https://www.macobserver.com/tmo/article/see_full_cookie_details_in_safari_5.1
