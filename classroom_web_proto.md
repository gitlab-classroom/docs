classroom web proto
===
> v0.1 by [Zhongyi Tong](https://github.com/geeeeeeeeek).
> 
> Note that the *View* below links to a static version and may not be up to date. Log into the [proto](https://zhongyi.proto.io) to catch up.

Overview
---

The app use Google's Material Design, restricted to the [official guideline](https://www.google.com/design/spec/material-design/). All components in my sketch can be interpreted into React components from http://material-ui.com/. If the sketch has any inconsistency with the official guideline including margins, colours or else, must stick to the latter one.

Screens
---
###login([view](https://zhongyi.proto.io/share/?id=5b7970e2-0063-4b11-a5c8-207f9fa77947&v=2))

SIGN UP --> goto the welcome page of gitlab

###classroom([view](https://zhongyi.proto.io/share/?id=5b7970e2-0063-4b11-a5c8-207f9fa77947&v=2))

Search box can be left in future implementation. 

###class([view](https://zhongyi.proto.io/share/?id=5b7970e2-0063-4b11-a5c8-207f9fa77947&v=2))

Currently our focus is on giving assignments and collecting them back. Thus the rest tabs are not planned yet.

The assignments are divided into three groups: UNASSIGNED, ON PROGRESS and FINISHED. The UNASSIGNED group and the float button is only visible to teachers. Students can see ON PROGRESS and FINISHED assignments. 

###assignment([view](https://zhongyi.proto.io/share/?id=5b7970e2-0063-4b11-a5c8-207f9fa77947&v=2))

What user sees is a combination of the git link card and the assignment detail card.

For students, only top two cards are visible. For teachers, it depends on the status of the assignment. If it has not been published, 'publish' and 'abort' buttons appear on the git repo card. If published and not collected, 'collect' appears. If already collected, there will be no more buttons. Also, the description of the card changes with each status.

###create assignment([view](https://zhongyi.proto.io/share/?id=5b7970e2-0063-4b11-a5c8-207f9fa77947&v=2))
Nothing special.
