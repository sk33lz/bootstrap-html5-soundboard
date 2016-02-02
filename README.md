## About

Flash Soundboards are a dying breed, so I wanted to make a soundboard boilerplate that will take soundboards into the next century.

Bootstrap HTML5 Soundboard runs on strictly on HTML5 and CSS. No Flash is required!

## Features

- Plays HTML5 compatible audio files like mp3 and ogg.
- Works in all modern browsers that support the HTML5 <audio> tag.
- Works most devices.
- No need for Flash!

## Installation

1. Download the latest release from the [releases page](https://github.com/sk33lz/bootstrap-html5-soundboard/releases).

2. Unpack the archive to your web server or local machine.

3. Add images in .png or .jpg format that are 138px Wide and 120px High to the `img` folder for the best results.

4. Add audio files in HTML5 <audio> tag compatible formats like .mp3, .mp4, or .ogg format to the `audio` folder.

5. Esure that the audio file and image files are the same name.

    Example:
	chewbacca.mp3
	chewbacca.png

4. Edit the index.html and modify the example code with your file names.

5. Edit the CSS class on the `<audio>` tag to have the same name as your file. This will ensure the JS sets up the proper unordered list rendering the image with the `<audio>` tag.

    Example:
	<audio class="chewbacca" title="Chewbacca Clip">

## Credits

- The Bootstrap HTML5 Soundboard was inspired by [Perry Harlock's HTML5 Soundboard](https://github.com/perryharlock/soundboard).

- The JavaScript used in this soundboard was found in [this blog post](http://blog.mozilla.org/webdev/2009/08/06/html5-audio-soundboard/).

- The audio files and image files included in this repository are copyright their original content creators. These files were included as examples of the types of audio files and image files that can be used in this script. These files are included for educational purposes only and should fall under [Fair Use](http://copyright.gov/fair-use/more-info.html).

  - [Chewbacca sound byte](https://www.youtube.com/watch?v=Pr3sBks5o_8) recorded from YouTube.