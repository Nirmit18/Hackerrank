<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        
            #d1{
                border: 8px solid black;
                border-radius: 10px;
                height: 800px;
                width: 60% ;
                margin: auto;
                margin-top: 20px;
                background-color:rgba(255, 255, 255, 0.992);

            }
        
        #ima{
            width: 200px;
            height: 200px;
            border: 6px solid black;
            margin:31px 350px;
            position: relative;

            
        }
        #ima::before{
            content: '';
            border: 6px solid red ;
            width: 100%;
            height: 100%;
            position: absolute;
            z-index: 1;
            top: 3px;
            left: 2px;
            background-image: url(kcc.itm.png);

        }
        #d2{
            font-family: Cambria;
            margin: auto;
            font-size: 38px;
             text-align: center
        }
    </style>
</head>
<body>
    <div id="d1">
        <div id="ima"></div>
        <div id="d2">
                    <h3>NAME-NIRMIT KAUNDAL</h3>
                    <h3>ROLL NO.-2104920100085</h3>
                    <h3>SECTION-'B'</h3>
                    <h3>SUBJECT-DATA STRUCTURE & ALGORITHM</h3>
    
    
        </div>
    </div>
   
</body>
</html>
