# sticky-code

$(window).scroll(function(){
    if ($(this).scrollTop() > 150) {
       $('#stickyCart').addClass('stickyCart');
    } else {
       $('#stickyCart').removeClass('stickyCart');
    }
});




#stickyCart{
	transition:all 0.3s;
}
#stickyCart.stickyCart{
	display:none !important;
}
#stickyCart .FfNlk .pf-variant-select  {
	border-width: 0px !important  ;
}
#stickyCart .FfNlk .pf-variant-select:focus-visible {
	outline: 0 solid   !important;
	outline-offset: 0!important;
	box-shadow: 0 0 0 0 #ff000000 !important,0 0 0 0 #ff000000 !important;
}
