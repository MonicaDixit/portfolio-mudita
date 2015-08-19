---
layout: post
title: Blocchat
thumbnail-path: "img/blocchat.png"
short-description: A realtime chat application using angularJS framework and firebase api.

---

{:.center}
![]({{ site.baseurl }}/img/blocchat.png)

## Synopsys

Blocchat is an realtime chat client using AngularJS and firebase api. Users can send and receive messages in real time.



## Know more

A user can create a chat room and start chatting with another user when they join the room.
The messages are stored in a firebase array and is synchronised for multiple users for multiple chat rooms.

{:.center}
![]({{ site.baseurl }}/img/BlocchatRooms.png)



A user would be required to provide a user name and this username would be appended to messages they send after joining a chat room.

{:.center}
![]({{ site.baseurl }}/img/BlocchatNewRoom.png)

Angular UI was used to create modal dialog boxes, for setting the username and creating new rooms. Just as a user could join a room to start chatting by hitting the 'join room' button, in the same a user could exit out of the room by hitting the 'quit room' button.

{:.center}
![]({{ site.baseurl }}/img/BlocChatUsername.png)


It is intersting to note here that the chat app has all the features of a realtime application without using anything other AngularJS and firebase.

Ok , lets start chatting !  

  