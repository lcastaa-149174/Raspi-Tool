# Raspi-Tool
A Friendly Raspberry Pi Helper

This is the development map for the AQLabs Raspi-Tool Scrpit:


                                       Phase One - [Menu Elements]     **All menus go in the main file**
                                       -----------------------------------------------------------------


== Main Menu == [main.py] - main()
----------------------------------
1. Tools                      	 -> [main.py] - tools()       
2. Installs                   	 -> [main.py] - installs()
3. Extras    		      	 -> [main.py] - extras()
4. -exit-    		      	 -> exit()


== Tools Menu == [main.py] - tools()
-------------------------------------------------
1. Service Manager            	 -> [tools.py] - tools_service()
2. System Viewer              	 -> [tools.py] - tools_system()
3. Docker Manager             	 -> [tools.py] - tools_docker()


== Extras Menu == [main.py] - extras()
--------------------------------------
1. Minecraft Server Installer        -> [main.py] - extras_mci()
2. Crypto Miner Installer            -> [main.py] - extras_cmi()



++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

						Phase Two - [Tools Menu Functions] **Functions go with their respected block**
						-------------------------------------------------------------------------------


1. Service Manager                    -> [tools.py] - tools_service
---------------------------------------------------------------------
	- See Running Services          -> [tools.py] - service_status()
	- Stop, Start, Restart Services -> [tools.py] - service_tink
 

2. System Viewer                      -> [tools.py] - tools_system()
--------------------------------------------------------------------
	- RAM Checker                   -> [tools.py] - tools_ramcheck()
	- Storage Space Check           -> [tools.py] - tools_storcheck()
	- CPU Temp Check                -> [tools.py] - tools_cputemp()
	- CPU Load                      -> [tools.py] - tools_cpuload()

3. Docker Manager                     -> [tools.py] - tools_docker() 
---------------------------------------------------------------------
	- Container Manager		  -> [tools.py] - tools_container()
	- Image Puller			  -> [tools.py] - tools_image()
	- Volume Manager                -> [tools.py] - tools_volume()
	- Network Checker               -> [tools.py] - tools_network()


+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

						Phase Three - [Installs Menu Functions] **Functions go with thier respected blocks**
						------------------------------------------------------------------------------------

1. Apache2					  -> [installs.py] - installs_apache2()
2. NginX					  -> [installs.py] - installs_nginx()
3. Pi-Hole					  -> [installs.py] - installs_pihole()
4. Pi-Vpn					  -> [installs.py] - installs_pivpn()
5. Homebridge				  -> [installs.py] - installs_homeb()
6. Docker					  -> [installs.py] - installs_docker()
7. OMV					  -> [installs.py] - installs_omv()
8. Java					  -> [installs.py] - installs_java()
9. Git					  -> [installs.py] - installs_git()

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

						Phase Four - [Extras Menu Functions] **Functions go with thier respected blocks**
						---------------------------------------------------------------------------------

1. Minecraft Server Installer         -> [extras.py] - extras_mci()
2. Crypto Mining Software             -> [extras.py] - extras_cmi()



v.1.0 will contain a total of 
-------------------------------
 - 4 Core files
 - 32 differnet functions



