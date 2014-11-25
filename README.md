# git-practice

A repo for us to practice our Git workflow, which is available at https://github.com/ojread/git-workflow

We will create a simple website together based on the requirements below. If you have any ideas for features that might be fun to develop together, add them to the list.


## Requirements

Most of the points below should be implemented in a separate feature branch and merged back into the develop branch. If you have any ideas, please add to the list.

- Create a basic web page using PHP
	- create and load separate CSS and JS files
	- create a sensible directory structure
	- give it a standard blog-style layout
		- consider using a framework such as Bootstrap or Foundation
- Separate out the different template parts:
	- header
		- show a banner image at random
	- sidebar with navigation
		- links to all content pages
	- footer
	- any other common template parts you can think of
- Create content pages that dynamically include the template parts
	- home page
	- team members section
		- a sub page for yourself with any content you like
	- christmas page with a countdown using JS
		- extend and reuse this code to show multiple countdowns
		- on team pages have a countdown to birthdays
	- AJAX
		- create a basic PHP page that simply displays a random quote from a list
		- create a front-end page that uses JavaScript to fetch content from the quote page
		- fetch a new quote when the user clicks a button or on a timer without reloading the page
	- Image gallery
		- PHP file that lists all images in a specific directory in the filesystem
		- click on images to see them on a separate page or in a lightbox and scroll through them