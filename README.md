Code die ik zelf niet heb geschreven (ik heb er wel zelf enkele aanpassingen aan gebracht):
gevonden op w3school https://www.w3schools.com/howto/howto_js_mobile_navbar.asp
		<!-- Simulate a smartphone / tablet look -->
				<div class="mobile-container">
					<!-- Top Navigation Menu -->
					<div class="topnav">
						<a href="#home" class="active"></a>
						<div id="myLinks">
							<a href="index.html">Homepage</a>
							<a href="about-me.html">About me</a>
							<a href="cv.html">CV</a>
						</div>
						<a href="javascript:void(0);" class="icon" onclick="myFunction()">
							<i class="fa fa-bars"></i>
						</a>
					</div>
					<!-- End smartphone / tablet look -->
				</div>
                	<script>
			function myFunction() {
			  var x = document.getElementById("myLinks");
			  if (x.style.display === "block") {
				x.style.display = "none";
			  } else {
				x.style.display = "block";
			  }
			}
			</script>
            body {
		font-family: Arial, Helvetica, sans-serif;
	  }
	  
	  .mobile-container {
		display: block;
		grid-column: 8/13;
		grid-row: 1/5;
		max-width: 480px;
		margin: auto;
		height: 500px;
		color: white;
		border-radius: 10px;
	  }
	  
	  .topnav {
		overflow: hidden;
		background-color: #186289;
		position: relative;
	  }
	  
	  .topnav #myLinks {
		display: none;
	  }
	  
	  .topnav a {
		float: left;
		color: antiquewhite;
		padding: 14px 16px;
		text-decoration: none;
		font-size: 17px;
	  }
	  
	  .topnav a.icon {
		float: right;
	  }
	  
	  .topnav a:hover {
		background-color: #0d87c4;
		color: black;
}

foto's komen van pinterest
board:
https://pin.it/6LPRvTrOq

