
<!DOCTYPE html>

<html>
<head>
  	
</head>
<body>

<div class="redbox margin3 arial ">
	<div class="parent">
		<div class="div1">
			<div class="blackbox margin3 arial centre">
            <h1>London</h1>
            </div>
            </div>
            
		<div class="div2">
			<div class="blackbox margin3 arial centre">
            <h1>London</h1>
            </div>
            </div>
            
		<div class="div3"> </div>
		<div class="div4"> </div>
		<div class="div5"> </div>
		<div class="div6"> </div>
		<div class="div7"> </div>
		<div class="div8"> </div>
		<div class="div9"> </div>
			</div>
			</div>
	  	
<div class="redbox margin arial ">

        <div class="blackbox margin2 arial centre">
            <h1>London</h1>
            </div>
        <div class="blackbox margin3 arial ">
            <h2>London is the capital of England.</h2>
            </div>
        <div class="blackbox margin3 arial ">
            <p>London is the capital of England.</p>
            </div>
    </div> 


  <script type="text/javascript">
    	
  </script>

  <style type="text/css">
  
.parent {
display: grid;
grid-template-columns: repeat(3, 1fr);
grid-template-rows: repeat(3, 1fr);
grid-column-gap: 0px;
grid-row-gap: 0px;
}

.div1 { grid-area: 1 / 1 / 2 / 2; }
.div2 { grid-area: 1 / 2 / 2 / 3; }
.div3 { grid-area: 1 / 3 / 2 / 4; }
.div4 { grid-area: 2 / 1 / 3 / 2; }
.div5 { grid-area: 2 / 2 / 3 / 3; }
.div6 { grid-area: 2 / 3 / 3 / 4; }
.div7 { grid-area: 3 / 1 / 4 / 2; }
.div8 { grid-area: 3 / 2 / 4 / 3; }
.div9 { grid-area: 3 / 3 / 4 / 4; }  
  
  
    	.redbox {
		    background-color: tomato;
		    color: black;
		
		}
		
		.blackbox {
		    background-color: black;
		    color: white;
		
		}
		
		    .margin {
		        margin: 20px;
		        padding: 35px;
		    }
		    
		    .margin2 {
		        margin: 10px;
		        padding: 5px;
		    }
		
		    .margin3 {
		        margin: 5px;
		        padding: 5px;
		    }
		
		
		.arial {
		    font-family: Arial; 
		}
		
		.centre {
		    text-align: center;
		}
		
		
		h1 {
		  font-size: 40px;
		}
		
		h2 {
		  font-size: 30px;
		}
		
		p {
		  font-size: 14px;
		}
  </style>
</body>
</html>
