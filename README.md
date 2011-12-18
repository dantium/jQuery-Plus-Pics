# jQuery Display Google+ Images Plugin

## Demo

[Demo Display Google+ Images](http://www.danatkinson.com/demo/googlepluspics/)

## Setup instructions

Include the JS and CSS files

	<link rel="stylesheet" href="style.css" type="text/css" media="screen, projection" />
	<script type="text/javascript" src="pluspics.js"></script>

Then add the command to run the plugin:

	<script type="text/javascript">
	$(document).ready(function(){
		$('#container-id').plusPics({
			userId: 'your_user_id',
			albumId: 'your_album_id',
			numImages: 3,
			title: 'Images'
		});
	});
	</script>

## Requirements

* [jQuery](http://jquery.com/) v. 1.4.2+