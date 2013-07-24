Mobile Starter Kit
================================

UI Components
--------------------------------

###Flip switch


Flip switch is used when user has to select one of the two options.

* "active" class needs to be applied for the value which we need to show in the active state by default. 

* "inactive" class needs to be applied for the value which we need to show in the inactive state.  

* "floatRight" class need to be added with class "slider" to position flipswitch to the right side of container. 

* "floatLeft" class need to be added with class "slider" to position flipswitch to the left side of container.

		
		<div class="slider">
			<input id="toggle" type="checkbox" checked="checked">
			<label for="toggle" onclick>
				<div class="options">                       
					<div class="active" value="yes">YES</div>
					<div class="inactive" value="no">NO</div>
				</div>
				<div class="sliderBar"></div>
			</label>
		</div>
		
Example
              
![alt text][FlipswitchYes]

[FlipswitchYes]: ../screenshots/flipswitchYes.png "Demo"


![alt text][flipswitchNo]

[flipswitchNo]: ../screenshots/FlipswitchNo.png "Demo"

*[back] (UI_overview.md)*  
