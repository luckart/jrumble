# jRumble

[![Project Status: Inactive - The project has reached a stable, usable state but is no longer being actively developed; support/maintenance will be provided as time allows.](http://www.repostatus.org/badges/latest/inactive.svg)](http://www.repostatus.org/#inactive)
[![CDNJS version](https://img.shields.io/cdnjs/v/jrumble.svg)](https://cdnjs.com/libraries/jrumble)

#### 2016-11-04 Update

This project is no longer being developed or maintained. I recommend using the the CSS version, [CSSShake](https://elrumordelaluz.github.io/csshake/) by [@elrumordelaluz](https://github.com/elrumordelaluz/). It performs a lot better and has tons of options. 

---

jRumble is a [jQuery](http://jquery.com) plugin that rumbles, vibrates, shakes, and rotates any element you choose. It's great to use as a hover effect or a way to direct attention to an element.

- **Latest Version:** 1.3
- **Latest Release Date:** December 3, 2011
- **Original Release Date:** March 30, 2011
- **Compressed:** 1.47kb
- **Uncompressed:** 4.84kb

### Documentation, Demos, and Discussion

Documentation, demos, and discussion can be found at http://jackrugile.com/jrumble

### Basic Usage

```javascript
// Initialize jRumble on Selector
$('#rumble-element').jrumble();

// Start rumble on element
$('#rumble-element').trigger('startRumble');

// Stop rumble on element
$('#rumble-element').trigger('stopRumble');
```

### Options

<table>
	<thead>
		<tr>
			<th>Option</th>
			<th>Default</th>
			<th>Description</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td><strong>x</strong></td>
			<td><em>2</em></td>
			<td>Set the horizontal rumble range (pixels)</td>
		</tr>
		<tr>
			<td><strong>y</strong></td>
			<td><em>2</em></td>
			<td>Set the vertical rumble range (pixels)</td>
		</tr>
		<tr>
			<td><strong>rotation</strong></td>
			<td><em>1</em></td>
			<td>Set the rotation range (degrees)</td>
		</tr>
		<tr>
			<td><strong>speed</strong></td>
			<td><em>15</em></td>
			<td>Set the speed/frequency in milliseconds between rumble movements (lower number = faster)</td>
		</tr>					
		<tr>
			<td><strong>opacity</strong></td>
			<td><em>false</em></td>
			<td>Activate opacity flickering while rumbling</td>
		</tr>
		<tr>
			<td><strong>opacityMin</strong></td>
			<td><em>.5</em></td>
			<td>When the opacity option is set to true, this controls the minimum opacity while flickering</td>
		</tr>
	</tbody>
</table>

### Known Issues

- For rumble elements that are position fixed/absolute, they should instead be wrapped in an element that is fixed/absolute
- Rotation does not work in Internet Explorer 8 and below
