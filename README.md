<!--created by prashant shukla-->
<!DOCTYPE html>
<html>
    <head>
        <title>AI PING PONG GAME</title>
 
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
     
        <link rel="stylesheet" href="style.css">
        <script src="https://unpkg.com/ml5@0.4.3/dist/ml5.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.0.0/p5.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.0.0/addons/p5.sound.min.js"></script>   
    </head>
    <body background="background.jpg">
        <center>

            <div class="btn btn-warning heading">
              <h3>AI PING PONG GAME </h3>
              <button class="btn btn-warning"  data-toggle="modal" data-target="#myModal">Instruction</button>
            </div>
      
            <br><br>
            <button class="btn btn-success" onclick="startGame()" id="start">Play Game</button>
            <br><br>
            <h3 id="status" class="btn btn-default"></h3>
            <br><br>
            <div id="canvas"></div>
            <br><br>
            <button onclick="restart()" class="btn btn-danger" id="restart">Restart</button>
            <br><br>
            
            <h4>Developed By :AdityaNathMishra</h4>
        
            <div id="myModal" class="modal fade ">
              <div class="modal-dialog" >
                <!-- Modal content-->
                <div class="modal-content">
            
                  <div class="modal-header">
                    <button class="close" data-dismiss="modal">&times;</button>
                    <h3>Instructions</h#>
                  </div>
            
                   <div class="modal-body">
                       <ol>
                           <li>First keep your laptop screen straight</li>
                           <li>Move yourself approximately 3-4 feet away from the laptop</li>
                           <li>Move your right wrist in an ascending and decending manner, a red dot should appear on your right wrist</li>
                           <li>Now press the play button, and again move yourself 3-4 feet away from laptop</li>
                           <li>The red paddel is your paddel, that will move as per the movement of your right wrist</li>
                       </ol>
                    </div>
      
                </div>
              </div>
            </div>
      </center>

<script src="main.js"></script>
</body>
</html>
