<!DOCTYPE html>
<html>
    <head>

        <meta charset="utf-8">

        <title>Internet_TV</title>
        <!-- Latest compiled and minified CSS -->
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

        <!-- jQuery library -->
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

        <!-- Popper JS -->
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>

        <!-- Latest compiled JavaScript -->
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script> 
        <link href="https://unpkg.com/video.js/dist/video-js.css" rel="stylesheet">
        <link href="css/style.css" rel="stylesheet">

        <!--[if lt IE 9]>
                <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
                <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
        <![endif]-->

        <script type="text/javascript" src="js/clappr.min.js"></script>
        <link href="css/custom.css" rel="stylesheet">
        <script type="text/javascript" src="js/clappr-chromecast-plugin.min.js"></script>
        <style class="clappr-style">
            @font-face{font-family:Roboto;font-style:normal;font-weight:400;src:local("Roboto"),local("Roboto-Regular"),url(https://cdn.jsdelivr.net/npm/clappr@latest/dist/38861cba61c66739c1452c3a71e39852.ttf) format("truetype")}
            body {
                background: #000 url(img/bgu.jpg) top center;
            }
        </style>
    </head>
    <body>

        <div class="container-fluid">
            <div class="row justify-content-center" style="margin-top: 50px;">

                <div class="col-12 col-lg-8">
                    <div class="embed-responsive embed-responsive-16by9">
                        <div id="player" class="embed-responsive-item">
                            <video id="vid1" class="video-js vjs-default-skin vjs-fluid" poster="http://i.imgur.com/xxqm7EE.png" width="640" height="360" controls autoplay preload="none" data-setup='{ "techOrder": ["html5", "flash", "youtube"], "sources": [{ "type": "application/x-mpegURL", "src": "https://nmxlive.akamaized.net/hls/live/529965/Live_1/index.m3u8"}]}'></video>
                        </div>
                    </div>
                </div>

                
                  
                </div>

            </div>
        </div>

<a href="https://www.hitwebcounter.com" target="_blank">
<img src="https://hitwebcounter.com/counter/counter.php?page=7853127&style=0009&nbdigits=5&type=page&initCount=0" title="Free Counter" Alt="web counter"   border="0" /></a>                                     

        <script src="https://unpkg.com/video.js@7.10.2/dist/video.js"></script>
        <script src="https://unpkg.com/@videojs/http-streaming@2.4.2/dist/videojs-http-streaming.min.js"></script>
        <script src="js/scripts.js"></script>

    </body>
</html>

