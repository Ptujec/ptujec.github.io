---
title: "The Unique Power of Browsing in LaunchBar"
date: 2025-02-03 14:47 +0100
---

I recently stumbled upon a cool little detail in the [LaunchBar developer documentation](https://developer.obdev.at/launchbar-developer-documentation/#/script-output) that I was not aware of before: `actionReturnsItems`. Here is the description:

> Specifies that selecting and executing the item (as specified by the action key) will return a new list of items. If this is set to true, the item will have a chevron on the right side, indicating that the user can navigate into it, and doing so causes the action to be executed.

I do a lot of chaining together functionality within my actions. It works without this property being enabled. But adding this is the icing on the cake for an action like the one I built for Zotero. **And it showcases one of the things that make LaunchBar unique.**

[My Zotero action](https://github.com/Ptujec/LaunchBar/tree/master/Zotero-Actions#launchbar-action-for-zotero) lets you search, browse, and act on items from your local Zotero database. Enabling `actionReturnsItems` does two things. It makes the browsing capabilities visually more obvious.

![Screenshot highlighting the chevrons in the Zotero Action](/assets/images/chevron.jpg)

And it lets you use arrow keys to do the browsing. (You can also use `space`, which behaves like the right arrow key).

The way browsing works in LaunchBar is one of the things that makes the app unique compared to other launchers. It is minimal and powerful at the same time.

**In the case of Zotero, it allows me to interact with the database in a way that is not possible in the native interface.** I can browse through tags, show library items with the selected tag, dive into the details of one of them, and explore related items. In this case, the other chapters of the book. And on and on …

![GIF of browsing the Zotero Library with LaunchBar](/assets/images/browse_zot.gif)

The possibilities are endless. And it is so simple. You can do it all just with arrow keys. Plus, you can always go back a step.  

I have checked out the Zotero extension of other launchers. They offer some great features, but they are mostly reproducing what you can do within the native interface. There is value in this … especially since the Zotero interface used to be a bit slow before [version 7](https://www.zotero.org/blog/zotero-7/). But LaunchBar's way of browsing opens up possibilities that add value beyond that.

It's thoughtful design like that that makes it stand out to me even after all those years and all the hype around its competitors.