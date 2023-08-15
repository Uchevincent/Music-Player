# Music-Player
html
<!DOCTYPE html>
<html>
<head>
  <title>Music Player</title>
</head>
<body>
  <audio id="musicPlayer" controls>
    <source src="music.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <script>
    const musicPlayer = document.getElementById('musicPlayer');

    // Play the music
    musicPlayer.play();

    // Pause the music
    musicPlayer.pause();

    // Stop the music
    musicPlayer.pause();
    musicPlayer.currentTime = 0;
  </script>
</body>
</html>
