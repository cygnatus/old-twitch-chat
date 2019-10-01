Old Twitch Chat
===============

![Before-and-after comparison animation](https://github.com/cygnatus/old-twitch-chat/blob/master/diff.gif?raw=true)

Background
----------
On September 26, 2019, Twitch announced a [rebranding][].

I am not exactly a fan, but the worst thing about the update is how hard it makes it to read chat, which is kind of central to the whole Twitch experience.

This project restores the original (dark mode) style of Twitch chat before the redesign to make it readable again.

CSS
---
The original CSS isn’t that difficult as far as I can surmise:

```css
.chat-list, /** Live chat */
.video-chat__message-list-wrapper, /** VOD chat */
.clips-chat /** Clip chat */ {
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-size: 12px;
    line-height: 20px;
    font-weight: 400;
    color: #dad8de;
    background-color: #0f0e11;
}

.chat-input {
    background-color: #0f0e11;
}
```

Installation
------------
Otherwise, to use my userstyle, the easiest thing for you to do is to download the browser extension [Stylus][] and import my script, like so:

1. Install the [Stylus][] browser extension
2. Download `stylus.json` from this project to your computer using the below link
    - <https://raw.githubusercontent.com/cygnatus/old-twitch-chat/master/stylus.json>
3. Open Stylus
4. Click **Manage**
5. Hit **Import** on the bottom left, then **Import Styles**
6. Open `stylus.json`; this might overwrite existing Stylus settings

And that’s it; Stylus has a nice button for turning off a custom style so you can see what it looks with the settings on and off.

Thanks
------
Throw a follow on [Twitch][] or [Twitter][] or something.

You can also retweet [the announcement tweet][t].


[rebranding]: https://blog.twitch.tv/en/2019/09/26/nice-to-meet-you-again-for-the-first-time/
[stylus]: https://add0n.com/stylus.html
[twitch]: https://twitch.tv/cygnatus
[twitter]: https://twitter.com/cygnatus
[t]: https://twitter.com/cygnatus/status/1177300220503351296
