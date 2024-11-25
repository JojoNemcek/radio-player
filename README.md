# Radio Player
A simple, responsive web player for streaming radio. Includes dynamic metadata fetching, volume control.

## Features
**Play/Pause Button:**
<ul><li>Intuitive controls for starting and stopping the stream.</li></ul>

**Volume Control:**
<ul><li>Adjustable slider with smooth volume adjustments.</li></ul>

**Dynamic Metadata:** 
<ul><li>Displays the current song and artist fetched from the radio stream.</li></ul>

## Technologies Used
<ul>
    <li>HTML, CSS, and JavaScript</li>
    <li>Font Awesome icons</li>
    <li>Responsive design for various screen sizes</li>
    <li>Fetch API for dynamic data loading</li>
</ul>

## How to Use
Clone the repository:
```git clone https://github.com/JojoNemcek/radio-player.git```
<br><br>
In JavaScript function fetchMetaData() insert JSON url:
```const response = await fetch("https://stream.aetter.sk/status-json.xsl");```
<br><br>
Insert radio stream URL:
```source.find(stream => stream.listenurl === "http://stream.aetter.sk:8000/aetter") : source;```
<br><br>
Enjoy streaming Radio Aetter live! 🎵