AWStream: Adaptive Wide-Area Streaming Analytics
---

[![Build Status][travis-badge]][travis]

- [talk.pdf](https://awstream.github.io/talk/talk.pdf)
- [talk.pptx](https://awstream.github.io/talk/talk.pptx)


## Abstract

The emerging class of wide-area streaming analytics faces the challenge of
scarce and variable WAN bandwidth. Nonadaptive applications built with TCP or
UDP suffer from increased latency or degraded accuracy. State-of-the-art
approaches that adapt to network changes require developer writing sub-optimal
manual policies or are limited to applicationspecific optimizations.

We present AWStream, a stream processing system that simultaneously achieves low
latency and high accuracy in the wide area, requiring minimal developer
efforts. To realize this, AWStream uses three ideas: (i) it integrates
application adaptation as a first-class programming abstraction in the stream
processing model; (ii) with a combination of offline and online profiling, it
automatically learns an accurate profile that models accuracy and bandwidth
trade-off; and (iii) at runtime, it carefully adjusts the application data rate
to match the available bandwidth while maximizing the achievable accuracy.  We
evaluate AWStream with three real-world applications: augmented reality,
pedestrian detection, and monitoring log analysis. Our experiments show that
AWStream achieves subsecond latency with only nominal accuracy drop (2-6%).

## Credit

[**Metropolis**](https://github.com/matze/mtheme) is a simple, modern Beamer
theme suitable for anyone to use. It tries to minimize noise and maximize space
for content; the only visual flourish it offers is an (optional) progress bar
added to each slide.

<!-- link -->
[travis-badge]: https://travis-ci.com/awstream/talk.svg?branch=master
[travis]: https://travis-ci.com/awstream/talk
