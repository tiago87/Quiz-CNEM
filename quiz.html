<?php
   if( $_POST["name"] || $_POST["email1"] || $_POST["email2"] || $_POST["email3"] || $_POST["email4"] || $_POST["email5"] ) {
      

      	echo "Welcome ". $_POST['name']. "<br />";
      	echo "Welcome ". $_POST['email1']. "<br />";
      	echo "Welcome ". $_POST['email2']. "<br />";
      	echo "Welcome ". $_POST['email3']. "<br />";
      	echo "Welcome ". $_POST['email4']. "<br />";
      	echo "You are ". $_POST['email5'];
   } else {
   		header("Location: index.html");
		die();
   }
?>

<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>CNEM Quiz</title>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">

		<!-- MATERIAL DESIGN ICONIC FONT -->
		<link rel="stylesheet" href="fonts/material-design-iconic-font/css/material-design-iconic-font.min.css">
		
		<!-- STYLE CSS -->
		<link rel="stylesheet" href="css/style.css">

		<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js" type="text/javascript"></script>
	</head>

	<body>

		<div class="wrapper">
			<div class="inner">
				<form action="">
					<h3 id="numberTest"></h3>
					<p style="margin-bottom: 10px;"><label for="question">Questão: </label></p>
					<p style="margin-bottom: 10px;"><label><input type="radio" name="question1" value="2">Opção 1</input></label></p>
					<p style="margin-bottom: 10px;"><label><input type="radio" name="question1" value="1">Opção 2</input></label></p>
					<p style="margin-bottom: 30px;"><label><input type="radio" name="question1" value="0" checked="checked">Não sei/Não Respondo</input></label></p>
				</form>

				<h3 id="numberTimeleft"></h3>
				<div id="progressBar">
				  <div class="bar"></div>
				</div>
			</div>
		</div>
	</body>

	<script type="text/javascript">
		function progress(timeleft, timetotal, $element, questionNumber, totalOfQuestions) {
		    var progressBarWidth = timeleft * $element.width() / timetotal;
		    $element.find('div').animate({ width: progressBarWidth }, 500);
		    numberTimeleft.innerText = timeleft;
		    if(timeleft > 0) {
		        setTimeout(function() {
		            progress(timeleft - 1, timetotal, $element, questionNumber, totalOfQuestions);
		        }, 1000);
		    } else {

		    	var radios = document.getElementsByName('question1');

				for (var i = 0, length = radios.length; i < length; i++) {
				  if (radios[i].checked) {
				    //TODO: do whatever you want with the checked radio
				    //alert(radios[i].value);

				    // only one radio can be logically checked, don't check the rest
				    break;
				  }
				}
		    	if ( questionNumber < totalOfQuestions ) {
		    		numberTest.innerText = "Pergunta "+(questionNumber+1);
		    		progress(timetotal, timetotal, $element, (questionNumber+1), totalOfQuestions);
		    	} else {
					window.location.replace("submit.html");

		    		//TODO: Submeter as coisas...
		    		//TODO: Fazer o submit, sendo que para já apenas dá uma mensagem bonitinha a dizer participação registada com sucesso
		    	}
		    }
		};

		function letsPlay(numberOfQuestions, timePerQuestionInSeconds) {
			numberTest.innerText = "Pergunta 1";
			progress(timePerQuestionInSeconds, timePerQuestionInSeconds, $('#progressBar'),1,numberOfQuestions);
		}

		letsPlay(5, 5);
		
	</script>
</html>