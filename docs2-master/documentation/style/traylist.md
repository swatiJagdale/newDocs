Styling for elements
================================

textbox
--------------------------------

		<input type="text" placeholder="Driver's name" data-offset="none"/>
		
		*[demo] (http://github.github.com/accordion.html).*  
		
		
		    <div class='banner'>
			<nav class="contentLink">
				<ul>
					<li>
						<a class='icon autoAccident' data-transition='slide' data-ajax='true'></a>
						<a href="#home" data-tab="autoAccident" id="autoAccidentTrayClick"
					data-transition="slide" data-ajax="true"
					onclick="invokeLandingPage('trayList.html','../auto/autoAccidentToolkitLanding.html');">
								<div class='item'>
										<span class='title'>Auto Accident</span>
								</div>
						</a>
					</li>
					<li>
						<a class='icon billPay' data-transition='slide' data-ajax='true'></a>
						<a href="#payBill" data-tab="payBill"  id="payBillTrayClick"
					data-transition="slide" data-ajax="true"
					onclick="viewPolicyAndPayBill('../billing/accountSelection.html','../billing/billPayMultiplePolicies.html');">
								<div class='item'>
										<span class='title'>View & Pay Bill</span>
								</div>
						</a>
					</li>
				</ul>
			</nav>	
		</div> 
			<div class="content">
					<nav>
						<ul>
							<li>
								<a class='icon auto' data-transition='slide' data-ajax='true'></a>
								<a href="auto/index.html" data-tab="auto" id="autoTrayClick" data-transition="slide" data-ajax="true">
										<div class='item'>
												<span class='title'>Auto</span>
										</div>
								</a>
								<div id="autoTray"></div>
							</li>
							<li>
								<a class='icon dental' data-transition='slide' data-ajax='true'></a>
								<a href="dental/index.html" data-tab="dental" id="dentalTrayClick" data-transition="slide" data-ajax="true">
										<div class='item'>
												<span class='title'>Dental</span>
										</div>
								</a>
								<div id="dentalTray"></div>
							</li>
							<li>
								<a class='icon home' data-transition='slide' data-ajax='true'></a>
								<a href="home/index.html" data-tab="home"   id="homeTrayClick" data-transition="slide" data-ajax="true">
										<div class='item'>
												<span class='title'>Home</span>
										</div>
								</a>
								<div id="homeTray"></div>
							</li>
							<li>
								<a class='icon life' data-transition='slide' data-ajax='true'></a>
								<a href="life/index.html" data-tab="life" data-transition="slide" data-ajax="true"  id="lifeTrayClick">
										<div class='item'>
												<span class='title'>Life</span>
										</div>
								</a>
								<div id="lifeTray"></div>
							</li>
						</ul>
					</nav>
				<nav class="quickLink">
					<ul>
						<li>
							<a class='icon contactUs' data-transition='slide' data-ajax='true'></a>
							<a href="common/contactMetLifeLanding.html"  id="contactTrayClick" data-tab="contactUs" data-transition="slide" data-ajax="true">
									<div class='item'>
											<span class='title'>Contact Us</span>
									</div>
							</a>
						</li>
						<li>
							<a class='icon policy' data-transition='slide' data-ajax='true'></a>
							<a href="#policy" data-tab="myPolicy"  id="myPolicyTrayClick" onclick="selectAccountSelection();">
									<div class='item'>
											<span class='title'>My Policy Info</span>
									</div>
							</a>
						</li>
						<li>
							<a class='icon rateapp' data-transition='slide' data-ajax='true'></a>
							<a id="lnkRateApp" data-tab="rateApp" data-transition="slide" data-ajax="true">
									<div class='item'>
											<span class='title'>Rate Our App</span>
									</div>
							</a>
						</li>
						<li>
							<a class='icon feedback' data-transition='slide' data-ajax='true'></a>
							<a id="feedbackTrayClick" target="_blank">
									<div class='item'>
											<span class='title'>Feedback</span>
									</div>
							</a>
						</li>
					</ul>
			</nav>
		   </div >
		
				<footer>
					<div class='horizontal'>
						<div>
							<a id="mobileSiteTrayClick" data-transition="slide"
								data-ajax="true" class="left">View Mobile Site</a>
						</div>
						<div>
							<span id="versionContainer"></span>
						</div>
					</div>
					<div class='vertical'>
						<div>
							<a href="common/termsConditions.html" data-tab="legal"
								id="termsTrayClick" data-transition="slide" data-ajax="true">
								<span>Legal</span> </a> <span class="textseparator">&nbsp;.</span> <a
								data-tab="privacy" data-transition="slide"
								data-ajax="true" id="privacyTrayClick"
								onclick="invokeLandingPage('trayList.html','../common/privacyPolicy.html');">
								<span>Privacy</span> </a>
						</div>
						<div class='copyright'>
							<span>&copy; 2012 MetLife, Inc.</span> <span>&copy; 2012
								PNTS.</span><br /> <span> L0812276994 (exp0814) [All States]</span>
						</div>
					</div>
				</footer>
			</div>
		</div>
	</div>
	
	
	![alt text][traylist]

[traylist]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/traylist.png "Logo Title Text 2"