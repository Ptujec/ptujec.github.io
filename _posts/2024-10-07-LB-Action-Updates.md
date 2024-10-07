---
title: "LaunchBar Action Updates: Todoist Inbox 3.0 & SF Symbols"
date: 2024-10-07 19:39:32 -0200
last_modified_at: 2024-10-07T19:39:32.592Z
---

## [Todoist Inbox 3.0](https://github.com/Ptujec/LaunchBar/tree/master/Todoist-Inbox)

I have a love/hate relationship with [Todoist](https://todoist.com/). After years of use, it still bugs me that it does not quite feel at home on macOS. For example, there is hardly any of the functionality exposed in the menu bar, plus the usual limitations of an Electron app.

Other than that, it's mostly love, though. The natural language input is second to none. Doist keeps innovating and adding features without cluttering the UI or experience. The app is easy to navigate and use with keyboard shortcuts, which are different from a typical macOS app. But they are there. 
Todoist also has a very good API, which allows me to use my favorite tool as an input method.  

Recently, Todoist gained time-blocking features. I'm exploring them right now. I thought it would be nice to be able to add durations with my LB Action as well. I've also wanted to support multiple labels for a while, so this update has both. 

And there is more. I often add links to MS Teams to my tasks so I can find information quickly. I thought about how I could simplify this. Now I can pull in the current clipboard entry by starting my entry with a comma ",". Teams links are automatically converted to direct links in Markdown format, and the cursor moves to the correct position for me to type away. That's a big win for me.

I also did some [fixing and cleanup](https://github.com/Ptujec/LaunchBar/commit/163dfe5bdb95a26f594bf27f00ca496f620833b6). For example, clicking on a notification really opens the task now. You can also open the task if you hold down cmd at the last step … that is, if you confirm the project or project section for the task. 

**All that said, you can still use the action plain and simple to get something into your inbox without any of the fancy stuff.**

## [SF Symbols](https://github.com/Ptujec/LaunchBar/tree/master/SF-Symbols-Browser)

I updated the SF Symbols Browser Action to support version 6.0. 