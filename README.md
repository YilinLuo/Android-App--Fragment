# Android-App--Fragment
This is a practice with Android APP fragment activity control. In the app, you can type in some message, send it to the top  of the view, and then decide to send it down. 

You can download the zip file and run it in your Android Studio!

Some technicalities:

1, One vertical Linearlayout that has one main layout and two frame layouts that each contains one fragment. The three layouts are spread out into three equal areas.

2, text input in main would be transported to TopFragment on button “send message”;
Sentence in Top Fragment would be transported to Bottom Fragment on button “send back”.

3, I used Bundle on TopFragment, and I used interface on communicating data between two fragments in one activity. 

