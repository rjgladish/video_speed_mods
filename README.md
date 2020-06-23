# video_speed_mods
Javascript "bookmarks" to override web video playback speed.

This is a collection of simple bookmarks to change the playback speed of videos in situations where the speed control is inaccessible, or options are limited.
In your browser of choice, add one or more of the following "bookmarks" using your bookmark manager, with names such as "2X Video Playback". Does not work on flash videos.

javascript: document.querySelector('video').playbackRate = 0.25;
javascript: document.querySelector('video').playbackRate = 0.50;
javascript: document.querySelector('video').playbackRate = 1.00;
javascript: document.querySelector('video').playbackRate = 1.25;
javascript: document.querySelector('video').playbackRate = 1.50;
javascript: document.querySelector('video').playbackRate = 1.75;
javascript: document.querySelector('video').playbackRate = 2.00;
javascript: document.querySelector('video').playbackRate = 3.00;
javascript: document.querySelector('video').playbackRate = parseFloat(prompt('Playback Rate'));
