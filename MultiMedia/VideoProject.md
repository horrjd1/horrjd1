<style>
  .resp-container {
    position: relative;
    overflow: hidden;
    padding-top: 56.25%;
}
  .resp-iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}
</style>

## Video:
<div class="resp-container">
<iframe class="resp-iframe" src="https://www.youtube.com/embed/-JR7h4kgNoM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


## Shot list
<table>
	<tr>
    		<th>Camera Subject</th>
    		<th>Shot Type</th>
		<th>Camera Angle</th>
		<th>Camera Move</th>
	</tr>
	<tr>
		<td>Actor</td>
    		<td>Medium Close-up</td>
    		<td>Eye level</td>
    		<td>None</td>
 	</tr>
  	<tr>
		<td>Razer Synapse Software</td>
    		<td>Screen recording</td>
    		<td>-</td>
    		<td>-</td>
  	</tr>
    	<tr>
		<td>Overwatch (game)</td>
    		<td>Screen recording</td>
    		<td>-</td>
    		<td>-</td>
  	</tr>
    	<tr>
		<td>Keyboard Fulls</td>
    		<td>Full shot</td>
    		<td>Birds eye view</td>
    		<td>None</td>
  	</tr>
    	<tr>
		<td>Keyboard Sections</td>
    		<td>Close-up, medium, Full</td>
    		<td>High angle, low angle</td>
    		<td>none</td>
  	</tr>
      	<tr>
		<td>Keyboard Pans</td>
    		<td>Close-up</td>
    		<td>High angle</td>
    		<td>Pan</td>
  	</tr>
</table>
(Fulls mean showing the keyboard of its entirety)
(Sections means showing a section of the keyboard)
(Pans means panning over keys)

I havent listed out all of the keyboard full, section and pan shots as there will be too many that only slightly change the angle, So I plan to experiment with angles during the filming. Im doing this because there are alot of parts in the review where im generally speaking about the keyboard as a whole (such as the conclusion) where I cant accuratly plan out what shots are going to be shown. For these moments I plan to use a variety of angled section shots.

more footage then I need So in post production I will find a selection of the best of these angles shots during these sections.

## Storyboard

I have listed the shots I know I need in the storyboard (shots showing features that I talk about specifically). 

## Decisions

For the whole video I decide to mostly use fades as transitions, as the background footage was static or slow panning, so I used fades to keep the relaxed atmosphere. I changed up the transitions for the intro and the transition to the game. I did this on the intro because it provides a visual way to separate the title screen/intro shots from the video itself, and I did it on the games because it visualises jumping into a game.

All of the titles for the video were in the same font (Bahnschrift Semi-Condensed) and are all located in the bottom left, to keep consistency.

For a lot of the shots I tried to keep the keyboard very close to the edge of the frame. This was to keep the video visually interesting, since I relied on birds eye view shots for a lot of parts in my review. I didn’t do any wide shots as the focus of the review is the keyboard and my setup shouldn’t be relevant. 

For the bird’s eye view shots, I added some white space around the edges. This means that on the shots that need subtitles and the shot where I put the wrist rest on had extra room for those extra things.

For some of the shots I tried to get my phone camera to change focus midway through the shot. I did this because I was trying to replicate the effect that is present on a lot of more professional reviews where they change the depth of field of the camera midway through the shot. I used this effect to give some of my static shots a sense of movement.

This was also the reason that I used my custom wave lighting effect on the keyboard, to give it a sense of movement. I also tried to match the colours with the wallpaper of my computer so that when it transitions to the screen recording it doesn’t feel too jarring.

The music I used is copyright and royalty free and was intended to be used in the background of YouTube videos. I credited the author in the description as is required when using the song. I decide that a relaxing electronic song would be best but they were hard to find so hiphop was the next best thing. -----
Song also matched my plans for the opening, it had a good build up at the start.

I decided to start the video with me talking to the camera, I did this because for the intro, I wasn’t talking about the keyboard, and instead I was talking about people (possibly some of them watching). Since it was addressed to the viewer, I talked to the camera.

## Technical:

### Colour Correction

Comparisons (my version on the left, original footage on the right)
Almost all of my video was black and white (white desk and black keyboard) so the impact of my colour correction was mostly to create contrast between the two, as well as make the keyboards backlighting more vibrant. I used two video effects to achieve this.

In the ‘Colour-Correction’ effect I increased the saturation a small amount. In order to make the keyboards backlight more vibrant.

In the ‘Colour-Curves’ effect I increased the contrast in order to make the desk whiter and the keyboard darker


### Screen Pump Transition

Transition used at 0:12 and 2:24

I made this ‘screen pump’ transition (not a default transition) for transitioning to the introduction (me on camera talking) as well as transitioning from the list of games into a game.

I did this during the intro as a visual way of separating the intro shots of the keyboard and the start of the review.

And used it again when transitioning into the gameplay in order to keep have a different transition to keep things interesting. The previous shot was already moving quite fast so having a zooming transition wasn’t too jarring.

#### How I made it

In order to create this effect I used the ‘BlurMoCurves’ effect. This effect had to be made on each of the two clips on either side of the transition.

On the first clip I created key frames at the end of the clip and 4 frames before the end of the clip. Using those key frames I made the Z Distance go from 1 to 1.6. This gave it a smooth, blurred zoom out. I also made the footage wrap when it zoomed out so that it didn’t zoom out into black.

Then for the second clip I did the opposite. I created key frames at the start and 4 frames after the start, and by using those key frames I made the Z Distance go from 0.6 to 1.

### Fading

I used to types of fading in my video. Fading into another clip and fading to and from black

I used 20 frames as a standard for fading duration between two shots, but increased or decreased the length when necessary. For example when the fade happens mid-sentence, then I would stretch the fade length in order to make the footage less abrupt.

### Stabilization

For my panning shots I used Vegas’s stabilization effect. For this effect I set the ‘Pan smoothing’ to 50 and the ‘Stabilization amount’ to 20 as increasing the stabilization amount any more would make the footage too far zoomed in.


### File Structure

Since this project involved a lot of files, I made sure to keep my file system clean and organized. I kept all the different elements of the video (music, graphics etc) in their own folders.

The footage folder was separated into four subfolders separating the recordings by what the subject is. 

Since the preview in Vegas can lag slightly during effects or fades, I exported some of these small sections of the video to check that the timing matched up properly etc.

### Rendering

When rendering the final version I used an internet template that Vegas already had. 

All of its setting matched what I was reading in YouTubes help website:
https://support.google.com/youtube/answer/1722171?hl=en

I didn’t need to change the video codec as AVC is the same as H.264.

However since my video was 1080p 30fps I used a 10Mbps bitrate instead of a 16Mbps. This would decrease the file size without losing any video quality.

