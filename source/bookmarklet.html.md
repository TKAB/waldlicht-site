---
title: Welcome to Middleman
toc:
  - name: Desktop
    anchor: desktop
  - name: Mobile
    anchor: mobile
    # sub:
    #   - name: Sub 1
    #     anchor: sub1
    #   - name: Sub 2
    #     anchor: mobile
last_change: 2019-11-02
---

# Bookmarklet

For quick and easy logging while browsing web pages add the unconfuse
bookmarklet to your browser favorites. It allows you to log any page or
document that you are looking at.


## Desktop

This is a single step activity.

1. Drag the following link to your browser's bookmark bar:
Link: Log!
2. Done

From now on whenever you are on an interesting page, press the bookmark to log the page.


## Mobile

This is a multi-step activity. Please contact us if you're stuck.

1. Create a bookmark by bookmarking this page
2. Copy the red string below
3. Edit the bookmark that you created
4. Paste the copied string into the address field and change the name to Log!
5. Done.

<p class="text-danger">
javascript:o=location.href;t=document.title;if(document.getSelection)%7Bs=document.getSelection();%7Delse%7Bd="";%7D;void(open("https://app.unconfuse.me/bookmarklet_add?url="+encodeURIComponent(o)+"&description="+encodeURIComponent(s)+"&title="+encodeURIComponent(t),"unconfuse%20add","toolbar=no,scrollbars=yes,width=750,height=700"));
</p>

