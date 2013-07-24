Mobile Starter Kit
================================

UI Componets
--------------------------------

###Toggleswitch


		
		<div class="toggleswitch" id="toggleswitch">	
					<div class="options" onclick="toggle(this);" id="yesBtn"><span>YES</span></div>
					<div class="options" onclick="toggle(this);" id="noBtn"><span>NO</span></div>
		</div> 
		
		
		function toggle(element){
			 $(".toggleswitch *").removeClass("active");
			 $(element).addClass("active");
		   }
	

Demo


![alt text][toggleWithoutSelection]

[toggleWithoutSelection]: ../screenshots/toggleWithoutSelection.png "Demo"


![alt text][toggleYesSelection]

[toggleYesSelection]: ../screenshots/toggleYesSelection.png "Demo"


![alt text][toggleswitchNoSelection]

[toggleswitchNoSelection]: ../screenshots/toggleswitchNoSelection.png "Demo"

*[back] (UI_overview.md)*  
