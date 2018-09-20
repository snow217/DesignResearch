# Research on Discord
**All-in-one** **voice and text** **chat for gamers that's free, secure, and works on both desktop, Xbox and phone.  (Not on PS4 and switch yet)**
By Xueming Sherry Xu


![](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537400254523_Discord-LogoWordmark-Color.png)

- Video gaming communities
- Provides partial support for rich text via the [Markdown](https://en.wikipedia.org/wiki/Markdown) syntax - Specializes in text, image, video and audio communication between users in a chat channel
- Runs on Windows, macOS, Android, iOS, Linux, and in web browsers
- 130 million unique users of the software as of May 2018



![Discord Desktop Overview](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537395055372_+2018-09-19+3.10.10.png)




## Information Architecture
![](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537469300818_Info+Archtecture.png)


To start with, I wrote down information architecture of Discord. There are three main components for this system, including Friends Hub, Server hubs and Me.  All of users have same level of control thought Friends Hub and Me section. Users have different level of control though Servers based on their roles of that certain servers.



![Discord Home Page (Starting Point)](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537402002094_+2018-09-19+5.01.11.png)


Discord home page is a starting point allows you to see real time update of your friends activities and game activities, which encourages users to jump into a game whether with their friends or by themselves.


## UI Layout Overview

I regard the page (Server & Channel Page) above as main page because Discord remembered the page you interacted last time, plus I saw the most usage of servers interaction from most of users.

![Layout Overview - Main Page](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537468837296_Discord+Research_UI+Layout.png)



![System Layout Overview - Main Page](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537468823753_Discord+Research_White+UI+Layout.png)


From system layout overview, we saw order of Discord system design - From top(home) to bottom(single person) and from left & right (Server) to center(Channel). This is also refer to user’s reading order in real life that avoids your eyes jumping around when reading information. 



## Section UI
![Discord spends much of its time listening to user feedback in order to enhance and update their app. (By Tea Chang -  https://medium.com/cup-of-tea/another-look-discord-7c6121e8b264)](https://cdn-images-1.medium.com/max/1600/1*SPVbZZIOVJIka9KwVNXTNw.png) (By Tea Chang -  https://medium.com/cup-of-tea/another-look-discord-7c6121e8b264)




- **Easier Messaging is Top 1**

Discord aimed to put ‘easier messaging’ as the top one goal though the whole app.  From the UI layout that I generated, space that allowing user to message is located in center of the App and has larger space than other.

![When I narrow down the app, I can still message in group](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537426380489_+2018-09-19+11.52.25.png)


When I narrowed down the whole app, the app is responsive (absolutely) with messaging feature always in center. 


![Allow user to send quick reply message without jumping out of current state](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537427017017_hello.gif)


Easier Messaging is not only being considered though server discussion, it also applies to 1-on-1 chat. Once upon a time you had to slowly and methodically tap your way through sections and between servers and friends list just to send and respond to messages. Discord allows you to do rapidly respond by hover user’s avatar.



- **Invite Visibility - Invite your friends? Easy!**

From Information Architecture that I did, I noticed Discord put invite friends visible everywhere to encourage user to do the action.

![1st way to Invite People to Server](https://cdn-images-1.medium.com/max/1200/1*OAGC9a4lUO3Juypdl0pFBw.png)


Once you joined a server, a small banner shows up on left hand side above channel list to lead you invite friends and help to build the community. You can turn off this banner easily so it won’t show up again.


![2nd way to Invite People to Server](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537428653305_invite.gif)


Discord allow users to do instant invite easily by hover though channel list. Once you hover though channel list, the invite icon shows up.



![3rd way to Invite People to Server](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537428729266_Invite3.gif)


By tapping on server name, Discord provides the 3rd way for  users to do invite behavior. 
As you can see Discord tried to have Invite visibility as much as they can to encourage users to invite and build community.



- **Server & Channel Switcher**
![Discord Server & Channel Switcher](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537467757638_Switcher.gif)


Discord allows users to switch over between servers and channels to focus on chat itself. By only one tap away, user can jump into the certain servers they want very easily. Also server switcher also allows users to switch between friends list and server lists.


![Server Switcher](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537468460951_Screen+Shot+2018-09-20+at+11.34.02+Sherry+Xu.png)
![Channel Switcher](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537468613319_Screen+Shot+2018-09-20+at+11.34.09+Sherry+Xu.png)


Discord is using channel title for channel switcher.
Discord is using profile-picture-only on server switcher.



- **User Control & Settings**

There are mainly three different settings in the system: Server setting, channel setting and personal setting. Discord uses same setting icons for all of their settings, which make those setting features easy to find and look consistent. Here is how Discord layout them: 

![Discord Server setting is under server name](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537475648323_Screen+Shot+2018-09-20+at+1.33.37+Sherry+Xu.png)
![Discord Server setting](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537475527106_Screen+Shot+2018-09-20+at+1.31.41+Sherry+Xu.png)


For Discord Server Setting, it is under server name, which is a little bit hard to find out at the first glance.  Once user tap/click on server title & arrow, an overlay of choices shows up.


![Discord Channel Setting](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537474948425_Screen+Shot+2018-09-20+at+1.21.51+Sherry+Xu.png)
![Discord Personal Setting](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537475018162_Screen+Shot+2018-09-20+at+1.17.22+Sherry+Xu.png)


But when you look at the bigger picture of the system, you can find out that there are two same setting icons show up at the same section to serve different setting actions.

![Roles Control for Admin](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537476329255_Screen+Shot+2018-09-20+at+1.16.44+Sherry+Xu.png)



![https://discordapp.com/features](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537479982591_Screen+Shot+2018-09-20+at+2.46.01+Sherry+Xu.png)


As an admin of Discord, you  have ability and freedom to provide different permission to different roles of users. Also you can add/define roles based on your needs.




- **Unread indicator**

Having appropriate notification helps users to have a sense of engaging but not too annoying. Discord introduces their dynamic unread indictors, which provides users expectation before they jump to those content.

![Unread Servers](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537477324944_Screen+Shot+2018-09-20+at+1.44.33+Sherry+Xu.png)
![Unread Channels](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537477316587_Screen+Shot+2018-09-20+at+1.44.44+Sherry+Xu.png)
![Unread Messages](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537477354927_Screen+Shot+2018-09-20+at+1.44.26+Sherry+Xu.png)



- **Mute Control**
![User has one tap away to mute a channel](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537478080017_Screen+Shot+2018-09-20+at+2.14.03+Sherry+Xu.png)


Discord makes user mute a certain channel very easily. By clicking on mute icon on top of the channel, the channel will be muted.


![Mute Server](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537478212657_Screen+Shot+2018-09-20+at+2.16.34+Sherry+Xu.png)


Discords also provide user’s freedom to mute the entire server. If you still want to catch up what will be related to you, you can choose ‘only @mentions’ on notification settings.


![Personal mute control](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537478645093_Screen+Shot+2018-09-20+at+2.23.55+Sherry+Xu.png)


Users can get to know their own status from those simple icons at first glance, that provides users feeling to safe when using Discord.



- **Finding right person to answer your question?**
![](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537478992257_Screen+Shot+2018-09-20+at+2.29.44+Sherry+Xu.png)


There is an user case which is, you are new to the group and you are looking for the right person to answer your question? Discord designed a small indicator to show you who is the server admin. So you can easily find them and ask them questions.


![Slack also has a good solution to lead 1st time user](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537479097795_Screen+Shot+2018-09-20+at+2.31.27+Sherry+Xu.png)




- **Dynamic Model and Static Model Overlay**

Discord also distinguish different level of importance between different models.
Here are some **Dynamic Models:**

![Connection information](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537479381142_Screen+Shot+2018-09-20+at+2.34.23+Sherry+Xu.png)
![User’s infomation](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537479378292_Screen+Shot+2018-09-20+at+2.34.30+Sherry+Xu.png)
![Pinned message](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537479374067_Screen+Shot+2018-09-20+at+2.34.36+Sherry+Xu.png)


Those are examples of dynamic models - providing information for users as reference and won’t block users from reading messages.

Also, there is another model that called **Static Model.** Discord uses static model to display important actions and information that makes users focus on those content itself.

![Helps](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537479563615_Screen+Shot+2018-09-20+at+2.34.58+Sherry+Xu.png)
![Delete Servers](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537479566692_Screen+Shot+2018-09-20+at+2.34.51+Sherry+Xu.png)
![Settings](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537479569834_Screen+Shot+2018-09-20+at+2.34.44+Sherry+Xu.png)



- **Rich 21st century Text format**
![Discord allows different formats of text](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537479733113_Screen+Shot+2018-09-20+at+2.41.38+Sherry+Xu.png)
![Roblox announcement on Discord](https://d2mxuefqeaa7sj.cloudfront.net/s_73D4C0FA1D17B009119B4C6243737CCE6E670D23BEF5848FF3E4996788067279_1537479736110_Screen+Shot+2018-09-20+at+2.41.19+Sherry+Xu.png)


Discord embeds most types of media directly in the chat. Also, they allow using Markdown to create better format of messages. Users are allowed to add reaction though messages, that has more feeling of engaging in Discord!



## User’s Pain Point
1. Confusion on member list indicate whether Server members or Channel members 
2. Confusing between Server invite and Channel Invite
3. Tell a certain server only from its avatar?
4. How to leave a voice channel once I am in?
5. Too many icons shows up on same page



## What users want the Most?
- **Icon to distinguish someone is on mobile or PC, also admin icons**

Make user’s status more clear. Also make admin more stand out so members have idea on who to ask.


- **Dyslexic and visually impaired accessibility**

Add options for custom fonts, colors, sizes, etc. for those who need easier visual access. 


- **Timed Mutes**

Should be able to mute users direct messaging me. And it would be nice if I could do it for a period of time ie 30mins, 3hours, until 6pm etc. 


- **Mention @ certain roles of people in server**

Right now custom roles can either be mentioned by everyone in the server, or no one at all. Having a setting to give a specific role ping access would be amazing for every discord server that uses custom roles.


- **Full Markdown Support**

Allowing user to have Headers, quotes, and codes etc to have better format of message.


- **Customizable Servers**

Having Server admins be able to change the color of the server, add background, add banners for the game, etc., would really make servers look more colorful and alive.





