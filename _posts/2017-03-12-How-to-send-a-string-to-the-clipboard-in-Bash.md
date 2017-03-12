---
layout: post
title: How to send a string to the clipboard in Bash
---

```
##The **PRIMARY** selection
echo string | xclip

##The **CLIPBOARD** selection
echo string | xclip -sel clip
```
