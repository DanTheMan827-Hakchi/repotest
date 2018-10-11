# KMFDManic NESC/SNESC Experimental Core/HMOD Set

**Released On:** 2018-10-09

NESC/SNESC Core/HMOD Set is fully merged to work with both the NES, as well as the SNES Classic! (Tremendous Personal Thanks to madmonkey, cluster, pcm720, gpstar, soulctcher, DarkAkuma, DanTheMan827, Melthris, Gingerbeardman, skogaby, 'TheOtherGuys': CompCom, Viral DNA, & Swingflip, Princess Daphie, Xorloser, Doctor Dalek, Defkorns, AceVanquish, Bslenul, shawnsub, asper, ∆ + 0 / 9, shawnsub, DR1001, fr500, twinaphex, gamez-fan, markwkidd, arcadez, wilstorm, dankcusions, hunterk, grant2258, ZappaUtopia, kps501, qclart, AntiFly, justme488, jul car, and of course the libretro team, and the fantastic individuals who have done some truly amazing work for the Scene! And, lastly, anyone else I may not have mentioned that has obviously been invaluable to me in all of my efforts!!!)

**Visit us on Discord, at Nintendo Classics, using the Invite Link:)**

 https://discord.gg/VwaXnNS

 **Alternative Links to my Core Set in Folder Structure:)**

 https://mega.nz/#F!e55DVTqA!jkfylvaQ-6I0Y59Ov1SamA

 https://hakchi.net/KMFDManic/

 **Hakchi2 CE**

 https://github.com/TeamShinkansen/hakchi2/releases/

 **DarkAkuma Canoe Compatibllity Sfrom Tool Link:)**

 http://darkakuma.z-net.us/p/sfromtool.html

 **CompCom's Amazing Options HMOD for RetroArch**

 https://github.com/CompCom/OptionsMenu/releases

 **Qclart's Amiga Guide**

 https://www.reddit.com/r/miniSNESmods/comments/8dbqv7/guide_playing_amiga_games_on_the_snes_classic/

 **10-9-18**

 Thank you all so much for being incredibly patient.  Had power outage yesterday and was unable to post before sleep time!  I also had a few last minute additions and things to clean up and fix!  So, here we go!

 Well, here we are again for yet another incredibly awesome Update!  First, Bullet Points, then Descriptive Notes, then Videos to coincide with this Release, and Final Closing Notes:)  

 - WIP Hakchi2 CE Mod Hub Integration!!!
 - ScummVM Fully Functional!!!
 - gpSP Saves Fixed!!!
 - RetroArch 1.7.5 Xtreme!!!
 - Reicast Xtreme!!!
 - Dreamcast Cheats!!!
 - Final Burn Alpha 2016 Performance Upgrade!!!
 - Beautiful and Glorious Video Game Art!!!
 - NEW Sega Saturn Core with CHD Support (still slow)!!!
 - PPSSPP Xtreme nearly 10 MB Smaller!!!
 - Hatari and Free2JME Removed from Set
 - YouTube Shout-Outs!!!
 - Speaking of HORROR 'Stravaganza & Hardest NES!!!
 - Vice x64 Core Fixed & How to add Games to the Commodore 64 Mini!!!
 - NEO-GEO Mini...Is it worth hacking and modding!!!?
 - Xtreme & Legacy Core Sets!!!
 - WIP!!!

 **Release Notes**

 **WIP Hakchi2 CE Mod Hub Integration!!!**

   Huge personal thanks to DanTheMan827, madmonkey, and Team Shinkansen for incorporating my Core Set into a context menu for the Upcoming Hakchi2 CE Release.  You will still be able to get the Core Set Release, per normal, via Github and the 2 alternative links.  But, you can also use Hakchi2 CE, itself, to "grab" anything from the Main Release that you so choose!  You will also have the nifty ability to "multi-select" Cores!  This will be one of many amazing features and updated perks to the upcoming CE Release!  I am in constant communication with Team Shinkansen and try to adapt every Release to any and all changes made within CE:)  You will notice dates have been removed from the file names, to make updating easier and more intuitive.  For future reference, when troubleshooting with me, just refer to the "date" of the Release Archive Folder that said HMOD comes from and it will be a very easy process!  I will notate the biggest Core changes with each and every future Update, so you are in the know.  The final implementation of how Hakchi2 CE next Release unfolds will be based on testing.  Thank you all for your patience.  Testing is most paramount in anything Released.  If all goes well, the CE Update will roll out in due time.

   **ScummVM Fully Functional!!!**

     I was starting to think this day would never come!  But, low and behold, here we are and here it is!  We now have ScummVM! And, it is fully functional!  Myself (KMFDManic), Beylie, and madmonkey happily bring this to you with very high compatibility due to the extra time put into generating and putting all but 24 known ScummVM games from the most current set into launcher format, as well as getting the Core up and running as optimally as possible!  Huge personal thanks to Yellow and Black 1965, Beylie, and madmonkey for helping with testing!  And, Yellow and Black 1965, you will get more personal thanks in another special video:)

       For those of you are uninitiated, ScummVM stands for Script Creation Utility for Maniac Mansion Virtual Machine.  It is a truly amazing subset of Point and Click Adventure and similarly minded games that has developed quite a cult following over the years! It is a very niche genre and has had more than great success on the most well known games, such as the Monkey Island series...and, of course Maniac Mansion!  Many have become accustomed to the greatness of Maniac Mansion from its prominence on the original Nintendo Entertainment System!  

         To add games for play on the Mini, use Hakchi to add one of the pertinent launcher files.  Make sure the .scummvm file is not compressed by Hakchi.  You can disable compress games when adding, or simply right click and decompress after the fact!  After adding the .scummvm launcher file as a game, navigate to that CLV folder directory, and copy the entire contents of whichever game you choose to play into said folder.  Add art, then synch/export, etc:)  Enjoy:)

	   Launcher wise, there are 3 sets.  One is officially tested, but missing many games!  Two is generated unofficially 
	   tested ones that cover the missing games from the first set.  Three is generated unofficially, also covering by
	   platforms!  In testing, the unofficial sets have been quite reliable.  They have not been fully tested, as of yet.
	   But, you should potentially be able to run all (roughly 435) but 27 games with the unofficial ones!  The officially
	   tested ones are included as back-up, just in case any of you need to use those instead!  We will work on filling in 
	   the gaps for the remaining games!

	     In preliminary tests, saving via "start" ScummVM menu seemed to worked out quite well.  Other methods, such as RetroArch and Suspend States may not work or prove to be unreliable.  You can't type a save game name without a keyboard, but the right shoulder button let's you add the number 5, so that may help to uniquely identify your save games for now.  I delayed this Core Set Release an extra day to ensure you Guys and Gals would be able to play as many games as possible, with better overall optimization and performance and compatibility, as well as had to fix "saves".  We discovered the saves were being deleted upon exiting games and/or shutting down.  I applied a couple adjustments and fixes and they should save with both NAND and USB-HOST (hakchi/saves) now:) 

	       For more info on this Core, check out the ScummVM Videos below the descriptive Release Notes, as well as the ReadMe! in the Xtras/ScummVM Folder.

	         I have also included 8 legal to distribute Freeware Games in the Mega NZ Link, in Xtras/Games/ScummVM.  Since I talk to so many people from a variety of Countries around the world, who speak several different languages...I have decided to do my best to include multiple versions of as many of these Freeware Versions as I possibly could, to cover some of these languages, such as French, German, Spanish, and so on!  Enjoy these awesome games!

		  **gpSP Saves Fixed!!!**

		    As usual, feedback is very important, and several of you came forward stating some GBA games saved and some did not.  It turns out, the reason some were not saving was due to a double extension bug, IE: .gba within .zip.  BsLeNuL was kind enough to come up with a fix which is now applied within this Update!  You will need to install any version of RetroArch Xtreme and gpSP in order for the saves to properly function.

		    **RetroArch 1.7.5 Xtreme & Reicast Xtreme!!!**

		      First of all, there is a new option in RetroArch, under Configuration, to Reset to Defaults.  **Do Not Use This Option** for now.  It will default to expected path perimeters of PC, etc. RetroArch.  Just like with a flash drive, just because an option to "Format" is there, does not mean you should get click happy and use it.  This option could have technically been hidden.  But, there are also a dozen other options that can equally screw things up if you inadvertently mess with them.  Just be careful changing options that you are not familiar with.  Ask, if in doubt.  Learn in the process.  But, again, if you accidentally use this option, do not be too concerned.  You can simply reinstall RetroArch and/or use Load Configuration and select from _RetroArch Defaults, the back-up Configuration I put into place.  It is always a good idea to know exactly what something does before you click it.  I will let you know if anything changes regarding this option.  But, for now, stick to not using it.  

		        Next up, we have a Performance and Compatibility Upgrade for Reicast.  This specific Updated Core is now called Reicast Xtreme, and will ONLY work on RetroArch 1.7.5 Xtreme.  If you try to use it on 1.7.4 it will have not have sound and be prone to C7/C8 Crashes.  But, it works exceptionally well on 1.7.5 Xtreme, and has better and smoother Performance and overall better Compatibility than the non-Xtreme Reicast Core.  Not to mention, keyboard and online support have been added!  In order to use keyboard, you will have to set controller number 1 to keyboard, save the configuration for that specific game, exit, then when you reload game, keyboard will work!  As far as Online, I did not get to fully test this on the Mini as of yet.  But, it works great with Phantasy Star Online V2 on my PC testing!  Hopefully, we will be able to get some decent online matches with Marvel Vs Capcom 2 going!  Once this Update is out, I will play around more with the Online Component!  As always, any and all feedback is greatly appreciated!

			  Standard Reicast Core can be used with RetroArch 1.7.4 Xtreme and Neo.  And, again, Reicast Xtreme can only be used with RetroArch 1.7.5 Xtreme.  Only install one Reicast Core at a time, just like with PPSSPP and PPSSPP Xtreme.    

			  **Dreamcast Cheats!!!**

			    Absolutely love this addition, personally!  You can easily unlock all characters in Marvel Vs Capcom 2, and do many other amazing things in other games with the Dreamcast Cheats!  Have fun!

			    **Final Burn Alpha 2016 Performance Upgrade!!!**

			      Many games will run much better and more optimally.  Try loading up Night Slashers Japan Version (nslasherj), as an example.  I will be doing more performance upgrades for games that were previously stubborn to run, such as this one!  Feel free to request me to look into any!  Do not expect Ninja Baseball Batman and a few other Irem games to benefit, however.  These still run best on MAME 2003 Xtreme!  Enjoy this Update.  More things will change with Final Burn Alpha 2016 in the near future!  

			      **Beautiful & Glorious Video Game Art!!!**

			        You've all seen me use this absolutely beautiful and amazing Video Game Art in my videos over the last 2 years!  I have gotten very special permission to include them with my set:)  I personally thank RetroKenesis for explicit permission to include these truly amazing Art Packs in my Core Set Releases:)  These are the result of hundreds of hours of true dedication and hard work, blood, sweat, and tears...And, it shows in these masterpieces!  Due to our precious size limitations with NAND Internal Flash Memory, the files were losslessly reduced with PNGoo, which is included in Xtras/Tools.  There is not any loss in quality, yet file sizes are much smaller:)

				  They are a permanent fixture in my collection, and now you will all be able to easily enjoy them!  They are in Mega NZ Link, in Xtras/Game Art!!!  I will add more in future Updates!  But, for now, enjoy ones he has done for NES, Sega 32X, Sega-CD AKA Sega Mega-CD, Sega Genesis AKA Sega Mega Drive, Sega Master System, and Turbografx-CD, and so on!!!  Enjoy the mind-blowing art work which will be a true showcase on your Main UI!!!

				    Rubbishmonkey's equally awesome, coverage of some of the more obscure games, translations, hacks, and so on, were included a few Updates back.

				      I have also included Soulctcher's amazing "Cart Art" package for those who want NES/FDS games as they looked once outside the boxes!

				        Since Arcade Games are my life blood and one of the biggest reason I ever got into computers to begin with...I have added a very extensive Arcade Flyer Art Pack, which covers several thousand games!  The very first 2 MAME games I ever emulated via CMD prompts were Michael Jackson's Moonwalker and Sly Spy.  I spent an entire Summer on a 56k AOL connection trying to acquire the entire MAME set.  Prehistoric Isle failed many many times, and was one of the more difficult ones to successfully get!  Download managers did not yet exist.  I have used ClrMAMEPro over the years and have just adjusted my original set to adapt to coding and driver changes since the late 1990s, when I first got into MAME.

					  I will most certainly look into adding many more Art Packs in the very near future, to fill in any other missing Systems!  Feel free to request any and I will add them!  And, you won't necessarily have to wait for an Update either, as I will be hosting these (again) entirely within the Mega NZ Link, in Xtras/Game Art.  So, request away!

					    Keep checking the Mega NZ this link this week, as I will continue to add many more Art Packs!

					    **NEW Sega Saturn Core with CHD Support (still slow)!!!**

					    We now have yet another Sega Saturn Core with full CHD Support.  You can use the Xtras/Tools/CHDMAN set-up I previously put together to easily convert bin+cue, etc. into CHDs!  You will need BIOS for this.  The pertinent files are mpr-17933.bin, sega_101.bin, which can be installed via Master BIOS Module, like any other HMOD.  Simply copy and paste them into the root libretro/system folder!  

					    **PPSSPP Xtreme nearly 10 MB Smaller!!!**

