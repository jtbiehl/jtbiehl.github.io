---
title: "Understanding Screen Contents for Building a High Performance, Real Time Screen Sharing System"
collection: publications
excerpt: 'Presents new techniques for capturing, transmitting, and storing screen content in collaboration systems.'
permalink: /publication/2012-10-29-understanding-screen-contents
date: 2012-10-29
venue: "ACM International Conference on Multimedia (MM)"
citation: "Chandra, S., Biehl, J.T., Boreczky, J., Carter, S., & Rowe, L.A. 2012. &quot;Understanding Screen Contents for Building a High Performance, Real Time Screen Sharing System.&quot; <i>In Proceedings of the 20th ACM International Conference on Multimedia (MM '12)</i>. ACM, New York, NY, USA, pp. 389-398."

---
Faithful sharing of screen contents is an important collaboration feature. Prior systems were designed to operate over constrained networks. They performed poorly even without such bottlenecks. To build a high performance screen sharing system, we empirically analyzed screen contents for a variety of scenarios. We showed that screen updates were sporadic with long periods of inactivity. When active, screens were updated at far higher rates than was supported by earlier systems. The mismatch was pronounced for interactive scenarios. Even during active screen updates, the number of updated pixels were frequently small. We showed that crucial information can be lost if individual updates were merged. When the available system resources could not support high capture rates, we showed ways in which updates can be effectively collapsed. We showed that Zlib lossless compression performed poorly for screen updates. By analyzing the screen pixels, we developed a practical transformation that significantly improved compression rates. Our system captured 240 updates per second while only using 4.6 Mbps for interactive scenarios. Still, while playing movies in fullscreen mode, our approach could not achieve higher capture rates than prior systems; the CPU remains the bottleneck. A system that incorporates our findings is deployed within the lab.

DOI: [10.1145/2393347.2393404](https://doi.org/10.1145/2393347.2393404)
