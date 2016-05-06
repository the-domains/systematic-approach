---
author: []
datePublished: '2016-05-06T09:50:23.217Z'
title: 'TOOLKIT: VMAX Commands'
description: ''
sourcePath: _posts/2016-05-06-toolkit-vmax-commands.md
dateModified: '2016-05-06T09:50:08.900Z'
starred: false
inFeed: true
hasPage: false
inNav: false
_type: MediaObject

---
# TOOLKIT: VMAX Commands
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/9da1ed56-57cd-4156-a629-a1f1249b2255.jpg)

\#List Masking View  
**symaccess -sid 1234 list -type port -v | grep H\_HostName**

\#Show Masking View  
**symaccess -sid 1234 show view MV\_MaskingView**

\#Replace Host WWN  
**symaccess -sid 1234 -wwn 1000000000000001 replace -new\_wwn 10000000000000002**

\#Check WWN is logged into array  
**symaccess -sid 1234 list logins -wwn 1000000000000001 -v**