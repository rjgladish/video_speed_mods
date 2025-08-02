# video_speed_mods
Javascript "bookmarks" to override web video playback speed.

This is a collection of simple bookmarks to change the playback speed of videos in situations where the speed control is inaccessible, disabled, or options are limited.
In your browser of choice, add one or more of the following URL "bookmarks" using your bookmark manager, with names such as "2X Video Playback". Must include semicolon at the end. 
N.B.
- Does not work on flash videos, and may not defeat coursework timing mechanisms.
- The last bookmark prompt for playback rate, less than 5 recommended. 

javascript: document.querySelector('video').playbackRate = 0.25;

javascript: document.querySelector('video').playbackRate = 0.50;

javascript: document.querySelector('video').playbackRate = 1.00;

javascript: document.querySelector('video').playbackRate = 1.25;

javascript: document.querySelector('video').playbackRate = 1.50;

javascript: document.querySelector('video').playbackRate = 1.75;

javascript: document.querySelector('video').playbackRate = 2.00;

javascript: document.querySelector('video').playbackRate = 3.00;

javascript: document.querySelector('video').playbackRate = parseFloat(prompt('Playback Rate'));
