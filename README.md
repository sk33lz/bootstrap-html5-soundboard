# Bootstrap HTML5 Soundboard

## About

Flash Soundboards are a dying breed, so I wanted to make a soundboard boilerplate that will take soundboards into the next century using HTML5.

Bootstrap HTML5 Soundboard runs on strictly on HTML5 and CSS. No Flash is required!

## Features

- Plays HTML5 compatible audio files like M4A, MP3, OGG, and WAV.
- Works in all modern browsers that support the HTML5 <audio> tag.
- Responsive, mobile-friendly design works on mobile devices.
- No need for Flash!

## Installation

1. Download the latest release from the [Releases page](https://github.com/sk33lz/bootstrap-html5-soundboard/releases).

2. Unpack the archive to your web server or local machine.

3. Add images in .png format that are 138px Wide and 120px High to the `img` folder for the best results.

4. Add audio files in HTML5 `<audio>` tag compatible formats like .mp3, .m4a, .ogg, or .wav format to the `audio` folder.

5. Esure that the audio file and image files are the same name.

        Example:
	    chewbacca.mp3
	    chewbacca.png

4. Edit the `index.html` and modify the source code with your file names.

5. Edit the CSS class on the `<audio>` tag to have the same name as your file. This will ensure the JS sets up the proper unordered list rendering the image with the `<audio>` tag.

        Example:
	    <audio class="chewbacca" title="Chewbacca Clip">

## Adding Additional Sound Clips and Images

1. Copy the last full `<audio>` tag lines and paste them below those lines to add another entry.

2. Upload your new HTML5 compatible audio clip to the audio directory, 'audio'. (Formats: .m4a, .mp3, .ogg, .wav)

3. Upload your new PNG image file to the the img directory, 'img'. (Formats: .png)

4. Looking at the source code's `index.html` you would copy the following lines, Lines 84-88, and paste them on the following line, Line 89.

        <audio class="raven" title="Great Odin's Raven! Clip">
		    <source src="audio/raven.mp3" />
		    <source src="audio/raven.ogg" />
		    <source src="audio/raven.wav" />
        </audio>

5. Modify the `<audio>` title to what you would like users to see when they mouseover the image.
		
6. Rinse and repeat these steps for additional soundboard entries with audio clips with images. Just make sure that your `<audio>` class name, your image name, and your `<audio>` src clip name match, or the jQuery won't work properly in rendering the soundboard.

## Credits

- The Bootstrap HTML5 Soundboard was inspired by [Perry Harlock's HTML5 Soundboard](https://github.com/perryharlock/soundboard).

- The JavaScript used in this soundboard was found in [this blog post](http://blog.mozilla.org/webdev/2009/08/06/html5-audio-soundboard/).

- The following audio files and image files included in this repository are copyright their original content creators and copyright owners. These files were included as examples of the types of audio files and image files that can be used in this HTML Soundboard script. These files are included for educational purposes and research only. They should fall under [Fair Use](http://copyright.gov/fair-use/more-info.html).

  - [Chewbacca sound byte](https://www.youtube.com/watch?v=Pr3sBks5o_8) from Star Wars recorded from YouTube.
  - [Phil Connors sound byte](http://goo.gl/B9D74) from Groundhog Day downloaded from moviesoundclips.net.
  - [Obi-Wan Kenobi sound byte](http://goo.gl/IH9Bg) from Star Wars: A New Hope downloaded from moviesoundclips.net.
  - [Ron Burgundy sound byte](http://goo.gl/wkT0M) from Anchorman: The Legend of Ron Burgundy downloaded from moviesoundclips.net.