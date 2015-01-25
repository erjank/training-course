---
date: 2014-03-06
round: Round 8
title: 'Screencast: Improving the behaviour of the up and down arrows in bash'
author: Jean-Christophe Leyder
permalink: /2014/03/screencast-improving-the-behaviour-of-the-up-and-down-arrows-in-bash/
enclosure:
  - |
    |
        /uploads/2014/03/screencast-bash-history.mp4
        5817745
        video/mp4
        
  - |
    |
        /uploads/2014/03/screencast-bash-history.m4v
        5817745
        video/mp4
        
tags:
  - Video
---
Below is the screencast I created about improving the behaviour of the up/down arrows when recalling commands from the history in the bash shell.

The first screencast I recorded lasted over 6 minutes, so I removed extraneous examples. The second version lasted about 4 minutes, with lots of hhhhmmmms. This screencast shown below is the third and final version, lasting 2:59.

I used QuickTime Player to record the screen, and didn&#8217;t edit the video at all (other than trimming the beginning and the end).

The two lines to add to the `$HOME/.inputrc` shown in the screencast are:  
`"e[A":history-search-backward<br />
"e[B":history-search-forward`

I hope you will find this tip useful!

<div style="width: 474px; height: 296px; " class="wp-video">
  <video class="wp-video-shortcode" id="video-6255-4" width="474" height="296" preload="metadata" controls="controls"><source type="video/mp4" src="/uploads/2014/03/screencast-bash-history.mp4?_=4" /><a href="/uploads/2014/03/screencast-bash-history.mp4">/uploads/2014/03/screencast-bash-history.mp4</a></video>
</div>

<p style="text-indent: 5em;">
  <p>
    <a href="/uploads/2014/03/screencast-bash-history.m4v">Direct link</a> to my screencast.
  </p>
