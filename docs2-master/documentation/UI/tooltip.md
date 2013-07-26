Mobile Starter Kit
================================

UI Components
--------------------------------

		
###Tooltip		
	
	
		<div class='tooltip'>
				<a class='icon'></a>	  
				<div>
					<span></span><!--It indicates the lip of tooltip-->
					<p>This is tooltip text</p>
				</div>
		</div>
		
		
		$('.tooltip .icon').each(function(){
		showTooltip($(this),$(this).next().children('p').html());
		});
		
		/* The function shows the tooltip when activeped on the icon 
		* In case of multiple tooltips in the page, it will hide the previous tooltip 
		* and show the tooltip currently tapped
		*/
		function showTooltip(obj,val){
			var left,top,value;
			$(obj).click(function(){
				  left = $(this).position().left;
				  top = $(this).position().top;
				  value =  val;//$('.tooltip div p').text();//val;

				  $('.tooltip .icon.active').removeClass('active');
				  $(this).addClass('active');

				  $('.tooltip div p').empty().html(value)
				  $('.tooltip div').css({'left':left-$('.tooltip div').width()+22,'top':top}).css('display','block');
				  return false;
			})
		}
	
		$(document).click(function(){
			$('.tooltip div').css('display','none');
			$('.tooltip .icon.active').removeClass('active');
		});
		
		
Example

####Tooltip

![alt text][tooltip]

[tooltip]: ../screenshots/tooltip.png "Logo Title Text 2"


####tooltip after clicking on it
	
![alt text][tooltipOpen]

[tooltipOpen]: ../screenshots/tooltipWithMessage.png "demo"
		
*[back] (UI_overview.md)* 
