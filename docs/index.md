---
title: Buffy
description: "Your personal film selector for movie nights!"
layout: default
---

## Summary

_Buffy_ is a convenient motion picture title finder for audiences looking for viewing suggestions that match specific preferences, and for those who need help remembering the title of a film.

## Intended users

Write a bullet list here, including at least 2 different types of intended users. Make it reasonably specific; simply saying "Anyone who likes games" (for example) is not sufficiently specific.

For each type of intended user, include at least 1 _user story_. A user story is usually just 1 simple sentence (no more than 2 sentences), in the voice of the intended user, stating a specific task that the user needs to perform, and the benefit that will be obtained. The simplest user stories take the form 

> As a <type of intended user (_who_)> I want to <goal (_what_)> so that <benefit (_why_).

Please avoid writing too much for the user story. In particular, if the way the user story is written makes it difficult to see the _who_, _what_, and _why_, then you probably need to re-write it more directly. (On the other hand, a user story should not simply be a re-statement of the intended user description.)

Here is one (silly) example of an intended user, along with a user story. Please note not only the conceptual structure, but the Markdown syntax used.

* Consumers who want to watch a movie with certain specific elements, and would like some title suggestions.

    > As a parent of five, who works full time, I don't have the time to keep up with what new movies have been released, and I know I've missed a lot that would interest me.  And I also don't have the time to read descriptions of random movies hoping to find something I like.  I need a way to filter enough specific preferences to return a small, targeted list of titles from which to choose.
	
* Consumers who want immediate assistance finding a specific film title.
	
	> As a movie buff it is very important to me to not forget the name of a film.  The other night I was out with friends and an old film came up in conversation, that we all remembered obscure details about, but couldn't quite place the title.  If I had an app that could find the title based on a few details it would have come in handy that night.

## Functionality

* The user will be presented with 12 different search fields (genre, year(range), actor, director, writer, composer, studio, run time(range), language, MPAA rating, awards(yes/no), and title), into which they can type as much information as they want or know.  The app will return a list of movie titles that match search criteria, sorted in reverse chronological order.

* The user will be able to add a film title to a watchlist for revisiting at another time.

* A "surprise me" button that will only return one movie title, at random.

## Persistent data

* Watchlisted titles.

* Recent search histories.
    
## Device/external services

* [the_movie_database_API]: https://developers.themoviedb.org/3/getting-started/introduction

## Stretch goals/possible enhancements 

* Additional sorting options (alphabetical, popularity, public ratings, run time, genre)

* Links to online streaming options

* Connection to app developer database of film ratings, so in addition to a "suprise me" button, there will be a "Buffy suggests" button.
