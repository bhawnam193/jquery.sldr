jquery.sldr
====

Design Features

<ol>
	<li>Multiple slide width.</li>
	<li>Visible stage.</li>
	<li>Responsive height and width.</li>
</ol>

Dev Features:

<ol>
	<li>Support for IE 7+, Chrome, Safari, Firefox, IOS 3+, Android 3+. Not tested in Opera or older versions of Chrome, Safari, Firefox.</li>
	<li>Callbacks on initialization, slide start, slide complete.</li>
	<li>Next, previous, pagination, and element toggle selector definitions.</li>
	<li>¡To do! Animation Hook. Define your own animation.</li>
</ol>

To do:

<ol>
	<li>Make base.resizeElements work with offset option.</li>
	<li>Responsive Height Option. By default, the slider's height is responsive if the using 100% width block images. May include function however to set the style of the slider's width.</li>
	<li>Rework base.fillGaps to work with post loaded images. </li>
	<li>Establish method for passing updated args on to callback functions if using the Animation Hook.</li>	
	<li>A shadow box mode.</li>
	<li>Click Drag/Swipe pagination for mobile.</li>
</ol>

Settings:

<table>
<tr><td>focalClass    </td><td>The classname of the focal point of the slider (or 'active' slide). Defaults to 'focalPoint'.</td></tr>
<tr><td>offset        </td><td>¡To do! The center point of the slider. Defaults to "$(this).width() / 2" (or center of the slider).</td></tr>
<tr><td>selectors     </td><td>Selectors for the paginating elements. Example "$('ul > li')". No Default.</td></tr>
<tr><td>toggle        </td><td>A series of elements to toggle the focalClass of. Can be used to show/hide captions. Example "$('.descriptions > div'')" No Default.</td></tr>
<tr><td>nextSlide     </td><td>Selector for the next slide. No Default.</td></tr>
<tr><td>previousSlide </td><td>Selector for the previous slide. No Default.</td></tr>
<tr><td>hashChange    </td><td>Optional boolean that gets passed through the callback args. Defaults to false.</td></tr>
<tr><td>resizeDelay   </td><td>Delay for the window resize. Defaults to 1.</td></tr>
<tr><td>sldrNumber    </td><td>Number of slides that increases when the sldr is initiated. Defaults to 0.</td></tr>
<tr><td>sldrInit      </td><td>Callback. Accepts function name. When the sldr is initiated, before the DOM is manipulated. No Default.</td></tr>
<tr><td>sldLoaded     </td><td>Callback. Accepts function name. When individual slides are loaded. No Default.</td></tr>
<tr><td>sldrLoaded    </td><td>Callback. Accepts function name. When the full slider is loaded, after the DOM is manipulated. No Default.</td></tr>
<tr><td>sldrStart     </td><td>Callback. Accepts function name. Before the slides change focal points. No Default.</td></tr>
<tr><td>sldrComplete  </td><td>Callback. Accepts function name. After the slides are done changing focal points. No Default.</td></tr>
<tr><td>sldrWidth     </td><td>The width of the slider. Set to 'responsive' for full width slides. Set to number for fixed width. Defaults to the width of the slider.</td></tr>
<tr><td>animate       </td><td>¡To do! Hook for custom animation. Accepts function name. Defaults to "base.animate" in jquery.sldr.js.</td></tr>
<tr><td>animateJQ     </td><td>Force default animation to jquery animate(). Defaults to false using CSS transitions. Browsers that do not support CSS transitions use jquery animate().</td></tr>
<tr><td>sldrAuto      </td><td>Auto timer for transition. Defaults to false.</td></tr> 
<tr><td>sldrTime      </td><td>Auto timer time transition time. Defaults to 8000.</td></tr>
<tr><td>isBrowser     </td><td>Variable for setting browser. Defaults to the navigator.userAgent.</td></tr>
<tr><td>isIE   		  </td><td>Variable for Internet Explorer. Defaults to false. Will be set to true based on navigator.userAgent.</td></tr>
</table>