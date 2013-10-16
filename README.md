Skeleton Modified
========================

Skeleton: A Beautiful Boilerplate for Responsive, Mobile-Friendly Development

Modified CSS: skeleton_mod.css
Added an option without offsets and an option for a completely fluid skeleton based on percentages

The responsive container is based on a 16 column grid, so to create a two column panel you would code the container like so…

<div class="container">
	<div class="seven columns">
		SPANS 7 COLUMNS - CONTENT HERE
	</div>
	
	<div class="nine columns">
		SPANS 9 COLUMNS - CONTENT HERE
	</div>
</div>

* Note 7 + 9 = 16. You can use any combination of column classes as long as your row = 16.


To add offsets (space between the columns), just add the "offset" class to the wrapping container...

<div class="container offset">


To make fluid (responsive to all screens), just add the "fluid" class to the wrapping container...

<div class="container fluid">
