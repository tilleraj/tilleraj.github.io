---
layout: post
title: Why 1440p is the Best Desktop Resolution
sitemap: false
---

When shopping for new technology, especially computer monitors, it can be easy to get overwhelmed by all of the numbers being thrown around.
That's why I'm going to make an over-generalized statement to help you decide:  
Whatever your use case, the **correct** choice is a 27" 2560x1440 monitor.

# Why is 27" 1440p monitor best monitor?
## Use Case: Office
[OSHA says](https://www.osha.gov/SLTC/etools/computerworkstations/components_monitors.html) to sit "20 to 40 inches" away from your monitor. 
[The Mayo Clinic says](https://www.mayoclinic.org/healthy-lifestyle/adult-health/in-depth/office-ergonomics/art-20046169) "about an arm's length away".
This comes out to 28" on average according to [some industrial design firm](http://macoshdesign.com/en/theory/articles/anthropometrical)(they're the only source I could find, okay?)
Let's call it 30.

"Retina display is about 300 PPI for a device held 10 to 12 inches from the eye" - Steve Jobs

2*10*300*tan(0.5deg) = 52.4 px/°
2*30*100*tan(0.5deg) = 52.4 px/°

So straight from the Apple's mouth, we're looking to hit ~100px/in for desktop monitors.

## What does this magical 52.4 px/° look like?
What are you trying to accomplish?

### I want to try to see the pixels
Do you have a 13" or 15" Macbook made in the past eight years?  
Sit with your eyes 13.25" away from it

13" Windows laptop?  
17.75"

15" Windows Laptop?  
20.5"

### I want to see how small my text is
Do you have a 13" or 15" Macbook made in the past eight years?  
Sit with your eyes 26.5" away from it.

13" Windows laptop?  
Same distance (assuming the reccomended 150% scaling)

15" Windows Laptop?  
An inch closer with scaling at 125%

## Could you provide reference to some more... historical monitors?
uhh... sure. Here's some more sizes of 1080 and 1440 too.

|Name |Wide (px)|Tall (px)|Ratio|Size (in)|PPI    | 
|:---:|:-------:|:-------:|:---:|:-------:|:-----:|
|XGA  |1024     |768      |4:3  |15       |85.33  |
|SXGA |1280     |1024     |5:4  |17       |96.42  |
|SXGA |1280     |1024     |5:4  |19       |86.27  |
|WXGA |1366     |768      |16:9 |19       |82.48  |
|HD+  |1600     |900      |16:9 |20       |91.79  |
|FHD  |1920     |1080     |16:9 |20       |110.15 |
|FHD  |1920     |1080     |16:9 |22       |100.13 |
|FHD  |1920     |1080     |16:9 |24       |91.79  |
|FHD  |1920     |1080     |16:9 |27       |81.59  |
|WQHD |2560     |1440     |16:9 |25       |117.49 |
|WQHD |2560     |1440     |16:9 |27       |108.79 |
|WQHD |2560     |1440     |16:9 |29       |101.28 |

## So, what display do you daily drive?
Oh, thanks for asking!  
It's a Dell U2515H, 25" @ 1440p, so 117.5 PPI  
This puts it in the ballpark of the ~113 PPI found in 2012 and later Macbook Pros (13" or 15") with their 200% scaling, or a 13" 1920x1080 Windows laptop with 150% scaling.
We typically sit closer to laptops than desktop monitors though, (like ~10" closer). The minimum ideal viewing distance for Steve Jobs' eye balls and my screen would be ~25.5".
I sit 28" away so I get 57.4px/°. This is "smaller" than most people would like or are used to. Going up to a 27" display takes care of that.

## Why a 27" and not a 29"?
If you had a 29" 1440p display, sitting any closer than 29 3/4" would dip you below the mythical 52.4 px/°.
If you 'downgrade' to a 27" though, you can sit 2" closer at 27.75". Hey, that's almost exactly our average "arm's length" from before!

"But I have bad eyes and things are always too small for me on my screen"
Fine, YOU can get the 29" display.

# But what about 4k?
Just don't do it, kids

## Scaling is bad, mmkay?
[Why is Windows Display Scaling So Bad? - Tech Quickie](https://youtu.be/NF210WeR9C8)  
Here's an explanation of "bitmap scaling" [Resizing Images - Computerphile](https://youtu.be/AqscP7rc8_M)
- It can make things blurry for no reason
- You're throwing money out the window by not running your monitor at native resolution

## Okay, what are our options?

|Name               |Wide (px)  |Tall (px)  |Ratio  |Size (in)  |PPI        |Comment                                                      |
|-------------------|-----------|-----------|-------|-----------|-----------|-------------------------------------------------------------|
|UHD                |3840       |2160       |16:9   |27         |163.18     |WAY too dense                                                |
|UHD 200% scaling   |1920       |1080       |16:9   |27         |81.59      |WAY too sparse                                               |
|UHD 150% scaling   |2560       |1440       |16:9   |27         |108.79     |Literally just my reccomendation                             |
|UHD                |3840       |2160       |16:9   |32         |137.68     |WAY too dense                                                |
|UHD 150% scaling   |2560       |1440       |16:9   |32         |91.79      |Usable but scaled                                            |
|UHD 125% scaling   |3072       |1728       |16:9   |32         |110.15     |Usable but scaled                                            |
|UHD                |3840       |2160       |16:9   |43         |102.46     |Just right but do you seriously have 38" of desk to spare?   |

## I don't care about scaling, I'm a #gamer and want to do #gaming at 4k!
See my [post about why 4k gaming is silly](#), but the tl;dr is that in order to get just 30fps at 4k, your rig will have to be capable of 1080p/120fps.
With those same resources you could game on Super Ultra Wide 1080 at 60fps.
For what it would take to play 4k/60, you could instead be playing Ultra Wide 1440 at 100fps (or 3x1080/75+ if that's your thing)

The point is, you'll either have to deal with scaling and running your games at lower resolutions, or if you somehow have a machine capable of playing games at 4k, there are so many better ways of utilizing it.

[mm]: https://guides.github.com/features/mastering-markdown/
[ksyn]: https://kramdown.gettalong.org/syntax.html
[ksyntab]:https://kramdown.gettalong.org/syntax.html#tables
[ksynmath]: https://kramdown.gettalong.org/syntax.html#math-blocks
[katex]: https://khan.github.io/KaTeX/
[rtable]: https://dbushell.com/2016/03/04/css-only-responsive-tables/
