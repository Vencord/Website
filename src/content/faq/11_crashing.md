---
title: Why does my Discord always crash when opening DevTools?
tags: crashing, crashes, oom
---

Discord on Windows uses 32bit electron which has a hard memory limit of 2gb. Discord's memory management is inefficient, so it will easily reach upwards of ~1.5gb ram if you are in a lot of servers and leave it open for a while

DevTools uses a lot of memory, and can make Discord quickly hit the 2gb ram usage, which crashes the client

**Solution**: use **Discord Browser** / **[Vencord Desktop](https://github.com/Vencord/Desktop)** 