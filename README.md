<!DOCTYPE html>
<html>
	<head>
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
		<script>
			$(document).ready(function(){
				$("#hide").click(function(){
					$("p").hide();
				});
				$("#show").click(function(){
				$("p").show();
				});
			});
		</script>
	</head>


	<body>
		<p>Со стискање на копчето "Исчезни" - ќе исчезнам. За повторна моја појава - стисни "Појави се".</p>

		<button id="hide">Исчезни</button>
		<button id="show">Појави се</button>
	</body>

</html>
