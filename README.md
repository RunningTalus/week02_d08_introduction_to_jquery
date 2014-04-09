//
Week02, Day08

Document Object Model- Internal (in-memory) representation of HTML.  
	
	DOM has two children- Head & Body
		Head has two children- Meta and Link
		Body has three children-
		
		NODES-???
		Tags represent text within HTML.  
		Tags <div> are NOT represented in the DOM.
		Only ELEMENTS, CLASSES, and ID's are in the DOM.  
		
	window object IS the global object
		window.location.href - an example that we've seen.

	How we can test this?
	In Chrome Developer Tools...

	var start = 25
	window
	window.start
	//console renders 25

	Access to the DOM via...
	document.head
	document.body
	...as these are required HTML elements.  

	document.body.childNodes[1]
	document.body.childNodes[1].style
	console.dir
	
	JavaScript does not know ANYTHING about selectors.  
		JS sees selectors as "STRINGS" i.e. ".col"
		The jQuery Library was written to parse selectors.

	A function on an object is a METHOD.
	$ === jQuery

	//Short break//

	


