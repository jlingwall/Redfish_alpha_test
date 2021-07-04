---
layout: default
title: Clue 2
---
 
<h1>Watch each video to find the clues that will lead you to your destination:</h1>

<p>(Note, click "Submit" to check your answers. You may need to scroll down the page as you submit answers to see the results.)</p>



<iframe width="560" height="315" src="https://www.youtube.com/embed/5F_dglZFboI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/cDqADZygseM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/IjZ5cqdDksA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



            
 
<p>Where is this clue taking you?
</p>




<div class='wrapper'>
			<form id='nameForm1'>
						<div class='form-uname'>
						    <label id='nameLable1' for='nameField1'></label>
						    <input id='nameField1' type='text' maxlength='25'>
						</div>
						<div class='form-sub'>
						    <button id='subButton1' type='button'>Submit</button>
						</div>
			</form>

			<div>
			    <p id='result1'></p>
			</div>
</div>


<script type="text/javascript">
				  var solved1 = 0;

				function createLink(linkExtension) {

				  const balanceDiv = document.createElement("div");
				  const symbolSpan = document.createElement("span");
				  const link = document.createElement("a");

				  link.setAttribute('href', `https://docs.google.com/forms/d/e/1FAIpQLSeiX5A9Ru63ItlfnU3pDgtuzXNab3f9809VxwR_8u23XIm6Uw/viewform?usp=sf_link`);
				  link.textContent = 'Take a selfie in front of a J. Dawgs location and then upload at this link.';
				  symbolSpan.appendChild(link);
				  balanceDiv.appendChild(symbolSpan);
				  document.body.appendChild(balanceDiv);
				}

				  function getUserName1() {
				    var nameField = document.getElementById('nameField1').value;
				    var result1 = document.getElementById('result1');

				    if (nameField != "J Dawgs" && nameField != "J. Dawgs" && nameField != "j dawgs" && nameField != "j. dawgs") {
				        result1.textContent = 'Keep trying ...';
				        //alert('Username must contain at least 1 characters');
				    } else {
				        // result1.textContent = 'Correct!' + "Take a selfie on bended knee with the Falls in the background.";
				              result1.textContent = createLink('myparam');
				        solved1 = 1;
				        //alert(nameField);
				    }
				    }
				    var subButton1 = document.getElementById('subButton1');
				    subButton1.addEventListener('click', getUserName1, false); 

</script>


<button onclick="Hint1()" >Hint?</button>
<div id="Hint1">
    	<div>
				    We used to get our snack at the little red shack. <p></p>

<button onclick="Hint1b()" >Another?</button>
				 <div id="Hint1b"><div>
				  Jason grills 'em up fresh south of campus.
</div>
</div>
</div>

<script type="text/javascript">
		  document.getElementById("Hint1").style.display = "none";
</script>

<script>
		function Hint1() {
		  var x = document.getElementById("Hint1");
		  if (x.style.display === "none") {
		    x.style.display = "block";
		  } else {
		    x.style.display = "none";
		  }
		}
		  document.getElementById("Hint1b").style.display = "none";
		  function Hint1b() {
		    var x = document.getElementById("Hint1b");
		    if (x.style.display === "none") {
		      x.style.display = "block";
		    } else {
		      x.style.display = "none";
		    }
		  }
</script>


