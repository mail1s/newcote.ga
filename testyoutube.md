﻿---
layout: post
title: testvideo
permalink: /test/youtube/
---

<script>
const player = new Plyr('video', {captions: {active: true}});
window.player = player;
</script>
<div class="plyr__video-embed" id="player">
  <iframe
    src="https://www.youtube.com/embed/ecV00RVV9sM?origin=https://plyr.io&amp;iv_load_policy=3&amp;modestbranding=1&amp;playsinline=1&amp;showinfo=0&amp;rel=0&amp;enablejsapi=1"
    allowfullscreen
    allowtransparency
    allow="autoplay"
  ></iframe>
</div>