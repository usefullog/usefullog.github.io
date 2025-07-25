---
layout: page
title: About
date: 2025-01-20
permalink: /about/
---

*Here are a bunch of logs.\
Some are useful.\
Some are useless.*

![suedbahnhof](/images/suedbahnhof.jpg)

# Motto
> "It is only by selection, by elimination, by emphasis that we get at the real meaning of things. -- Georgia O'Keeffe"


# Tech Logs

 - 2024-05-04 Adding photos took from the Chicago trip but Github would not let me push the commit. It took me a while to root cause the [problem](https://confluence.atlassian.com/stashkb/git-push-fails-fatal-the-remote-end-hung-up-unexpectedly-282988530.html). Turns out that I need to set the POST buffer size larger than 1MB. ```git config --global http.postBuffer 5000000```  
 - 2024-07-13 Adding Saguaro NP and Glacier NP.  
 - 2024-10-06 Add Camera post. 
 - 2024-10-17 Re-installed Fedora 40 with KDE Plasma. I was not able to get Gnome to show RAW file thumbnails. Some things to be done after installation -- 
 1. transfer all backup files
 2. install [RPMFusion](https://rpmfusion.org/Howto) codecs for multimedia
 3. setup GitHub for this site, need to remember ```git submodule update --init --recursive``` for the hugo theme
 4. firefox freezes sporadically and no solution - switching to chromium for now
 5. install nvidia driver, this might solve the firefox problem
 6. install vscode, darktable, blender
- 2024-12-18 Add Redwood NP post. The photos are taken by Sony A6700 and developed using Darktable
- 2024-12-19 Enable image on the preview
- 2025-01-20 Add Maui post
- 2025-04-12 Add Lisbon post
- 2025-05-03 Add Seaside post
- 2025-07-12 Add Learning post
- 2025-07-21 Add 5-step engineering process post