#Tasks
###Task 1:
#####Create a HTML page containing the folowing:
* `Header` section, containing the following:
	* Nav bar with div with class `nav`, containing:
		* Unordered list with sample links
* Div with id `main content`, containing the following:
	* Div with id `artists`, containing:
		* Bootstrap-looking grid system with sample content
		* Example:
		```
		<div class="row">
			<div class="col-3">
				...
			</div>
		</div>
		```
* Add a `link` in the head section to connect to your css and style the page:
	* Clear all default styles set by the browser
	* Add custom font; Use this for reference - [Custom font usage in css](http://www.w3schools.com/cssref/css3_pr_font-face_rule.asp)
		* To use custom font just simply go to this [website](http://www.fontsquirrel.com/) download a sample font or convert your font file (file with extension .ttf or .otf)
		* You can locate your fonts in the directory in your PC as follows: `Control Panel\Appearance and Personalization\Fonts`
	* Style the navigation bar using whatever colors, links and fonts you like
		* Add `hover` effects (HINT: Use `transition` for cool efects)
	* Style the custom grid system making every `.col-3` with `20%` width
	* Style the artist' data and add some `box-shadow` to it; If you want, use this [tool](http://www.cssmatic.com/box-shadow)
* Result should look like: [Result image](01.StyleWithCSS.png)

###Task 2:
#####Use the files from the `Task 1` and modify the following:
* Change the `header` section, using Bootstrap classes and html tags (HINT: the header has a `Navbar`) - see [documentation](http://getbootstrap.com/components/)
