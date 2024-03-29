---
title: Should it really be Telegram?
date: 2023-07-18 13:08:40
thumbnail: telegram.jpg
featured_image: telegram.jpg
tags:
---

In recent years, WhatsApp has become one of the most popular messaging apps worldwide, connecting billions of people across the globe. However, beneath its seemingly user-friendly interface, there are growing concerns about privacy, security, and the impact of its corporate parent, Facebook. As a result, many users are seeking alternatives to WhatsApp that prioritize their digital well-being. However, it seems like most people are switching to another messenger that I'm pretty unsure about.

### It's open source. Right?


Telegram states the following on their website:

{% blockquote Telegram https://telegram.org/apps%}
Telegram apps are open source and support reproducible builds. Anyone can independently verify that Telegram apps you download from App Store or Google Play were built using the exact same code that we publish.
{% endblockquote %}


While those two sentences are not wrong, they are dangerously misleading consumers. See, what they are stating here is that their **clients** are open source. Their server code however still remains **closed** and therefore we do not know what Telegram actually does with our data. 

### No encryption, no peace of mind

While Telegram offers end-to-end encryption in its "Secret Chats," this feature is [**not enabled by default**](https://www.howtogeek.com/709484/how-to-start-an-encrypted-secret-chat-in-telegram/) for regular chats. This means that the content of your conversations may not be fully secure unless you specifically **opt in** for Secret Chats. Telegram has also faced criticism regarding the lack of independent audits of its encryption protocols, unlike Signal, which has undergone extensive third-party security audits. Without such audits, it is rather hard to prove that their E2EE is powerfull enough.

### But what should we use instead

There are many other great privacy respecting messenging apps which i'd rather use than telegram. I've listed my favorite ones below:

[Signal](https://www.signal.org/de/): Known for its strong encryption, Signal offers end-to-end encryption by default for all conversations and has a focus on user privacy. Like I already said, it has undergone independent security audits and is widely regarded as one of the most secure messaging apps available.

[Threema](https://threema.ch/de): Probably the OG because it's the oldest one. Also requires no phone number to sign up (!!!)

[Element](https://element.io/) (Matrix): Element is an open-source, decentralized messaging platform that uses the [Matrix protocol](https://matrix.org/). 