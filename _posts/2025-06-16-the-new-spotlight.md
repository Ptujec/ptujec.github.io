---
title: "The New Spotlight"
date: 2025-06-16 15:30 +0200
---

If you're reading this, it should be no surprise that the [Spotlight announcement](https://www.apple.com/si/newsroom/2025/06/macos-tahoe-26-makes-the-mac-more-capable-productive-and-intelligent-than-ever/) at WWDC 2025 caught my attention. I'm a launcher nerd.

I think what Apple did is great. Well, at this point it *looks* great. I need to try it to actually judge it. But it looks promising.

Obviously, people following along with the announcement were talking about apps being sherlocked by this. I get it. But it feels a bit silly to me by now.

[LaunchBar](https://www.perplexity.ai/search/what-was-the-first-launcher-ap-rqhBERPsRC.YKSVPommVCA), my launcher of choice, has not been replaced by the initial launch of Spotlight, nor by Quicksilver or Alfred or anything that followed. I know firsthand that it won't go anywhere. This is because it is a labor of love. It does not need to justify a ton of VC funding. It does not need my private data. It has a very solid core, is extensible, and has never lost its focus. So I am not worried about LaunchBar one bit.

What caught my attention most is the App Intent integration. Spotlight now is another app besides Shortcuts that is able to do stuff with them. 

<video width="100%" controls autoplay muted playsinline>
  <source src="https://www.apple.com/newsroom/videos/2025/autoplay/06/macos-tahoe-26-makes-the-mac-more-capable-productive-and-intelligent-than-ever/apple-wwdc25-macos-tahoe-26-spotlight-actions-send-email/large_2x.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

(Source: [Apple](https://www.apple.com/newsroom/2025/06/macos-tahoe-26-makes-the-mac-more-capable-productive-and-intelligent-than-ever/))

Is there a chance that Apple opens that [private API](https://mastodon.social/@jgarnham/114508467792973758) at some point?

This is what [I really want](https://hessen.social/@ptujec/114612574020290426). I don't want to be limited to the Shortcuts interface to use App Intents. I want direct access to them. I want to integrate them into LaunchBar actions.

Why App Intents? For one, it is what Apple has been pushing in recent years. As of now, there is usually an alternative way to interact with apps (URL schemes, CLI, AppleScript, reading plists, databases, etc.). This is true even for the example shown in the video above. But I have already come across instances where the only access is through an App Intent. For example, in my [action to display recent chats/messages](https://github.com/Ptujec/LaunchBar/tree/master/Recent-Messages), I can open those in the Messages app with a URL scheme—except for named group chats. No API, no AppleScript … There is an "Open Conversation" App Intent, though; it is in Shortcuts. It is kind of stupid, though, to have to create a shortcut and call that via the shortcut CLI just to open a group conversation. Using it directly would be so much more convenient.

BTW, the last bit of this year's live version of [The Talk Show](https://youtu.be/vqwPUHTFEkg?si=mkFtnEBEyZJq55D7&t=7074) is about the Spotlight announcement. It's worth a listen.