# Growtopia Server ![Build Status](https://ci.appveyor.com/api/projects/status/github/GrowtopiaNoobs/GrowtopiaServer)
First Growtopia Private Server made with ENet by GrowtopiaNoobs.

This project has been compiled with Codeblocks (Link = https://sourceforge.net/projects/codeblocks/files/Binaries/20.03/Windows/codeblocks-20.03mingw-setup.exe)

This project has been published under GNU AFFERO GPL license, so you need to **publish whole source code and citate orginal authors name, even if you are using your server as service**!

**TODO list:**
1. Refactor whole code, it is very hard readable and there might be problems with maintaining it
2. Try get some normal DB working or atleast save all files as BSON or some binary format
3. Write load balancer, it is very CPU expensive part because it calculates BCrypt hashes and access to database
4. Try possible to write multiple servers which only share between themselves possibly world list, player list and boradcast queue
5. Extend data which are saved now - there should be saved current clothes, inventory, login time, register time and maybe tracing hashes if you want to do proper ban system also in worlds there should be saved block extras (enabled, water, fire, etc.) and dropped items
6. Write event pool - this is needed to make delayed actions like respawning
7. Make heavy events asynchronous with possibly some good thread count (probably one or two) and connect them to event pool or use callbacks
8. Disable all loging to console and log everything to file, this will free up console for CLI

If you want to support development of this server, then make sure you contribute to this repo!

Make that sure that you subscribe my channel https://www.youtube.com/channel/UCLXtuoBlrXFDRtFU8vPy35g and enjoy :+1:
