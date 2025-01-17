---
title: "MAJOR Nextcloud Release, Pop!_OS Rust, and more!"
date: "2022-10-04"
categories: 
  - "news"
tags: 
  - "newsletter"
coverImage: "newsletter1-2.jpg"
---

Welcome to the first newsletter! This is a roundup of the big stories that we’ve seen this week. This newsletter will grow and develop to serve the tech community as a whole. We are always open to suggestions. With that let’s get into some things that happened this week.

## **Fedora Dropping GPU Support for Popular Video Codecs**

Something that had the Linux community in a buzz this last week was the decision from Fedora that they’re going to be dropping support for H.264. The initial reaction was met with correction as this will only affect Video Acceleration API support for H.264, H.265, and VC-1 codecs. This is due to legal worry as there could be push back from patent holders. This will primarily affect AMD GPU users and any user who uses open-source graphics drivers, preventing them from using GPU acceleration to play video content that requires these codecs.

[https://news.itsfoss.com/fedora-drops-vaapi-codec](https://news.itsfoss.com/fedora-drops-vaapi-codec)

## Nextcloud Hub 3 is HERE!

This is one of the largest releases in the history of Nextcloud. Starting with the photos application there is now AI powered face and object recognition, a built in photo editor and more.

![](images/photo-editor.jpg)

Nextcloud talk is shipping with new features such as polls and better chat permissions. Mail 2.0 ships an improved user interface with easily accessible quick actions, mail content preview in the sidebar, a streamlined account setup wizard and integrated support for replying to calendar invitations. The viewer integration enables users to view attachments without having to save the file or leaving the Mail app. This is just the surface of everything that is new. With every release Nextcloud seems to get closer and closer to being the best option for many business that care about security and privacy.

## **Pop!\_OS is skipping 22.10, but that Rust Toolkit though!**

Instead of focusing on a short term release the developers at System76 want to take the time and effort in constructing their home-grown, Rust-based COSMIC desktop environment. Better yet, we got a preview of what this could look like visually.

![](images/rust-popos.webp)

Pop!\_OS COSMIC desktop is going to use Iced Rust Toolkit rather than GTK that is used in GNOME. A [developer on Reddit](https://www.reddit.com/r/pop_os/comments/xs87ed/comment/iqjc35b/?utm_source=reddit) stated the following.

> You are quick at noticing. Jeremy just started working on this yesterday. This is a design demo application that will showcase all of the widgets and theming capabilities available in the COSMIC design system. This will also be the COSMIC library that we'll be using to develop COSMIC applications from. The UX team has been carefully designing widgets and applications over the last year. We are now at the point where it is critical for the engineering team to decide upon a GUI toolkit for COSMIC. After much deliberation and experimentation over the last year, the engineering team has decided to use Iced instead of GTK. Iced is a native Rust GUI toolkit that's made enough progress lately to become viable for use in COSMIC. Various COSMIC applets have already been written in both GTK and Iced for comparison. The latest development versions of Iced have an API that's very flexible, expressive, and intuitive compared to GTK. It feels very natural in Rust, and anyone familiar with Elm will appreciate its design. COSMIC Settings will be developed in tandem with, and from, this toolkit.

https://www.omgubuntu.co.uk/2022/09/excited-for-pop\_os-22-10-dont-be

## Featured Video: **Khadas Edge2 Pro Review**

This is the most powerful SBC I have ever used. To the point that I think it could replace the desktop computer for many people. It is great for web browsing, media playback, and light gaming. Additionally, the specs make it a great option for a small home server.

<iframe title="i hope the Raspberry Pi 5 is this good - Khadas Edge2 Pro" src="https://www.youtube.com/embed/SUfRDDgwW8U?feature=oembed" width="200" height="113" frameborder="0" allowfullscreen="allowfullscreen"></iframe>

## Twitter Blue is starting to roll out an edit button

If you follow TechHut on Twitter you probably have seen quite a few examples of how an edit button on the platform would be beneficial to everyone. Unfortunately, it looks like this feature is going to be available only to paying customers, and for now those customers in Canada, Australia and New Zealand. This is followed up with a tease that the feature will be coming to the US soon. Like other social networks when you edit a post it will show a timestamp of when the Tweet was edited with version history so we can see what was changed.

<blockquote class="twitter-tweet"><p dir="ltr" lang="en">hello</p><p>this is a test to make sure the edit button works, we’ll let you know how it goes</p><p>— Twitter Blue (@TwitterBlue) <a href="https://twitter.com/TwitterBlue/status/1575590534529556480?ref_src=twsrc%5Etfw">September 29, 2022</a></p></blockquote>

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## GitHub Repository of the Week!

Motionity is a free and open source animation editor in the web. It's a mix of After Effects and Canva, with powerful features like keyframing, masking, filters, and more, and integrations to browse for assets to easily drag and drop into your video.

![](images/preview.gif)

[https://github.com/alyssaxuu/motionity](https://github.com/alyssaxuu/motionity)

Thank you for reading. Tell your friends!
