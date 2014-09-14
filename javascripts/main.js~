jQuery(document).ready(function() { //checks to see if the document is ready
	jQuery('.tab-links a').on('click', function(e) { //when a clikc event happens on a tab with ".tab-links a"
		
		var currentAttrValue = jQuery(this).attr('href'); //grabs the href of the clicked achor link
		
		// Show/Hide Tabs
		jQuery('.tabs ' + currentAttrValue).fadeIn(400).siblings().hide();	
		jQuery(this).parent('li').addClass('active').siblings().removeClass('active'); //change/remove current tab to active
		e.preventDefault();
		
		//fade animation
		
