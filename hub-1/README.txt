===========================================================
FeatherBoard Config Example

Name:		Hub-1
Description: 	This example is made for hub servers.
		it is a simple looking scoreboard that
		shows the command of the server you can
		join with a color (green/red) depending
		on if the server is online/offline.
===========================================================

INSTALLATION
------------
1) 	Copy the contents of CONFIG-BOARD.yml to the board
	of the FeatherBoard config.yml
2)	In the /placeholders/ directory make sure:
	2a)	That placeholder_bungeecord.yml is enabled
	2b)	That placeholder_pinger.yml is enabled
	2c)	That placeholder_pinger.yml returns "&a" when isonline true
	2d)	That placeholder_pinger.yml return "&c" when isonline false