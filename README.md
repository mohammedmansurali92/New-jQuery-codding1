# New-jQuery-codding1
<script>
		$(document).ready(function(){
			$("#btn1").click(function(){
				$("p").prepend("<b>Prepend text</b>");
			});
			$("#btn2").click(function(){
				$("ol").prepend("<li>Prepend List Item</li>");
			});
		});
	</script>
	</head>
	<body>
    <p>This is a paragraph</p>
    <p>This is a another paragraph</p>
    <ol>
    	<li> list item 1</li>
    	<li>List item 2</li>
    	<li>List item 3</li>
    </ol>
    <button id="btn1">Prepend text</button>
    <button id="btn2">Prepend list item</button>
