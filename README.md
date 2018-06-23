# Dark Souls REMASTERED: Ogre Anti-Hacker Technology
A script for Dark Souls REMASTERED that allows you to block hackers.

Works on Cheat Engine 6.6 and newer.
I leave the database to the community.

This tool makes use of a database which you can fill in yourself.
I included 2 variants, one checks for your in-game name, the other for your Steam ID.
The database can be changed at any time but keep in mind that you need to restart your game if you wish to remove a person from the list.

The way it works is that when it finds a match (You blacklisted 'HackerMan123' and someone with that very name invades you) it will force a disconnect on them, it works in a similar way if the other player would force-close their game or crash.
If you invade however and find a match, instead the game will disconnect you from their world, cancelling your Co-op/invasion.
When a match happens, the tool will also give you details about the user, providing their in-game name and Steam ID for you to add to your list or share to other users.

To add someone to your list, go to the active players and copy paste their name, the same method is used for their Steam ID.
In case you fail to get their ID, you can go to their profile, get their SteamID from there and convert it into Hexadecimal.
Keep in mind that every entry must be in "quotes" and must end with a comma.

This tool will only check wether you are the host or a phantom, and read the names and ID's of other players. You can also be able to see the level and attributes of the other players. It will not change any of your data and therefore is safe to use.

This tool cannot be used to detect hacking or cheating of any sort, it can only be used to prevent users from connecting with you.

Enjoy!

[Download here](https://github.com/GonthorianDX/DSR_Ogre-_Anti-Hacker_Technology/archive/master.zip)

[Demonstration video](https://youtu.be/MY6cj6MyQII)


-Credits goes to Phokz for the base table + session info and Pavuk for the disconnect scripts.

