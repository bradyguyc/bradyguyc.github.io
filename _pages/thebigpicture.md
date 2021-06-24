---
title: The Big Picture
subtitle: Technology and Architecture
description: Use the Argon Jekyll theme to build a landing page, blog or complete website.
featured_image: /assets/img/dreamstimemaximum_136730926.jpg
---

--- 
## Key Components of the solution

Azure, Visual Studio, and Xamarin are the primary technologies utilized in the solution.  While not comprehensive these technologies are at the core with Xamarin Forms being the core of the solution for mobile development with it's single code multi device deployment a driving feature for it's selection.

{% include bigpicture.html %}


1. Visual Studio 2019 Preview Community Edition - is the IDE utilizing c#.
2. Xamarin Forms - is the framework for a multi mobile platform single code base.  I have attempted to utilize the core of Xamarin and not look to many add on's in particular commercial addon's.
3. GitHub - is the code repository and I am hosting this site/blog on github pages utilizing Jekyll.
4. Microsoft's App Center - for automated build pipelines.
5. LetsView - is a free windows app that allows you to screen mirror both iOS and Android devices which makes it a lot easier to compare the rendering of the app side by side and at a larger scale.  It also makes it easier to take snapshots of the app for documentation etc.
6. VNC Viewer - is a remote desktop viewer that I use to remote into my Mac so that I don't have to use a screen/keyboard switch to flip over to that environment.  I have also noticed that if I keep a VNC viewer session open the connection between Visual Studio and my mac is more stable.
7. Microsoft App Center - integrated sdk's into the mobile app allow for crash reporting 
8. Microsoft App Center Analytics - integrated sdk's into the mobile app allow for event monitoring and tracking.
9. Microsoft App Center Push - integrated sdk's for sending notifications to mobile devices.
10. Azure B2C Active Directory - for user authentication.
11. Azure functions - for backend processing.
12.  Azure CosmosDB is the primary data store that is synced with the mobile device.
13. DBPedia - a knowledge graph of all things wikkapedia.  This is some really cool stuff and is utilized to find book series and books in a series.
14. Google Books API for retrieving a massive set of details on a particular book.

<!--stackedit_data:
eyJoaXN0b3J5IjpbOTMzNzgyMDI5LDIxMjIyMjIwNDMsLTEwNT
M1NjQ0NDIsLTE4NTgxMDgwNDIsLTExOTkzMzI0MzVdfQ==
-->