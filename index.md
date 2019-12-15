{% include_relative listeners.html %}
{% include_relative scripts-local.html %}
{% include_relative styles-local.html %}

<img src="/image/z.jpg">

<div style="background-color: #eee; min-height:100px; min-width:800px;">
<script type="text/x-humdrum" id="example">
**kern
=1
1ryy
=-
*-
</script>
</div>

<table id="button-list">
<tr>

<td><div class="button" onclick="copyHumdrum()">copy Humdrum data</div></td>

<td><div class="button" onclick="copyMei()">copy MEI data</div></td>

<td><div class="button" onclick="clearData()">clear</div></td>


</tr>
</table>

<h2> Instructions </h2>

<ul>

<li> <b> Adding clef</b>
	<ul>
	<li> Type <span class="hi">C</span> to insert C3 clef.</li>
	<li> Type <span class="hi">2</span> or press the <span class="hi2">down</span> arrow to move clef to second line.</li>
	</ul>
</li>

<li> <b> Adding pitches</b>
	<ul>
	<li> Type pitch <span class="hi">letter</span> name of each note to add them to the line: <span class="hi">f.ed.efgagfgedderfag</span></li>
	<li> Type "<span class="hi">.</span>" to add dot after note.</li>
	<li> Type "<span class="hi">r</span>" to add a rest.</li>
	<li> Type <span class="hi2">backspace</span> to delete note.</li>
	<li> Capital letters choose direction of pitch class which is greater then lower case letters.</li>
	<li> <span class="hi2">Up/down</span> arrows transpose last pitch up/down a step.</li>
	<li> <span class="hi2">shift-Up/down</span> arrows transpose last pitch up/down an octave.</li>
	<li> <span class="hi2">backspace</span> delete last letter.</li>
	<li> <span class="hi2">shift-backspace</span> deletes entire syllable.</li>
	<li> Add dash at end of text for note to continue word to next note.</li>
	</ul>
</li>

<li> <b> Adding rhythm</b>
	<ul> 
		<li> <span class="hi">1</span> semibreve,
		     <span class="hi">2</span> minim,
		     <span class="hi">4</span> semiminim,
		     <span class="hi">8</span> fusa,
		     <span class="hi">6</span> semifusa,
		     <span class="hi">0</span> breve,
		     <span class="hi">9</span> long,
		     <span class="hi">7</span> maxima.
		<li><i>Interleaved method</i>: type (new) rhythm before adding a note.  The default rhythm is whole note (semibreve).  First note's rhythm should be typed before adding clef.</li>
		<li><i>Second-pass method</i>: type pitches first, then select first note and type rhythms to update note rhythms.</li>
		<li><i>Selective second-pass method</i>: type most common rhythm, then clef, then notes, then click on notes that need rhythms to fix.  Typing rhythm number will change rhythm and advance to next note.</li>
		<li> left/right arrow keys or tab/shift-tab moves to next/previous note/rest/clef.</li>
	</ul>
</li>

<li> <b> Adding text</b>
	<ul>
		<li>Click on a note (or left/right arrows or tab/shift-tab to move to target note).</li>
		<li>Type text for note, then press tab or right arrow key or click to go to next note.</li>
		<li> When at the end of the list, type tab twice or right arrow twice or click on first note to go to first note for adding rhythms/text starting at beginning of line.</li>
	</ul>
</li>

</ul>

