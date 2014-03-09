# yags - Yet Another Grid System (v.1.1)

It's a 12-columns ~ Margin left: 10px ~ Margin right: 10px; 4 breakpoints grid system.

Based on the [1kb.grid system](http://www.1k.crid.com/)
by Tyler Tate. 
& [Skeleton V1.2](http://www.getskeleton.com/)
by Dave Gamache.

Created by [Pawel Jonik](http://twitter.com/)
Free to use under [MIT License](http://opensource.org/licenses/MIT/)

## Quick how-to
This grid is based on html5 markup: sections & articles (you'll need [html5shiv.js](http://github.com/afarkas/html5shiv) & [respond.js](https://github.com/scottjehl/Respond) for this to work on IE8). Articles consist of columns (.col).
You can use div.container (or .section) & div.row (or .article) though (only respond.js needed in this case).

### Others are:
	.col = column setup
	.c1~12 = column width
	.on1~11 = column offset

### If you use:
	.half, .o-half, 
	.one-third, .two-thirds, .o-one-third, 
	.one-fourth, .three-fourths, .o-one-fourth, .o.three-fourths 
instead of 
	.c1~12
the columns will be forced on all resolutions.

## Example for html5 sectioning markup ([demo](http://paweljonik.net/.github/yags/index.html)): 

	<section>
		<article>
		    <div class="col c8">
		      <p>8-column content</p>
		    </div>
		    <div class="col c4">
		      <p>4-column content</p>
		    </div>
		</article>
	</section>
	
## Example for html4 div markup ([demo](http://paweljonik.net/.github/yags/index2.html)): 

	<div class="section">
		<div class="article">
		    <div class="col c8">
		      <p>8-column content</p>
		    </div>
		    <div class="col c4">
		      <p>4-column content</p>
		    </div>
		</div> <!-- /article -->
	</div> <!-- /section -->

Simple, huh. ;-)

