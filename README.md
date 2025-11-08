# How-to-play-Yuzu-Games-Online
How to play Yuzu Games Online with "Local Multiplayer"

ESPAÑOL
Cómo jugar Juegos Online en Yuzu - Por BeNach0 (Discord)
====================================================

1. Anda a Yuzu y en "Archivo" selecciona "Abrir Carpeta de Yuzu"
2. Anda a la carpeta "config" y edita el archivo "qt-config.ini"
3. En la sección [WebService] reemplaza:

	web_api_url\default=true
	web_api_url=https:/api.yuzu-emu.org
	
	por:
	
	web_api_url\default=false
	web_api_url=api.ynet-fun.xyz
	
4. Vuelve a Yuzu y anda a Emulación y selecciona Configurar
5. En "Sistema" anda a la Ventana "Red" y en "Interfaz de Red" selecciona Wi-Fi o Ethernet dependiendo de tu red.
6. Antes de abrir el juego, anda al ícono de dos monitores que sale en la esquina derecha abajo en Yuzu,
   en "Apodo" pon el que tu quieras y dale doble click a cualquier sala pública (sin candado) 
   que tenga una cantidad de jugadores máximos que cumpla con tus requerimientos
   (Las personas que jueguen contigo tendrán que conectarse a la misma sala).
7. Abre tu juego y selecciona Multijugador LOCAL (no funciona con otro tipo).

Si te sale el error de red 2306-0520, haz los siguientes pasos:
===============================================================
1. Dale click derecho a tu juego en Yuzu y dale a "Abrir ubicación de los mods"
2. Abre el archivo "Force.Network.Available.zip" y copia la carpeta dentro del zip a la carpeta que abrió Yuzu.

MOD por: Jason en https://github.com/theboy181
Link Original: https://github.com/kinnay/SMB35/issues/5#issuecomment-851696099

ENGLISH
How to play Games Online in Yuzu - By BeNach0 (Discord)
====================================================

1. Go to Yuzu, in "File" select "Open Yuzu Folder"
2. Go to "config" folder and edit "qt-config.ini" file
3. In the [WebService] section replace the following:

	web_api_url\default=true
	web_api_url=https:/api.yuzu-emu.org
	
	with:
	
	web_api_url\default=false
	web_api_url=api.ynet-fun.xyz
	
4. Go back to Yuzu, go to "Emulation" and select "Configure"
5. In "System" go to the "Network" window, and in "Network Interface" select Wi-Fi or Ethernet according to your network connection.
6. Before opening a game, go to the two monitor icon in the bottom right corner in Yuzu,
   in "Nickname" choose on of your liking and double click on any public room (the ones without a lock) 
   that has a maximum player quantity according to your requirements
   (The players that play with you have to connect to the same room).
7. Open your game and select LOCAL multiplayer (it shouldn't work with any other online mode).

If you get the network error: 2306-0520, do the following steps:
===============================================================
1. Right click your game in Yuzu and click "Open Mod Data Location"
2. Open the zip file "Force.Network.Available.zip" and copy the folder inside of it to the folder that Yuzu opened.

MOD by: Jason at https://github.com/theboy181
Original Link: https://github.com/kinnay/SMB35/issues/5#issuecomment-851696099
