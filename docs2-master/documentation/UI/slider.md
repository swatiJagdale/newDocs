Mobile Starter Kit
================================

UI Components
--------------------------------

###Slider

	var sliderOpen = -1;
			
			/* Slider function */
			function showOptions(id){
			var slider1 = $('#slider' + sliderOpen);; 
			if(sliderOpen != -1){
				var flag= false;
				 $(slider1).css("-webkit-transform","translate(0)");
				 $(slider1).siblings(".right").css("-webkit-transform","translate(0)");			
				 if(flag)return;
			}
			if(sliderOpen != id){	
				var slider = $('#slider' + id);
				if( id =='4'){
					$("#sliderInput").addClass("disable");
					$(slider).css("-webkit-transform","translate(-180px)");
					$(slider).siblings(".right").css("-webkit-transform","translate(50px)");		
					$(slider).siblings(".right").children(".arrow").hide();
					$(slider).children("span").show();
					$(slider).siblings(".right").children("span").show();
					sliderOpen = id;
					setTimeout(function() {		
						$(slider1).siblings(".right").children("span").hide();
						$(slider1).children("span").hide();
					  },700);
					setTimeout(function() {		
						$(slider1).siblings(".right").children(".arrow").show();
					  },850);
				}else if(id =='1' || id =='2' || id =='3')
				 {

					$(slider).css("-webkit-transform","translate(-180px)");
					$(slider).siblings(".right").css("-webkit-transform","translate(50px)");		
					$(slider).siblings(".right").children(".arrow").hide();
					$(slider).children("span").show();
					$(slider).siblings(".right").children("span").show();
					sliderOpen = id;
					setTimeout(function() {		
						$(slider1).siblings(".right").children("span").hide();
						$(slider1).children("span").hide();
					  },700);
					setTimeout(function() {		
						$(slider1).siblings(".right").children(".arrow").show();
					  },850);
				 
				 }
			}
			else{
				setTimeout(function() {		
					$(slider1).siblings(".right").children("span").hide();
					$(slider1).children("span").hide();
				  },700);
				setTimeout(function() {		
					$(slider1).siblings(".right").children(".arrow").show();
				  },850);
				sliderOpen = -1;
				if(id == '3'){
					setTimeout(function() {	
						$("#differentDueAmount").removeClass("disable");
				  },850);
					
				}
			}
		}



###Slider
		
				<div class="sliderControl">			
					<div class="options">
						<a href ='#' class="button blue ">Btn1</a>
						<a href ='#' class="button blue">Btn2</a>
						<a href ='#' class="button blue">Btn3</a>
					</div>
					<div class="left transition" onClick="showOptions('1')"	id='slider1'>
						<label class='bold'>Label</label>
						<div>$00.00</div>
						<span></span>
					</div>
					<div class="right transition" onClick="showOptions('1')">
						<span></span>
						<div class="arrow"></div>
					</div>
				</div>  
				

Example

![alt text][slider]

[slider]: ../screenshots/slider.png "demo"


![alt text][sliderOpen]

[sliderOpen]: ../screenshots/sliderOpen.png "demo"


	
###Slider with Input element

					<div class="sliderControl">
						<div class="options">
							<a href ='#' class="button blue">Btn1</a>
							<a href ='#' class="button blue">Btn2</a>
							<a href ='#' class="button blue">Btn3</a>
						</div>
						<div class="left transition" id='slider4'>
							<label class='bold'>Label</label> 
							<input type='text' id="sliderInput" placeholder='$0.00' onblur="showOptions('4')"/> 
							<span></span>
						</div>
						<div class="right transition" onClick="showOptions('4')">
							<span></span>
							<div class="arrow"></div>
						</div>
					</div>


Example


![alt text][sliderWithInput]

[sliderWithInput]: ../screenshots/sliderWithInput.png "demo"


![alt text][sliderwithInputOpen]

[sliderwithInputOpen]: ../screenshots/sliderwithInputOpen.png "demo"


*[back] (UI_overview.md)*  
