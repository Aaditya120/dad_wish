HOW TO ADD VIDEOS
=================

Drop your video files in this folder, then update index.html.

Find this section in index.html (search for "PAPA_VIDEOS"):

  const PAPA_VIDEOS = [
    { type: 'local', src: 'assests/videos/video1.mp4', title: '🎂 Birthday Celebration', caption: '...' },
    { type: 'local', src: 'assests/videos/video2.mp4', title: '📸 Family Moments',       caption: '...' },
    // Add more here ...
  ];

For YouTube videos use:
  { type: 'youtube', videoId: 'PASTE_VIDEO_ID_HERE', title: 'Title', caption: 'Caption' }

Supported local formats: .mp4, .webm, .ogg
