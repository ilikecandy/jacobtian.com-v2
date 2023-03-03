---
title: "I cut a perfectly working WiFi card. Here's why."
comments: true
header: 
  teaser: /assets/images/post/2022-01-18-stereoscopic-image-viewing/teaser.jpg
  overlay_image: /assets/images/post/2022-01-18-stereoscopic-image-viewing/teaser.jpg
last_modified_at: 2023-04-31
categories:
  - Blog
tags:
  - Fun
  - Software
---

# 

# The Problem

My brother's laptop's wifi suddenly stopped working recently. The first thing I thought was that it was a software issue causing it to malfunction. We messed around around the built in Windows Device Manager, and I saw the wifi card had a "Code 10" error, stating that "This device cannot start." From my previous experiences, this is a very generic error, and doesn't usually help in determining the issue. 

Since the wifi card was still being detected by the system, the chances of this being a physical connection problem were slim. I still opened up the laptop to check it out anyway.

Thankfully, the network card was right at the surface and I didn't need to remove any more components other than the back cover.

![](C:\Users\ilike\Desktop\91c1f3fd-3074-4646-8043-e5bc6354a771.a477141853500d4ed0abc7a6e73005c9.jpeg)

This is the chip, and seeing the two wires connecting to it, replacing the two wires seemed like the right thing to do, however I realized the "MAIN" wire couldn't snap back on the chip (circled in red in the photo). After closer inspection, the connector on the chip itself fell off entirely. I'm still not sure if it fell off (seems unlikely), or I broke it trying to unplug it.

This chip (Intel AX201) utilizes an M.2 slot, and this is common for laptop wifi cards, so I decided to try to swap it out for a wifi card from an older laptop. They're usually held on to the laptop's frame by a phillips screw (pointed on image). 

The screw was held on abnormally tight. Even with a screwdriver that fit perfectly, I ended up stripping the screw.

# Getting out the stripped screw

Stripping the screw (basically turning the screwhead circular) created a whole new problem, and I spent the majority of the time fixing the laptop on this one screw.

I attempted to get it out, through chipping away a line across the head, so I could use a flathead screwdriver on it. To no avail, I then tried to sand the whole screw off, which was incredibly time consuming (and felt really stupid).

[insert picture of screw here]

At this point, the card was covered in metal screw dust, and not having the tools to fix the broken connector made it quite worthless. Replacement wifi cards were only about $20, and at this point it was just worth it to cut through the card, even if it was still functioning.

# Replacing the WiFi Card

Cutting the card was simple. I took a pair of side cutters and cut around the screw. This made it easy to remove the card from the slot, and I could unscrew the screw by piniching the sides

This was the result: 

[insert image of broken card here]

I had a broken laptop from a little bit ago which I transplanted the wifi card from, but device manager couldn't find the card at all, even after connecting to the internet with an ethernet cable to install drivers. I suddenly remembered that my laptop had the same (Intel AX201) wifi card, and that's what ended up working! Weirdly enough, I put the same wifi card from the old computer into mine, and it worked fine, once the drivers for it were installed. 

# Conclusion

* Be careful when unscrewing screws

* There are better ways to remove stripped screws other than cutting the screw or sanding it

* Sufficiently attempt software fixes before digging into components

And that's why, I cut a perfectly working WiFi card.