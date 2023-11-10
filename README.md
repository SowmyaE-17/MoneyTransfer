<!DOCTYPE html>

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Video Call & Chat</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="css/style.css">
    <script src="https://kit.fontawesome.com/6510466b6c.js" crossorigin="anonymous"></script>

</head>

<body>
    <navbar>
        <div class="logo">Video Conferencing</div>
    </navbar>
    <!-- <div class="landing"> -->
        <!-- <div class="head-cont unselectable">
            Welcome to QuickMeet!
        </div> -->

        <div class="main">
            <div class="create-join">
                <div class="text"><div class="head">Quick Video Meetings with Whiteboard.</div>
                <div class="subtext">Instant Login. No Sign Ups.</div>
                </div>
                <button id="createroom" class="createroom-butt unselectable">Create Room</button><br>
                <input type="text" name="room" spellcheck="false" placeholder="Enter Room Code" id="roomcode" class="roomcode"><br>
                <div class="joinroom unselectable" id="joinroom">Join Room</div>
            </div>
            <div class="video-cont">
                <video class="video-self" autoplay muted playsinline></video>
                <div class="settings">
                    <div class="device" id="mic"><i class="fas fa-microphone"></i></div>
                    <div class="device" id="webcam"><i class="fas fa-video"></i></div>
                </div>
            </div>
        </div>

        <!-- <div class="main-cont">

            <form class="roomform" action="room.html" method="GET">
                <div class="formcont">
                    <input type="text" name="name" placeholder="Enter your name" id="username" class="inputtext"><br>
                    
                    <button type="submit" class="butt unselectable" id="joinroom">Join Room</button>
                    
                </div>
            </form>

        </div> -->

    <!-- </div> -->

    <script src="js/landing.js"></script>
</body>

</html># MoneyTransfer
