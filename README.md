<!DOCTYPE HTML>
<html>
    <head>
        <meta charset='utf8'>
    </head>
    <body>
        <div id='ruffle'></div>
        <script src='https://unpkg.com/@ruffle-rs/ruffle'></script>
        <script>
var swfobject = {};

swfobject.embedSWF = function(url, cont, width, height){
    var ruffle = window.RufflePlayer.newest(),
        player = Object.assign(document.getElementById(cont).appendChild(ruffle.createPlayer()), {
            width: width,
            height: height,
            style: 'width: ' + width + 'px; height: ' + height + 'px',
        });
    
    player.load({ url: url });
}

swfobject.embedSWF('https://carterbell69.github.io/flashgames/bloxors.swf', 'ruffle', 500, 500);
        </script>
    </body>
</html>
Flash Games
