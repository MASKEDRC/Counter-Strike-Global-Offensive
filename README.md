Zum Einfügen der Config + Video Settings einfach in folgenden Ordner kopieren:
C:\Program Files (x86)\Steam\SteamApps\common\Counter-Strike Global Offensive\csgo\cfg
Die Alte bitte vorher löschen, um sicher zu gehen.

Counter-Strike: Global Offensive Startparameter:
-high -32bit -dxlevel90 -novid  -tickrate128 -noborder -nointro -noforcemparms -noforcemaccel -noforcemspd

//VIDEO.TXT
"setting.mem_level" "2" > 	Dieser Befehl kann zu crashes beim Spielen führen.
							Wenn ja, einfach auf 0 stellen.



"setting.mat_queue_mode" "-1" > 	Dieser befehl setzt das Multicore-Rendering ein sofern er auf "2" steht.
									Nicht für CPUs mit schwachen Kernels geeignet.
									Dieser Befehl kann zu crashes beim Spielen führen.
									Wenn ja, einfach auf 0 stellen.

									
"setting.defaultres" "1920" > 			Auflösung Breite
"setting.defaultresheight" "1080" > 	Auflösung Höhe
"setting.aspectratiomode""1"	> 		16:9, falls ihr 4:3 wollte ändern in "0"
									
									
//CONFIG
Lade- Reihenfolge der Konfigurationsdateien
1. valve.rc
2. video.cfg
3. hud.cfg
4. sound.cfg
5. custom.cfg