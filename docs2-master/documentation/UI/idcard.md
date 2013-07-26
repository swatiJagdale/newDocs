Mobile Starter Kit
================================

UI Components
--------------------------------

###IDCard		
		
	<div class="cardContainer" data-value="cardContainer">
					<div class="card">
						<div class="cardFace cardFront">
							<div class="cardBackground">
								<a class="flip" data-value='flipButton'><span>Flip</span></a>
							<div class="cardContent">
								<ul><li>Customer #:0123654</li>
								<li>MetLife ID Number:546461665</li>
								<li>Name:RoMMEL M LAPID III</li></ul>
								<p>Do you have question on the plan design or 
								your claim? We can be reached by dialing:1-888-865-5455, 
								TDD 1-456-456-4125,from anywhe	re in the world. 
								overseas ? Looking for provider / Call the AXA Assistance Hot
								Line at: From the United States:1-456-852-4521 collect call 
								from anywhere in the world:321-321-5636</p>
							</div>
							</div>
						</div>
						<div class="cardFace cardBack">
							<div class="cardBackground">
								<a class="flip" data-value='flipButton'><span>Flip</span></a>
								<div class="cardContent">
								  <ul>
										<li>Dental Customer Service Consultants are available to answer your question:</li>
										<li>Monday - Friday,8AM - 11PM (ET)</li>
								  </ul>
								  <ul class="contact">
									<li>Information for your Dentist:</li>
									<li>www.metdental.com</li>
								  </ul>
								  <ul class="contact">
									<li>Mail Claims to:</li>
									<li>MetLife Denta; Claims</li>
									<li>P.O. Box 987456</li>
									<li>El Paso,TX 79998-4587</li>
								  </ul>
								  <ul class="contact">
									<li>Fax Claims to: 1-46-4545-545</li>
									<li>Electronic Payor Number: 445645</li>
								  </ul>
								 </div>
							</div>
						</div>
					</div>
			</div>	
			
			
			$(function(){
				$("[data-value='flipButton']", this.page).bind('click', function(e){
				$("[data-value='cardContainer']").toggleClass("flip");	
			});
			});
			
			  
Example

####IDCard
			
![alt text][idCard]

[idCard]: ../screenshots/idCard.png "demo"

####Fliped IDcard  

![alt text][idCard2]

[idCard2]: ../screenshots/idCard2.png "demo"



		
		
*[back] (UI_overview.md)*  
