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