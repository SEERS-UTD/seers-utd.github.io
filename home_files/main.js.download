jQuery(function() {
	$('#menu-panel').find('a').each(function() {
		var window_href = window.location.href;
		var this_href = jQuery(this).attr('href');
		if ( window_href.indexOf(this_href) > -1) {
			jQuery(this).addClass('active_menu_item');
		}
	});
});