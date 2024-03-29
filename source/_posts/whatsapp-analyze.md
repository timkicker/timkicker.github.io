---
title: Data about data
date: 2023-05-18 14:26:18
tags:
---


I am a huge fan of gathering, analyzing and evaluating data. Creating statistics and colorful graphs just has something to it. But the interesting part is not necessarily the data itself, it’s the data about the data. How often does something occur, at which time and by whom are very important characteristics when it comes to creating patterns.

For example, let’s look at the two weekday-graphs of two different WhatsApp chats of mine.

**Weekdays Chat A**


![](whatsapp-analyze/hourchartA.png)

**Weekdays Chat B**

![](whatsapp-analyze/hourchartB.png)

It is not that hard to figure out the difference between those two graphs. The number of daily messages in A is pretty stable except for Friday and Monday, which are two extremes. Maybe this could be about a friend group planning what they’re going to do on the weekend? The general quantity of messages is also lower as in figure B. The second chat also has a huge gap between Sunday and Saturday. Could this be a group chat related to work? Or is it someone close who happens to live in the same house?

You can see that it is possible to gather connections and create assumptions about certain topics without even looking at the data itself. Now let’s take a deeper look.


**Days-Heatmap Chat A**

![](whatsapp-analyze/heatmapA.png)


How interesting. We can see that the group is most active between the end of January till May and spikes again in October. If you happen to live in Austria, you probably know what that means. See, in most areas, the Austrian summer break for students lasts from June till the beginning of September while Christmas lasts from December to January. There is also one small break during November. You can clearly see that this could be a chat between friends who happen to be students but don’t have the same classes together. They probably spend a lot of their free time together, which explains the lack of data during the breaks. No one texts another person while they're sitting next to them... right?

**Days-Heatmap Chat B**

![](whatsapp-analyze/heatmapB.png)

We can see that the amount of messages remains pretty stable. This could prove our theory of two people in the same household as true. Maybe the gap in August could be a planned vacation?

It would be pretty frighting if I told you all our assumptions were correct. Right? You may now probably recognize that metadata is a lot more valuable than you originally thought. But what conclusions can we draw from this newly gained awareness? 

Most people rely on the encryption of their messaging apps. If no one can read my data then I am safe, right? No. As we can see, an attacker does not need access to your communication in order to gather valuable information.

If you want to look more into this topic, I'd recommend watching [Daniel Kriesel's 33c3 presentation](https://www.youtube.com/watch?v=-YpwsdRKt8Q).

