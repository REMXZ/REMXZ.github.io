<!DOCTYPE html>
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

        <title>REM'S HUB</title>

        
		<link rel="shortcut icon" type="image/x-icon" href="https://i.ibb.co/XDnCYJh/download-discord-server-icon-57.png">

		<meta name="author" content="REM'S HUB">
		<meta name="description" content="REM'S HUB">
		<meta name="keywords" content="Roblox, Roblox Hack, script, lua, krnl, REM'S HUB">

		<meta property="og:title" content="REM'S HUB">

        <style>
            body {
				background-color: rgb(25, 25, 25);
                color: white;
                font-family: "Trebuchet MS";
                background-image: url(https://images5.alphacoders.com/862/thumb-1920-862186.jpg);
				background-attachment: fixed;
				background-size: cover;
				background-repeat: no-repeat;
			}

            body::-webkit-scrollbar {
                width: 12px;
            }
      
            body::-webkit-scrollbar-thumb {
                background-color: rgb(80, 80, 80);
            }

            #owlImage {
                margin-top: 20px;
                height: 90px;
            }

            #scriptBtn {
                color: rgb(255, 255, 255);
                background-color: rgb(45, 45, 45);
                margin-top: 45px;
                border: 0px;
                border-radius: 5px;
                cursor: pointer;
                width: 650px;
                height: 35px;
            }

            #copyPopup {
                color: rgb(0, 0, 0);
                background-color: rgb(255, 255, 255);
                border: 0px;
                border-radius: 4px;
                text-align: center;
                position: absolute;
                display: none;
                width: 150px;
                height: 35px;
            }

            #gamesBtn {
                background-color: rgb(45, 45, 45); 
                color: rgb(255, 255, 255); 
                font-size: large; 
                border: 0px; 
                border-radius: 2px;
                cursor: pointer; 
                width: 100px; 
                height: 50px;
            }

            #discordBtn {
                background-color: rgb(114, 137, 218); 
                color: rgb(255, 255, 255); 
                font-size: large; 
                border: 0px; 
                border-radius: 2px;
                cursor: pointer; 
                width: 100px; 
                height: 50px;
            }

            #detailLine {
                margin-top: 45px;
                border: 1px solid rgb(53, 160, 204);
                width: 500px;
                height: 0px;
            }

            #copyBtn:hover {
                background-color: rgb(70, 70, 70);
            }
        </style>
    </head>
    <body>
        <input type="text" value="COPIED!" readonly="" id="copyPopup" style="display: none;">
        <center>
            <br>
            <br>
            <br>
            <button id="scriptBtn"><span style="color: rgb(78, 153, 204);">loadstring</span>(game:<span style="color: rgb(78, 153, 204);">HttpGet</span>(<span style="color: rgb(80, 179, 179);">"</span><span style="color: rgb(11, 194, 240);">https://raw.githubusercontent.com/REMXZ/MAIN/master/LOAD</span><span style="color: rgb(53,204,204);">"</span>))();</button>
            <br>
            <div id="detailLine"></div>
            <br>
            <h1 style="font-family: monospace;">Supportd Exploits</h1>
</a><br><a href="https://greenman.ga/files/trustedexploits.html" target="_blank" style="color: rgb(180, 180, 180);">PAID EXPLOITS</a></i>
            <div id="detailLine"></div>
            <br>
            <h1 style="font-family: monospace;">GAME LIST</h1>
            <button id="gamesBtn">VIEW</button>
            <div id="detailLine"></div>
            <br>
            <h1 style="font-family: monospace; color: rgb(114, 137, 218);">NEED KEY? </h1>
            <button id="discordBtn">JOIN</button>
            <br>
            <br>
            <br>
        </center>

        <script type="text/javascript">
            const scriptBtn = document.getElementById("scriptBtn");
            const copyPopup = document.getElementById("copyPopup");
            const gamesBtn = document.getElementById("gamesBtn");
            const discordBtn = document.getElementById("discordBtn");

            scriptBtn.addEventListener("click", () => {
                const scriptBox = document.createElement("textarea");
                scriptBox.value = ' _G.Key = "ENTERKEYHERE" _G.REDUCELAG = true loadstring(game:HttpGet("https://raw.githubusercontent.com/REMXZ/MAIN/master/LOAD"))();';
                document.body.appendChild(scriptBox);
                scriptBox.select();
                document.execCommand("copy");
                document.body.removeChild(scriptBox);
                copyPopup.style.display = "block";
                setTimeout(() => {copyPopup.style.display = "none";}, 1000);
            });

            gamesBtn.addEventListener("click", () => {
                window.open("https://ghostbin.co/paste/g8nmv/raw");
            });

            discordBtn.addEventListener("click", () => {
                window.open("https://discordservers.me/servers/692392883956875326");
            });
    </script>

</body></html>
