# WallpaperGenerator

Here is some detailed information on how to use Wallpaper Generator (DOCUMENTATION NOT FINISHED)

<ul>
<li><code>createPixelTile(color, imageFormat)</code> use this function to create 1x1 size image which can be later pasted onto a bigger tile to make shapes like triangles, quartercircles, semicircles etc.<br>
<code>color</code> : color tuple<br>
<code>imageFormat</code> : string ('jpg', 'png')
</li>

<li><code>createSquareTile(xLimit, yLimit, color)</code> use this function to create an image of specified size and color<br>
<code>xLimit</code> : width of output image<br>
<code>yLimit</code> : height of output image<br>
<code>color</code> : color tuple<br>
</li>

<li><code>createTriangleTile(foregroundColorImage, backgroundColorImage)</code> use this function to create all possible tiles with triangles in foreground on square background<br>
<code>foregroundColorImage</code> : color tuple of the 1x1 size image (it should already exist)<br>
<code>backgroundColorImage</code> : color tuple of the image to be used as background (it should already exist)<br>
</li>

<li><code>createCircleTile(foregroundColorImage, backgroundColorImage, style)</code> use this function to create all possible tiles with quartercircle/semicircle (specified through style) in foreground on square background<br>
<code>foregroundColorImage</code> : color tuple of the 1x1 size image (it should already exist)<br>
<code>backgroundColorImage</code> : color tuple of the image to be used as background (it should already exist)<br>
<code>style</code> : string ('quartercircle', 'semicircle')<br>
</li>

<li><code>createSquareWallpaper(foregroundColor, backgroundColor, imageFormat)</code> use this function to create wallpaper of desired imageFormat with input foregroundColor & backgroundColor<br>

</li>

