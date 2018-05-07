---
layout: post
title: GSoC Progress - Community Bonding Period
---
Its almost two weeks since the start of Community Bonding period for GSoC.

### Uploaded files internal links 
We had a major bug in the latest release, [#469](https://github.com/zulip/zulip-electron/issues/469), which though was fixed didn't work for new users or after adding/removing a server (`realm`) to the client, also support for downloading files other than pdf, mp3, mp4 etc like txt, js etc were not present with the solution implemented in the released version.  I pushed [#483](https://github.com/zulip/zulip-electron/pull/483), which was merged after which this issue is hopefully finally resolved once and for all after many different types of fixes. Now any uploaded file (other than images, gifs etc) would be prompted to download to the users desktop.


### System proxy settings
I have created a PR, [#480](https://github.com/zulip/zulip-electron/pull/480) which fixes a high priority feature [#296](https://github.com/zulip/zulip-electron/issues/296) of using system proxy settings along with manual proxy settings. I hope to get this feature merged this week.

### Loading indicator

Issue [#482](https://github.com/zulip/zulip-electron/pull/486) was a tricky frontend bug, which required quite some time of testing and trying different approaches with finally one working as a PR [#486](https://github.com/zulip/zulip-electron/pull/486). This being a tricky bug, after some rigourous testing hope to get it merged as well this week.


### Checkins
I have started a checkin on the developer community channel on the thread #checkin. Hope to make this more frequent as the period progresses.

Other than this also merged [#478](https://github.com/zulip/zulip-electron/pull/478) and working on a beta release with an electron update in it. <br>
From this week I hope to get more work done from my proposal deliverables and hope to a have a productive time working before I hibernate for end semester exam preparations.

See ya!