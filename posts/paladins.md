# The absolute state of Paladins
Since almost the entirety of the dev team at Evil Mojo has been laid off, no new updates or patches are planned to come out. As I really loved this game, even though it has been terribly mismanaged by their not-so-beloved publisher Hi-Rez, I find this really sad and wish to continue its legacy over private servers. 
But there's also some funny exploits and bugs still in the game, which will probably never be fixed now.

Starting off with
# EAC bypass
EAC (EasyAntiCheat) is Paladins usermode anticheat which prevents WinApi calls like LoadLibA to prevent dll injection. While there's bypasses for that of course, you can also simply choose not to start the game with EAC at all.. on live servers.. with no downsides. And this works on the current patch with both the Epic Games and Steam version!

How? Simply head to your game files and under `/Binaries/Win64` (Win32 should work just as well), you can start the game as follows:

`Paladins.exe -homedir=paladinslive -EACALT -seekfreeloadingpconsole -allow64 -pid=402 -eac-nop-loaded -replayfile= -COOKFORDEMO -log`
> These parameters work, but not all of them are necessary for this to work (probably)

When starting the game, you will face the old Hi-Rez login, which is usually skipped in the Epic/Steam version. If you wanna use your Epic or Steam account, you will need to create a new Hi-Rez account on their website and link your Epic or Steam account with that account. Then simply enter your Hi-Rez login info within the game and you're in. 

As previously stated, there's no downside to this. All game modes, online play and even ranked work as usual, with the added bonus of having no anticheat and easy DLL injection possibilities.

# Set Border/Title
For some reason, you can set your profile Title and your Loading Frame Border from the client, with the server accepting any input without checking for validity first.

This means, you can equip limited titles such as "Official Paladins Streamer" or even the "Evil Mojo" developer title with a tool like CheatEngine and it will show up for other players in games. 

The same works for Borders, so the Ranked borders could be equipped, or anything really. I personally prefer the "Season 1 Grandmaster" Border. 

> For this, you will need to start the no-EAC version. Otherwise the game will close instantly if you have CheatEngine open.

A list of item ids to equip can be found here: https://www.unknowncheats.me/forum/paladins/588438-item-ids-dump-equip.html

# Speedhack
You can literally speedhack in live games with no punishment or detection and it's not even hard. You can't just speed up the game's tickspeed though. Instead, just send twice (or how many you want) packets to the server and it will happily accept that and project it for every player in the match. 

If you wondered why your games have been so full of cheaters recently, well, that's why. It's just way too easy to cheat.