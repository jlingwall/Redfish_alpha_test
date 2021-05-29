---
layout: default
title: Test
---
 
<h1><i>This riddle is unlocked with a three-digit pin.<br> Each digit corresponds to the first number<br> of the street address of a historic building in Provo, UT. </i></h1>



<!-- FIRST CLUE START -->

 
<p>David's father, medieval Warrior,<br> 
Now his picture hangs in the corridor.
</p>


<div class='wrapper'>
<form id='nameForm1'>
<div class='form-uname'>
    <label id='nameLable1' for='nameField1'></label>
    <!-- <input id='nameField1' type='text' maxlength='15'></input> -->
</div>
<div class='form-sub'>
    <!-- <button id='subButton1' type='button'>Submit</button> -->
</div>
</form>

<div>
    <p id='result1'></p></div>
</div>


<script type="text/javascript">
	var solved1 = 0;
	function getUserName1() {
		var nameField = document.getElementById('nameField1').value;
		var result1 = document.getElementById('result1');

		if (nameField != "1" && nameField != "One" ) {
		    result1.textContent = 'Keep trying ...';
		    //alert('Username must contain at least 1 characters');
		} else {
		    result1.textContent = 'Correct!' + "";
		    solved1 = 1;
		    //alert(nameField);
		}
		}
		var subButton1 = document.getElementById('subButton1');
		subButton1.addEventListener('click', getUserName1, false); 

</script>


<button onclick="Hint1()" >Hint?</button>
		<div id="Hint1"><div>
		Pay attention to capital letters <br>

<button onclick="Hint1b()" >Another?</button>
		<div id="Hint1b"><div>
		Have you heard of the Victorian Mansions of Provo?
</div>
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





<!-- FIRST CLUE END -->




<!-- SECOND CLUE START -->
<p></p>
<p>I’ll give beauty for ashes, and garments for praise,<br>
while Mr. Taft speaks and then Sergei plays. 
</p>



<div class='wrapper'>
<form id='nameForm2'>
<div class='form-uname'>
    <label id='nameLable2' for='nameField2'></label>
    <!-- <input id='nameField2' type='text' maxlength='40'></input> -->
</div>
<div class='form-sub'>
    <!-- <button id='subButton2' type='button'>Submit</button> -->
</div>
</form>

<div>
    <p id='result2'></p></div>
</div>




<script type="text/javascript">
	var solved2 = 0;
	function getUserName2() {
		var nameField = document.getElementById('nameField2').value;
		var result2 = document.getElementById('result2');

		if (nameField != "5" && nameField != "Five" ) {
		    result2.textContent = 'Keep trying ...';
		    //alert('Username must contain at least 2 characters');
		} else {
		    result2.textContent = 'Correct!' + "";
		    solved2 = 1;
		    //alert(nameField);
		}
		}
	var subButton2 = document.getElementById('subButton2');
	subButton2.addEventListener('click', getUserName2, false); 
</script>




<button onclick="Hint2()" >Hint?</button>
<p></p>
<div id="Hint2">
		<div><!--div that we want to hide-->
<a href="https://youtu.be/bUpeGr55ad0">Listen in!</a><br>

<button onclick="Hint2b()" >Another?</button>
<p></p>
<div id="Hint2b">
		<div><!--div that we want to hide-->
Beauty <i>from</i> ashes in the City Center. <p></p>

</div>
</div>
</div>
</div>

<script type="text/javascript">
    document.getElementById("Hint2").style.display = "none";
	function Hint2() {
	  var x = document.getElementById("Hint2");
	  if (x.style.display === "none") {
	    x.style.display = "block";
	  } else {
	    x.style.display = "none";
	  }
	}
	document.getElementById("Hint2b").style.display = "none";

function Hint2b() {
  var x = document.getElementById("Hint2b");
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}
</script>

<!-- SECOND CLUE END -->

<!-- THIRD CLUE START -->


<p></p>
<p>
Cobblers, cobblestones, a Rock like a saint,<br>
Start at the book place, even if quaint,<br>
And then whither you go, or Whence you came,<br>
Keep spending your shoe-leather--conquer the game.
</p>


<div class='wrapper'>
<form id='nameForm3'>
<div class='form-uname'>
    <label id='nameLable3' for='nameField3'></label>
    <!-- <input id='nameField3' type='text' maxlength='40'></input> -->
</div>
<div class='form-sub'>
    <!-- <button id='subButton3' type='button'>Submit</button> -->
</div>
</form>

<div>
    <p id='result3'></p></div>
</div>

<script type="text/javascript">
	var solved3 = 0;
	function getUserName3() {
	var nameField = document.getElementById('nameField3').value;
	var result3 = document.getElementById('result3');


	if (nameField != "5" && nameField != "Five" ) {
	    result3.textContent = 'Keep trying ...';
	    //alert('Username must contain at least 3 characters');
	} else {
	    result3.textContent = 'Correct!' + "";
	        solved3 = 1;

	    //alert(nameField);
	}
	}
var subButton3 = document.getElementById('subButton3');
subButton3.addEventListener('click', getUserName3, false); 
</script>


<button onclick="Hint3()" >Hint?</button>

<div id="Hint3">
		<div><!--div that we want to hide-->
Two capital letters misplaced may appear to show you the names you want to hear. <p></p>

<button onclick="Hint3b()" >Another?</button>

<div id="Hint3b">
		<div><!--div that we want to hide-->
Look for a two-story salt-box residence across from the library.
</div>
</div>
</div>
</div>


<script type="text/javascript">
	 document.getElementById("Hint3").style.display = "none";
	function Hint3() {
	  var x = document.getElementById("Hint3");
	  if (x.style.display === "none") {
	    x.style.display = "block";
	  } else {
	    x.style.display = "none";
	  }
	}

	document.getElementById("Hint3b").style.display = "none";

	function Hint3b() {
	  var x = document.getElementById("Hint3b");
	  if (x.style.display === "none") {
	    x.style.display = "block";
	  } else {
	    x.style.display = "none";
	  }
	}
</script>


<!-- THIRD CLUE END -->





<!-- START OVERALL ANSWER -->


<div> <h1 id='overallresult'></h1>


<div id="theAnswer">


Submit your three-digit pin below.
			<div class='wrapper'>
			

			<form id='nameForm5'>
				<div class='form-uname'>
				    <label id='nameLable5' for='nameField5'></label>
				    <input id='nameField5' type='text' maxlength='40'></input>
				</div>
				<div class='form-sub'>
				    <button id='subButton5' type='button'>Submit</button>
				</div>
				
			</form>

			<div>
			    <p id='result5'></p></div>
			</div>

</div> 

	<!-- <button onclick="Hint5()" >Hint?</button> -->
	<div id="Hint5">
			<div><!--div that we want to hide-->
	<!-- Overall hint 1 -->
<p></p>
<!-- <button onclick="Hint5b()" >Another?</button> -->
	<div id="Hint5b">
			<div><!--div that we want to hide-->
	<!-- Overall hint 2 -->

	</div>
	</div>
	<script type="text/javascript">
	  document.getElementById("Hint5").style.display = "none";
	function Hint5() {
	  var x = document.getElementById("Hint5");
	  if (x.style.display === "none") {
	    x.style.display = "block";
	  } else {
	    x.style.display = "none";
	  }
	}
	  document.getElementById("Hint5b").style.display = "none";
	function Hint5b() {
	  var x = document.getElementById("Hint5b");
	  if (x.style.display === "none") {
	    x.style.display = "block";
	  } else {
	    x.style.display = "none";
	  }
	}
		// var solved5 = 0;

		function getUserName5() {
	var nameField = document.getElementById('nameField5').value;
	var result5 = document.getElementById('result5');


function createLink(linkExtension) {

  const balanceDiv = document.createElement("div");
  const symbolSpan = document.createElement("span");
  const link = document.createElement("a");

  link.setAttribute('href', `https://sites.google.com/view/june5utahcounty2b3ks7/home`);
  link.textContent = 'You solved the puzzle. Amazing. Click here to continue.';
  symbolSpan.appendChild(link);
  balanceDiv.appendChild(symbolSpan);
  document.body.appendChild(balanceDiv);
}



	if (nameField != "155" && nameField != "One Five Five" ) {
		if (nameField == "Close" || nameField == "close" || nameField == "so close"){
		result5.textContent = "Close.";
	}
		else {

	    result5.textContent = 'Keep trying ...';}
	    //alert('Username must contain at least 3 characters');
	} else {
	    // result5.textContent = <a href="https://sites.google.com/view/june5utahcounty2b3ks7/home">You solved the puzzle!! Amazing. Click here to continue</a>;
	    result5.textContent = createLink('myparam');
	    // solved5 = 1;
	    //alert(nameField);
	}
	}
	var subButton5 = document.getElementById('subButton5');
	subButton5.addEventListener('click', getUserName5, false); 

	</script>

</div>
</div>
</div>
</div>
</div>



<script type="text/javascript">

	// function demoDisplay() {
	  document.getElementById("theAnswer").style.display = "block";
	// }

		function getoverallsolution() {
			var overallresult = document.getElementById('overallresult');
			// solved1 = 1;
			// solved2 = 1;
			// solved3 = 1;
			// solved4 = 1;
	if (1 == 1) {
		overallresult.textContent =  "Enter your three-digit pin below.";
		   document.getElementById("theAnswer").style.display = "block";

	}

	}

	// subButton1.addEventListener('click', getoverallsolution, false); 
	// subButton2.addEventListener('click', getoverallsolution, false); 
	// subButton3.addEventListener('click', getoverallsolution, false); 
	// subButton4.addEventListener('click', getoverallsolution, false); 

</script>

<!-- END OVERALL ANSWER -->
