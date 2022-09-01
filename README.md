# Raspi-Tool
A Friendly Raspberry Pi Helper

This is the development map for the AQLabs Raspi-Tool Scrpit:
----------------------------------------------------------------------------------
Phase One - [Menu Elements]     **All menus go in the main file**


Main Menu  [main.py] - main()
Tools                      	 -> [main.py] - tools()       
Installs                   	 -> [main.py] - installs()
Extras    		      	 -> [main.py] - extras()
-exit-    		      	 -> exit()


Tools Menu  [main.py] - tools()
Service Manager            	 -> [tools.py] - tools_service()
System Viewer              	 -> [tools.py] - tools_system()
Docker Manager             	 -> [tools.py] - tools_docker()


Extras Menu  [main.py] - extras()
Minecraft Server Installer        -> [main.py] - extras_mci()
Crypto Miner Installer            -> [main.py] - extras_cmi()

--------------------------------------------------------------------------------


Phase Two - [Tools Menu Functions] **Functions go with their respected block**
						

Service Manager                    -> [tools.py] - tools_service
See Running Services          -> [tools.py] - service_stat
Stop, Start, Restart Services -> [tools.py] - service_tink
 

System Viewer                      -> [tools.py] - tools_system()
RAM Checker                   -> [tools.py] - tools_ramcheck()
Storage Space Check           -> [tools.py] - tools_storcheck()
CPU Temp Check                -> [tools.py] - tools_cputemp()
CPU Load                      -> [tools.py] - tools_cpuload()

Docker Manager                     -> [tools.py] - tools_docker() 
Container Manager		  -> [tools.py] - tools_container()
Image Puller			  -> [tools.py] - tools_image()
Volume Manager                -> [tools.py] - tools_volume()
Network Checker               -> [tools.py] - tools_network()

-------------------------------------------------------------------------------------------

Phase Three - [Installs Menu Functions] **Functions go with thier respected blocks**

Apache2					  -> [installs.py] - installs_apache2()
NginX					  -> [installs.py] - installs_nginx()
Pi-Hole					  -> [installs.py] - installs_pihole()
Pi-Vpn					  -> [installs.py] - installs_pivpn()
Homebridge				  -> [installs.py] - installs_homeb()
Docker					  -> [installs.py] - installs_docker()
OMV					  -> [installs.py] - installs_omv()
Java					  -> [installs.py] - installs_java()
Git					  -> [installs.py] - installs_git()

-------------------------------------------------------------------------------------------

Phase Four - [Extras Menu Functions] **Functions go with thier respected blocks**
						
Minecraft Server Installer         -> [extras.py] - extras_mci()
Crypto Mining Software             -> [extras.py] - extras_cmi()



v.1.0 will contain a total of 

4 Core files
42 differnet functions



