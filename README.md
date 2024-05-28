## Instructions on how to interact with the work

Click the "Play or Stop" button in the upper left corner, wait for the music to start, and play music for 5 minutes and 25 seconds.

## Details of your individual approach to animating the group code

1. Which did you choose to drive your individual code: audio, interaction, Perlin noise or time.

   used audio

2. Which properties of the image will be animated and how; highlighting how it is unique from other group members (i.e. one changes colours, the other component sizes, another reveals only some components at a time, etc.). You will need to work with your group members to make sure your work is sufficiently different from each other.

   The size, color, and shape of the pattern are used to create animation effects

3. References to inspiration for animating your individual code; these can be images (still or gifs). How did they influence your submission?

  Inspired by the vibration effect of the tape when music software plays music

4. A short technical explanation of how your individual code works to animate the image and any appropriate references.

   1. First obtain the amplitude object  of the music through p5.Amplitude(), and at the same time obtain the amplitude through amp.getLevel()
    2. Secondly, use the amplitude calculation to obtain the effective range (square range) and element scaling size.
    3. Finally, for each sub-element object, determine whether the object is within the effective range. If it is within the effective range, update the attribute values ​​(size, shape, random color) of the object. If it is a square, turn it into a circle.