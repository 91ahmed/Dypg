### JQuery Dynamic Pagination

#### Download
https://91ahmed.github.io/projects/dypg/dypg.zip

#### Demo
https://91ahmed.github.io/projects/dypg

#### Example

Include the files
``` html
<!-- css -->
<link rel='stylesheet' href='dypg.css'>

<!-- javascript -->
<script src='jquery-3.7.0.min.js'></script>
<script src='dypg.js'></script>
```

Create html element with 'dypg' id
``` html
<ul id='dypg'></ul>
```
Initialize javascript options
``` javascript
dyPaginate ({
	count: 35, // number of pages
	current: 1, // determine the current page
	pages: 5,  // number of pages to be displayed per page
	first_text: 'First', // set the first page text
	last_text: 'Last', // set the last page text or icon
	next_text: 'Next', // set the next page text or icon
	prev_text: 'Prev' // set the previous page text or icon
})
```