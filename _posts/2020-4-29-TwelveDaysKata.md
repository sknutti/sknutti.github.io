---
layout: post
title: Twelve Days Kata
published: true
---

Today I did the Twelve Days Kata(Java) which involved implementing several functions that would return a single verse given the number, a set of verses given a range, or do the whole song.

My first approach was to try a for loop counting down to get the list of items per day.  That was quickly shown to not be effective.  After some thought, I went with a switch statement without breaks.  That way when the number given was higher than one, it would do all of the items from the given day to day 1, appending into a StringBuffer.  I also added a function that would convert the number to a string representing the day (e.g. 8 -> eighth).

Once I had that and fixed several issues like adding an "and" to the end of two Turtle Doves and not adding the second line break to the last verse to be displayed, I had all of the tests passing!

It took me about 20 minutes to write the code and find and fix the bugs I had.  I'm hoping to improve that time as I go through more katas.