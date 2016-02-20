---
layout: post
title:  "25 Minutes of Rock 2"
date:   2015-12-31
author: tricorius
description: "25 minutes of rock 2"
series: 25m-of-rock
categories: article
tags:
- itunes
- music
- timeboxing
---

# 25m of Rock - Part 2

* **Primary Narrative Arc:** duplicating a version of my time-boxing with an iTunes “Rock” playlist which is limited to a 25-minute “pomodoro” time-box.
* **Primary Image:** screenshot of iTunes with “25m of Rock” playlist selected
* **Progress:** /Users/curtis/Library/Mobile Documents/comappleCloudDocs/Documents/KOC - Evolution of an Article

Introductory Paragraph

You might recall from earlier articles that as an individual managing ACDDDHO (my OCD inspired acronym rearrangement for the *fun* combination of ADHD/OCD) I strive to  proactively protect against distraction. One way that I do this (with the proper OCD underpinnings) is by utilizing a variation of [The Pomodoro Technique](http://pomodorotechnique.com/get-started/).

When i first started with the Pomodoro Technique, I performed it much more stringently. While I learned my personal patterns, the ticking of the timer was *very* helpful. 

I have always listened to music while performing creative work. It’s just a core preference. After collecting enough information to find my productivity baseline, I also realized that I had a fairly good innate sense of when that timer was going to ding.

At this point, I decided to drop the timer. But while listening to music, sometimes I would find the bottom dropped out and I’d been focusing for too long without a break.

*It sounds like you achieved Flow…why is this a problem?* A common misconception is that time-boxing breaks Flow. If you have a buzzer going off every 30 minutes you are going to be pulled out of your concentration focus.

I have found the exact opposite. Time-boxing has **integrated** into my flow.

As a general rule, when coding, it’s beneficial to follow small, iterative patterns. If you’re implementing a new feature, you might drop some pseudocode inline to experiment with your basic implementation theory. Of course, you then need *working* code, so modifying it to actual code without focusing **too** much on details is a great next iteration. After some confirmation that your code is passing test cases and actually accomplishing your goals, you may extract it into a more cleanly-structured format. Finally you might want to ponder (and document your experience for “future you”).

Observing the above sequence of events, you can probably see the time-boxes inherent in the entire process. For me, it’s good to have defined, structured breaks where I can naturally flow between the phases of implementation.

Time-boxed playlists are **perfect** for this.

## Intro the Playlist (with screenshot)

In the screenshot below, we see the iTunes edit dialog for the “25m of Rock” playlist. These settings provide an intelligent selection of music whenever the playlist is updated.

\<screenshot: playlist editor for 25m-of-rock playlist\>

## Explain the Rules

**Loved is true**

As previously mentioned, I enjoy the “loved” functionality of Apple Music. And as an Apple Music subscriber I take full advantage of this in my smart playlists.

However, if you prefer a scalar rating system (such as the “five stars” system), it’s perfectly acceptable to modify the playlist accordingly.

**Playlist is Rock**

Here we build upon a playlist designed in a [previous article](http://knightsoftheoldcode.com/article/2015/12/17/25minutes-of-rock/#playlists). In this case, it takes advantage of my “Rock” smart  playlist. (Obviously, I’ve duplicated and slightly altered a series of playlists to coincide with the musical genres I enjoy.)

**Last Played not in the last 3 days**

In order to help randomize the list, and also so I don’t get sick of hearing the same song repeated, we build in some filtering based on “last played”.

**Last Skipped not in the last 7 days**

In case I’m not in the mood for a particular song, even though I’ve “loved” it in the past, I maintain a filter for “last skipped”.
  
I also use this in other playlists during music library maintenance tasks. (Which we will cover in future articles. As a preview, I like to periodically go through and remove music that has a high skip count…apparently I don’t always continue to love things as much as I initially did.)

(Note that this functionality seems a bit buggy, or my concept of “skipped” doesn’t exactly line up with Apple’s concept of “skipped”. More on this after I research it.)

**Limit to 25 minutes selected by random**

Here’s the time-boxing rule. This is what enables a hard-limit when randomizing the playlist. I’m quite pleased with the algorithm that generates the playlist. It’s consistently within a minute of the bounds selected.

**Match only checked items**

Unchecking an item is a quick way to “fix” a song (I’m looking at you, U2) that keeps showing up and irritating you when trying to maintain Flow.

The maintenance playlists include filters to help find these items as well. I can then make an educated decision whether to keep songs in my collection. 

**Live updating (why is it off?)**

Live-updating, unfortunately, keeps the playlist endlessly updating. With live-updating enabled the playlist periodically refreshes itself. This occurs, at the very least, after every song is played. The side effect causing the playlist to always be filled with 25 minutes of music.

As you can imagine, this condition causes slight issues with our time boxing goals. Instead, we need to disable this feature so that it will play a time-boxed listing of music, then stop playing (your queue to take a break).

The downside is that after the music stops, you have to manually refresh the playlist if you want it to select a new set of random songs (and get rid of the previous set).

This isn't exactly *hard* by any means, and I found myself quickly adjusting to the ritual of pausing my work, taking a quick mental break, refreshing the playlist, and resuming work. It *would* be nice, however, if there were a setting that would play through the time limit set, pause the music, and automatically refresh the playlist (so that you could simply trigger play again with a fresh set of music).

## If Wishes were Fishes

I'd love a playback feature that would set it up to play through the playlist, pause the music automatically upon completion, and refresh the list to prepare it with a new 25 minute block of songs. I could then just trigger "play" and quickly block through my day.

## Conclusion

Summary of what we accomplished and a preview of the next article…