# Nasıl Kurulur?

Alttaki kodda yazan fivemip bölümlerine Sunucu ipnizi ts3ip yazan yerlere kendi ts3 ipnizi yazmanız yeterli
```html
<html>

    <link rel="stylesheet" href="https://ygtdev.xyz">
    
    <meta property="og:title" content="YGT Development">
    <meta property="og:description" content="The easy way to get into the game.">
    <meta property="og:image" content="https://cdn.discordapp.com/attachments/693624858323583026/775307843183443999/logo_v2v2.png">
    <meta property="og:image:width" content="1000">
    <meta property="og:image:height" content="1000">
    <meta property="og:url" content="https://api.ygtdev.xyz">
    <meta property="og:site_name" content="api.ygtdev.xyz">
    <meta property="og:type" content="website">


    <head>
        <meta charset="UTF-8">
        <title>Sunucu İsmi</title> 
        <link rel="icon" href="favicon" type="image/png">
    </head>

    <body>

        <a href="fivem://connect/fivemip" class="button"></a>
        <a href="ts3server://ts3ip" class="button2" class="button2"></a>

    </body>


    <style> 

        body { 
            background: url(https://cdn.discordapp.com/attachments/767882860992397323/844130578453889064/back.png) no-repeat top center;
            -webkit-background-size: cover;
            -moz-background-size: cover;
            -o-background-size: cover;
            background-size: cover;
        }
        
        .button {
            background-color: transparent;
            background-repeat:no-repeat;
            border: none;
            cursor:pointer;
            overflow: hidden;
            outline:none;
            height: 75px;
            width: 300px;
            position: absolute;
            left: 27%;
            top: 42%;
            border-radius: 20px 20px 20px 20px;
        }

        .button2 {
            background-color: transparent;
            background-repeat:no-repeat;
            border: none;
            cursor:pointer;
            overflow: hidden;
            outline:none;
            height: 75px;
            width: 300px;
            position: absolute;
            left: 27%;
            top: 52%;
            border-radius: 20px 20px 20px 20px;
        }

    </style>
        

    <script>document.location='fivem://connect/fivemip'</script>

</html>
```
