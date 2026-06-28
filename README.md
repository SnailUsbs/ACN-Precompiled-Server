# ACN Precompiled Server
The precompiled server for All City Network so anyone can host a bombrush multiplayer server of their own, without having to learn the steps needed to be able to build the server. This is the perfect option to play with friends, if you don't want to deal with freesoul, other players, or major servers that try and control what mods you can use in game. 


# How To Run The Server (On your device, mainly for friends):
- Download the build from this repo
- Keep everything in the folder, do not remove the exe from it, as it needs to call on the other files in it to run properly 
- Run the "BommbrushMPServer.exe"
- Ensure you have port forwarded a port, with port 41585 being the default option
- A terminal will appear giving you an over view of the server once its running. 
- Close the terminal when you want to close the server.

# How To Run A Major Server MMO Style
- You need to rent a remote server from month
- Best options would be something like DigitalOcean, which will only run you a few dollars per month.
- Depending on your player count, you may need to increase the amount of total power you are renting, but its unlikely based on Freesoul's numbers. 
- After your server is rented, you follow the same steps as above to get the server running. 

# Windows Firewall Issue:
- Windows may auto block the server even when its just running on your local network. To fix this, do the following:

1 - Open Firewall & Network Protection

2 - Click the "Allow An App Through Firewall" option

3 - Click the "change settings" button

4 - Find BombRushMP.ServerApp.exe in the list of options, and check it's box so its enabled to pass through the fire wall

5 - If you dont see the BombRushMP.ServerApp.exe option, click the allow another app option at the bottom, and select your BombRushMP.ServerApp.exe.
